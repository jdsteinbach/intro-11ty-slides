### Layout Aliases

Custom layout names mapped to files/folders

```js
module.exports = eleventyConfig => {
  eleventyConfig.addLayoutAlias(
    'home',
    'views/homeTemplate.njk'
  );
};
