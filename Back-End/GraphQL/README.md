<h1 align="center">
  <a href="https://graphql.org/">
    GraphQL.js
  </a>
</h1>

A query language for your API
---

## 🎉 Building with GraphQL

The reference implementation of the GraphQL specification, designed for running GraphQL in a Node.js environment.

To run a ```GraphQL.js``` hello world script from the command line:

```npm install graphql```

Then run ```node hello.js``` with this code in ```hello.js```:

```
var { graphql, buildSchema } = require('graphql');

var schema = buildSchema(`
  type Query {
    hello: String
  }
`);

var root = { hello: () => 'Hello world!' };

graphql(schema, '{ hello }', root).then((response) => {
  console.log(response);
});
```
