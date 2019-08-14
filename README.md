
Plugin is the same as [html-webpack-injector](https://github.com/thearchitgarg/html-webpack-injector)

```bash
  npm i --save-dev html-webpack-injector-leo
```
#

<h2 align="center">difference</h2>

`html-webpack-injector`
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>demo</title>
    <script type="text/javascript" src="scriptA.js"></script>
  </head>
  <body>
    <link href="styles/mainA.css" rel="stylesheet" />
    <script src="scriptB.js"></script>
  </body>
</html>
```

`html-webpack-injector-leo`
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>demo</title>
    <link href="styles/mainA.css" rel="stylesheet" />
    <script type="text/javascript" src="scriptA.js"></script>
  </head>
  <body>
    <script src="scriptB.js"></script>
  </body>
</html>
```
#
just put the `.css` in `<head>`
