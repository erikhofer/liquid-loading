# Liquid Loading

![Build](https://github.com/erikhofer/liquid-loading/workflows/Build/badge.svg) [![npm version](https://badge.fury.io/js/liquid-loading.svg)](https://badge.fury.io/js/liquid-loading)

<p align="center">
  <img alt="Preview" src="https://user-images.githubusercontent.com/17194301/89186073-98e4cc80-d59b-11ea-9895-64f21e58b037.gif" />
  <br />
  <a href="https://erikhofer.github.io/liquid-loading/">Demo</a>
</p>

## Usage

This is a Web Component. Just install and import it, somewhere in your app.

```
npm install liquid-loading
```

### Example with React (with TypeScript support)

```jsx
import React from "react";
import ReactDOM from "react-dom";
import "liquid-loading";

ReactDOM.render(
  <liquid-loading></liquid-loading>,
  document.getElementById("root")
);
```

### Example with plain HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://unpkg.com/liquid-loading"></script>
  </head>
  <body>
    <liquid-loading></liquid-loading>
  </body>
</html>
```

## License

This is a wrapper around [a CodePen project](https://codepen.io/ainalem/pen/eYmGLyp) by Mikael Ainalem. It is thus published under the original [license](https://github.com/erikhofer/liquid-loading/blob/master/LICENSE).
