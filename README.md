NTJS Web Assets Repository
==========================

This is a collection of web assets used by [NODE-NTJS](https://github.com/tohenk/node-ntjs).

Example usage using express app:
```js
const express = require('express');
const { Assets } = require('@ntlab/ntjs-assets');

const app = express();
app.use(express.static(Assets));
```