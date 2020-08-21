# List DOM

## Installation and Setup

Install with npm:

```
npm i list-dom
```

Install with CDN:

```html
<script src="https://a-angelov.eu/packages/list-dom/cdn/list-dom.js"></script>
```


import js in your project

```js
import ListDOM from 'list-dom';
```

Template:

```js
ListDOM({
  run: ['forEach', 'map', 'filter', 'some', 'find'],
})
```

### Usage

Basic exmaple

```js
ListDOM({
  methods: ['forEach'],
})
```

methods property accepts an Array of desired methods.

If you have errors after calling the ListDOM function, try to run test on the methods you want to use:

```js
ListDOM({
  methods: ['forEach', 'map'],
  test: ['forEach', 'map'],
})
```

You can always run the test while also attempting to add desired methods by using "run"

```js
ListDOM({
  run: ['forEach', 'map'],
})

