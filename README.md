## Nightwatch.js project template

[Nightwatch.js](http://nightwatchjs.org/) is an easy to use Node.js based End-to-End (E2E) testing solution for browser based apps and websites. It uses the powerful W3C WebDriver API to perform commands and assertions on DOM elements.

A good introduction to learn [Nightwatch.js](http://nightwatchjs.org/) can be found at [Learn how to use Nightwatch.js](https://github.com/dwyl/learn-nightwatch)

### Quick install

1) Clone poject

```
git clone https://github.com/dismorfo/test.git
```

2) Add enviorment information file

```
cp sample.env .env
```

3) Install the project using NPM. Inside the same folder that has the package.json

```
npm install 
```

NOTE: *You need to have in your system [Node.JS](https://nodejs.org/en/) to install [Nightwatch.js](http://nightwatchjs.org/)

Other) One-liner

``git clone https://github.com/dismorfo/test.git && cd test && cp sample.env .env && npm install``



### Running test

4) Inside the same folder that has the nightwatch.conf.js type:

```
npm test
```
