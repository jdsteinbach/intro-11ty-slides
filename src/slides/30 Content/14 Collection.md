### Collections

Create an array from `.md` {% link "Collections" "https://www.11ty.dev/docs/collections/" %}

```js
eleventyConfig.addCollection(
  'nav',
  collection => collection.getAll()
    .filter(item => {})
    .sort((a, b) => {})
  }
);
```
