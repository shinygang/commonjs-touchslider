
This is a fork based on [TouchSlide](http://www.superslide2.com/TouchSlide/).

```
npm install --save commonjs-touchslider
```

```js
var touchslider = require('commonjs-touchslider')
```

How I made this:


```diff
-
-var TouchSlide=module.exports =
-
-
+// @@ original loader
+// var TouchSlide=
+// @@ modified by shinygang
+var TouchSlide=module.exports =
+// @@ modifications end
```