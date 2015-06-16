# polymer-observe

Gives you Object.observe back in Polymer 1.0

## Example

```html
<dom-module id="demo-element">
  <template>
    <polymer-observe property="{{foo}}"></polymer-observe>

    <p>foo.bar.baz: <span>{{foo.bar.baz}}</span>

  </template>
</dom-module>
```

## Testing

Run `polyserve` and open `http://localhost:8080/components/polymer-observe/test/` in your browser.

## Browser Support

This requires [Object.observe()](http://caniuse.com/#feat=object-observe).
