### Content from an API

Get an array from an API {% link "Data from an API" "https://www.11ty.dev/docs/data-js/#using-js-data-files" %}
```js
// _data/posts.js
module.exports = () => {
  return new Promise(() => {
    // Make a request
    // `resolve` the returned data
  });
};
```
