# Error: TextKeyNotAllowed

A key was provided to the `data-text` attribute. The `data-text` attribute must _only_ have a value, representing an expression that is evaluated used as the text content of the element.

Example:

```html
<div data-text="foo.value"></div>
```

See the docs on the [`data-text`](https://data-star.dev/reference/plugins_dom#text) attribute.