# BEAUBUS Patterns plugin for TailwindCSS

![npm](https://img.shields.io/npm/dt/@beaubus/svg-patterns-for-tailwindcss?logo=npm)

A plugin that provides [140+ free svg patterns](https://patterns.beaubus.com) you can use as background image with utility classes.

![](demo.gif)

## Installation

Install the plugin from npm
```bash
npm i @beaubus/svg-patterns-for-tailwindcss
```

Then add the plugin to your `tailwind.config.js` file:
``` js
// tailwind.config.js
module.exports = {
  // ...
  plugins: [
    require('@beaubus/svg-patterns-for-tailwindcss'),
    // ...
  ],
}
```

## Usage
Now you can use the `bbp-` classes with pattern name from [BEAUBUS Patterns](https://patterns.beaubus.com) to add `background-image` to html elements:
```html
<body class="bbp-blue-wallpaper">
    <div class="bbp-moment"></div>
</body>
```
