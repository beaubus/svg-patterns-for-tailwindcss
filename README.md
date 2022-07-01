# BEAUBUS Patterns plugin for Tailwind CSS

<a href="https://www.npmjs.com/package/@beaubus/svg-patterns-for-tailwindcss">
    <img src="https://img.shields.io/npm/dt/@beaubus/svg-patterns-for-tailwindcss?logo=npm" alt="npm downnloads count">
</a>

<a href="https://github.com/beaubus/svg-patterns-for-tailwindcss/blob/master/LICENSE">
    <img alt="MIT" src="https://img.shields.io/github/license/beaubus/svg-patterns-for-tailwindcss">
</a>
&nbsp;&nbsp;
<a href="https://twitter.com/intent/follow?screen_name=daily_web_dev">
    <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/daily_web_dev?style=social">
</a>

<br>
<br>

A plugin that provides [200+ free svg patterns](https://patterns.beaubus.com) you can use as background image with utility classes.

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
