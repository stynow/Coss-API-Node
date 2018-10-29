# Coss-API-Node

A modular, open source/free use wrapper written in node.js for the coss.io API. All functionalities have been tested and work. API keys set as vars w/i index.js (for the time being). Bot.js serves as an example of how to call all of the wrapper's functions; every API call function returns the res.body response from the server as an object when the function is called (excluding getMarketSides() which returns a nested array formatted as such: [[firstBidPrice, firstBidQuantity][firstAskPrice, firstAskQuantity]].

#### Installation

* Ensure you have Node.js installed:
https://nodejs.org/en/download/

* Clone repository
```
$ git clone https://github.com/cryptodeal/Coss-API-Node

```
* Install dependencies

```
$ npm install
```

* Start the example app

```
$ npm start
```


For any inquiries about use, please contact the developer: telegram @cryptodeal20

TODO: 
1. Write up more thorough documentation beyond the examples in bot.js 
2. Add set Options function, so keys can be set from bot.js 
3. Publish as npm package
