# Hello World

LoopBack extends express... anything you can do with express you can do with LoopBack.

```js
// express hello world
var express = require('express');
var app = express();

app.get('/', function(req, res) {
  res.send('hello world');
});
```

```js
// loopback hello world
var loopback = require('loopback');
var app = loopback();

app.get('/', function(req, res) {
  res.send('hello world');
});
```

