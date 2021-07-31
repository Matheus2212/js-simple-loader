# js-simple-loader

Vanilla JS Simple Loader

## How to Use

Import the CSS and JS files on your webpage and use one of the codes bellow:

```javascript
Loader.open();

Loader.close();

Loader.ifClosed(function () {
  //some callback here;
}, "openLoader");

Loader.ifOpened(function () {
  //some callback here;
}, "closeLoader");
```
