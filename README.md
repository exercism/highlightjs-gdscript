# GDScript syntax for highlight.js

Syntax implementation of [Godot](https://godotengine.org/)'s GDScript language for [highlight.js](https://github.com/highlightjs/highlight.js).

This repo is a fork of [highlightjs/highlightjs-gdscript](https://github.com/highlightjs/highlightjs-gdscript).

### Usage

#### Using CommonJS

```javascript
const hljs = require("highlight.js");
const gdscript = require("@exercism/highlightjs-gdscript");

hljs.registerLanguage("gdscript", gdscript);
```

#### Using ES6

```javascript
import hljs from "highlight.js";
import gdscript from "@exercism/highlightjs-gdscript";

hljs.registerLanguage("gdscript", gdscript);
```
