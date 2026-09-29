---
CoinsCopper:
CoinsSiler:
CoinsElectrum:
CoinsGold: 250
CoinsPlatinum:
PartySize: 3
---
# Amount
 
 | Type     | Input                         | Kupfer                       | Silber                      | Electrum                   | Gold                       | Platin                   |
 | -------- | ----------------------------- | ---------------------------- | --------------------------- | -------------------------- | -------------------------- | -------------------------- |
 | Kupfer   | `INPUT[number:CoinsCopper]`   | `VIEW[{CoinsCopper}]`        | `VIEW[{CoinsCopper}/10]`    | `VIEW[{CoinsCopper}/50]`   | `VIEW[{CoinsCopper}/100]`  | `VIEW[{CoinsCopper}/1000]` |
 | Silber   | `INPUT[number:CoinsSiler]`    | `VIEW[{CoinsSiler}*10]`      | `VIEW[{CoinsSiler}]`        | `VIEW[{CoinsSiler}/5]`     | `VIEW[{CoinsSiler}/10]`    | `VIEW[{CoinsSiler}/100]`   |
 | Electrum | `INPUT[number:CoinsElectrum]` | `VIEW[{CoinsElectrum}*50]`   | `VIEW[{CoinsElectrum}*5]`   | `VIEW[{CoinsElectrum}]`    | `VIEW[{CoinsElectrum}/2]`  | `VIEW[{CoinsElectrum}/20]` |
 | Gold     | `INPUT[number:CoinsGold]`     | `VIEW[{CoinsGold}*100]`      | `VIEW[{CoinsGold}*10]`      | `VIEW[{CoinsGold}*2]`      | `VIEW[{CoinsGold}]`        | `VIEW[{CoinsGold}/10]`     |
 | Platin | `INPUT[number:CoinsPlatinum]` | `VIEW[{CoinsPlatinum}*1000]` | `VIEW[{CoinsPlatinum}*100]` | `VIEW[{CoinsPlatinum}*20]` | `VIEW[{CoinsPlatinum}*10]` | `VIEW[{CoinsPlatinum}]`    | 
 
 ## Totaler Wert
 
 Party grösse: `INPUT[number:PartySize]`  
 
 | Type     | Total                                                                                                          | Total Per Player                                                                                                    |
 | -------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
 | Kupfer   | `VIEW[{CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000)]`          | `VIEW[({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/{PartySize}]` | 
 | Silber   | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/10)]`   | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/10)/{PartySize}]`                                                                                                                    |
 | Electrum | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/50)]`   | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/50)/{PartySize}]`                                                                                                                    |
 | Gold     | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/100)]`  | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/100)/{PartySize}]`                                                                                                                    |
 | Platin | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/1000)]` | `VIEW[(({CoinsCopper}+({CoinsSiler}*10)+({CoinsElectrum}*50)+({CoinsGold}*100)+({CoinsPlatinum}*1000))/1000)/{PartySize}]`       

