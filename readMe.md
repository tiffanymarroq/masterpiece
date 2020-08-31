# Masterpiece

Masterpiece is a responsive single page app
### Installation

Install the dependencies and devDependencies and start the server.

```sh
$ npm install 
$ npm start
```

### Build

Install the dependencies and devDependencies and start the server.

```sh
$ gulp inject
```
The final file will be in assemble.html


## Structure
Variables:
- `state` (object): This is used to update global values in the app
- `masterpieceData` (object): Used to create sub pages. This is the main data set for the app.

Init: 
- Starts on `document.ready()`
- Then runs `initMasterpiece()`

Home Page:
- Page: `homepage()`
- Menu: `homepageMenu()`
- Tiles: `homepageProductList()`

Category Page:
- Page: `productPage()`
- Hero Section: `productInfo()`
- Related Product Section: `relatedProducts()`
- Product Tiles: `getRelatedProduct()` (static) and `getProductData()` (api)
- Articles: `topArticles()`

Error Page: 
- Page: `errorPage()`

## Tracking
- `masterpieceGA()`
- `$(document).on('click', '.js-trackEvent', function (e) { ... } `




