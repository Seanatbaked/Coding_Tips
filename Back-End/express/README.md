<h1 align="center">
  <a href="https://expressjs.com">
    Express
  </a>
</h1>

Express -- Fast, unopinionated, minimalist web framework for node.
---

## 📋 What is Express?

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications

## 🎉 How to use Express

Before installing, download and install Node.js. Node.js 0.10 or higher is required.

Installation is done using the ```npm install``` command:

```$ npm install express```


```
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```
