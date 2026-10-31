```dataviewjs
const srdCounts = new Map();

const categoryCounts = new Map();

for (const page of dv.pages()) {

  if (page.file.path.startsWith("z_Templates/")) continue;

  for (const raw of (page.file.tags ?? [])) {

    const tag = (raw.startsWith("#") ? raw.slice(1) : raw).toLowerCase();

    if (tag.startsWith("srd/")) {

      const name = tag.slice(4); // entfernt "srd/"

      srdCounts.set(name, (srdCounts.get(name) ?? 0) + 1);

    }

    if (tag.startsWith("category/")) {

      const name = tag.slice(9); // entfernt "category/"

      categoryCounts.set(name, (categoryCounts.get(name) ?? 0) + 1);

    }

  }

}

// Alle Kategorien sammeln

const labels = [

  ...new Set([

    ...srdCounts.keys(),

    ...categoryCounts.keys()

  ])

].sort((a, b) => {

  const totalA = (srdCounts.get(a) ?? 0) + (categoryCounts.get(a) ?? 0);

  const totalB = (srdCounts.get(b) ?? 0) + (categoryCounts.get(b) ?? 0);

  return totalB - totalA;

});

const srdData = labels.map(label => srdCounts.get(label) ?? 0);

const categoryData = labels.map(label => categoryCounts.get(label) ?? 0);

const chartData = {

  type: 'bar',

  data: {

    labels,

    datasets: [

      {

        label: 'SRD',

        data: srdData,

        backgroundColor: 'gold',

      },

      {

        label: 'Category',

        data: categoryData,

        backgroundColor: 'steelblue',

      }

    ]

  },

  options: {

    responsive: true,

    scales: {

      y: {

        beginAtZero: true

      }

    }

  }

};

if (window.renderChart) {

  window.renderChart(chartData, this.container);

} else {

  dv.paragraph("⚠️ No renderChart() found.");

}
```

