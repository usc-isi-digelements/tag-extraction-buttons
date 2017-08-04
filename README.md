# tag-extraction-buttons

A Polymer Element showing buttons to classify an extraction as either positive (correct) or negative (incorrect).

### Example
```js
var classification = {
  database: 'positive',
  type: 'ad',
  user: ''
};
```

```html
<tag-manager tag-manager="{{tagManager}}"></tag-manager>
<tag-extraction-buttons
  classification="[[classification]]"
  tag-manager="[[tagManager]]">
</tag-extraction-buttons>
```

### Styling

`<tag-extraction-buttons>` provides the following custom properties and mixins for styling:

Custom property                     | Description                                       | Default
------------------------------------|---------------------------------------------------|--------
`--tag-button-color`                | The color of the untagged buttons.                | paper-grey-600
`--tag-button-negative-color`       | The color of the negatively tagged buttons.       | paper-red-600
`--tag-button-negative-hover-color` | The hover color of the negatively tagged buttons. | paper-red-900
`--tag-button-positive-color`       | The color of the positively tagged buttons.       | paper-green-600
`--tag-button-positive-hover-color` | The hover color of the positively tagged buttons. | paper-green-900

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

