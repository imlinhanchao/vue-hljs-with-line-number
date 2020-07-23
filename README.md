# vue-hljs-with-line-number

[Vue.js](https://vuejs.org/) syntax highlighting made easy, using [highlight.js](https://highlightjs.org/).

[![Build Status](https://travis-ci.org/metachris/vue-hljs-with-line-number.svg?branch=master)](https://travis-ci.org/metachris/vue-hljs-with-line-number)

## Quickstart

### Installation

Simply install the [npm package `vue-hljs-with-line-number`](https://www.npmjs.com/package/vue-hljs-with-line-number):

```bash
npm install --save vue-hljs-with-line-number
```

### Using vue-highlightjs

In your main JavaScript file (eg. `main.js`):

```javascript
// Import Vue and vue-highlgihtjs
import Vue from 'vue'
import VueHljs from 'vue-highlightjs'
import 'vue-hljs-with-line-number/line-number.css';

// Tell Vue.js to use vue-hljs-with-line-number
Vue.use(VueHljs)
```

In your template, in order to highlight javascript code:

```html
<!-- If your source-code lives in a variable called 'sourcecode' -->
<pre v-hljs="sourcecode">
    <code class="javascript"></code>
</pre>

<!-- If you want to highlight hardcoded source-code -->
<pre v-hljs>
    <code class="javascript">
    const s = new Date().toString()
    </code>
</pre>
```
---

## About

Author: 
Chris Hager <chris@linuxuser.at> (https://www.metachris.com)  

License: MIT

Contributors:

* [Chris Hager](https://www.metachris.com)
* [mr-krille](https://github.com/mr-krille)
* [Duoc Nguyen](https://github.com/nguyenvanduocit)
* [Shu Ding](https://github.com/shudin)
* [Hancel Lin](https://github.com/imlinhanchao)

## Changelog

v1.0.0

- Since the original author is no longer updating, it needs to fork the warehouse to open another npm package. Add the line-number feature. Line-number feature reference warehouse [highlightjs-line-numbers.js](https://github.com/wcoder/highlightjs-line-numbers.js/) Extract and modify part of the code for Vue-compatible processing.
