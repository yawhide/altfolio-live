# Altfolio.Live

A react + websocket app to help track of a mixed portfolio of stocks and cryptocurrencies in realtime

![image](https://user-images.githubusercontent.com/1296162/35300381-13b0dfb2-003d-11e8-9498-eec57f29355f.png)

## Run locally
1. `npm i`
2. `npm start`
3. In a new terminal tab, `node api/api.js`
4. In a new terminal tab, `node api/crypto-worker.js`
5. In a new terminal tab, `node api/stock-worker.js`
6. In a new terminal tab, `node api/stock-historical-backfill.js`
7. Go to `localhost:3000`

## Contributing
Feel free to open a pull request to add functionality

## License
Altfolio is [MIT licensed](LICENSE).
