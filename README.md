# BEAUBUS Patterns plugin for TailwindCSS

A plugin that provides 140+ svg patterns you can use as background image with utility classes.

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
