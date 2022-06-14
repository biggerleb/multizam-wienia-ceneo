# Multizamówienia z Ceneo
Web app that makes it possible to find one shop with several products using data from ceneo.pl service (one delivery = less problem, less money spent on delivery services). User can search for wanted products, click on names of proposed products to open ceneo.pl page for given product, when 2 or more products are picked user can search for shops with all of the picked products in stock.

Scraping API was made by github.com/bogk9

Live version available at https://multizamowienia-ceneo.herokuapp.com/ , first request to API may take some time, due to necessity of "waking-up" free heroku dyno.
### Prerequisites for running this app on your local machine
In installation steps I will assume that you have installed NPM
### Installation
Create app with Create React App
```
npx create-react-app multizamowienia-ceneo
```
In mini-spotify directory delete all files and directories except node-modules directory, then paste there everything from this repository, then run
```
npm install
```
And to run this app on local server run
```
npm start
```
##### Built with React
