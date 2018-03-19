# Boilerplate Marvin Packet

A boilerplate to create a packet for [Marvin](https://github.com/marvin-js/marvin).

Packet is the same that [create a plugin](https://github.com/marvin-js/boilerplate-marvin-plugin), but is a array of plugin.

The `index.js` of package:

```javascript

var plugin1 = require('./plugin1');
var plugin2 = require('./plugin2');

module.exports = {
  plugin1: plugin1,
  plugin2: plugin2,
};
```
