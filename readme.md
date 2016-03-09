rdef
====
Require default. Returns default property after require module.  
Useful for using requiring `default export` value from ES6 modules.

INSTALL
-------
```sh
nmp i rdef
```

USAGE
-----
```js
const rdef = require("rdef");
var x = rdef("./some_module"); // equivalent to `require("./some_module").default`
```