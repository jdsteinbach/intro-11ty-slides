### Shortcodes

```js
eleventyConfig.addShortcode(
  'link',
  (title, url) => {
    return `<a href="${url}" class="link">${title}</a>`;
  }
);
```
