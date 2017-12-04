# koa-openapi-ui

Koa middleware for generating UI from an OpenAPI 2.0 specification.

## Installation

npm

```
$ npm install koa-openapi-ui
```

yarn

```
$ yarn add koa-openapi-ui
```

## Usage

```js
const Koa = require('koa');
const openapiUi = require('koa-openapi-ui');

const app = new Koa();

app.use(body());
app.use(openapiUi({ path: '/spec', filepath: __dirname + '/spec.yaml' }));

...
```

## License
MIT
