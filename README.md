# Doge UiPath

A simple crypto trading bot using DogeCoin testnet, UiPath, sochain.com price data to simulate trading dogecoin and tracking data via csv.

![Alt Text](https://github.com/mtclinton/doge-uipath/raw/main/uipath.gif)

## Description of UiPath Robot
1. Demo shows csv file with empty price data.
2. UiPath robot visits sochain.com for dogecoin price and writes to purchase price csv column.
3. UiPath robot creates wallet address named "uipath address"
4. UiPath robot visits Dogecoin testnet faucet and submits wallet address to receive testnet coins
5. UiPath robot visits different testnet site to return coins. The robot copys the site's wallet address.
6. UiPath robot sends coins to testnet site using dogecoin testnet wallet.
7. UiPath robot visits sochain.com for dogecoin price for sell price
8. UiPath robot reads csv data and compares purchase price to sell price for loss/gain.
9. UiPath robot writes sell price and loss/gain to csv.
