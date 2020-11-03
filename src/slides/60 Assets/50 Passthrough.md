### File Passthrough {% link "Passthrough Copy" "https://www.11ty.dev/docs/copy/" %}

```js
eleventyConfig.addPassthroughCopy(
  'src/fonts'
);
eleventyConfig.addPassthroughCopy({
  'src/assets/site.js': 'js/site.js'
});
```
