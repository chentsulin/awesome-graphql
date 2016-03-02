# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL & Relay

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
- [Libraries](#lib)
	- [Javascript](#lib-js)
	- [Ruby](#lib-rb)
	- [PHP](#lib-php)
	- [Python](#lib-py)
	- [Java](#lib-java)
	- [C/C++](#lib-c)
	- [Go](#lib-go)
	- [Scala](#lib-scala)
	- [.NET](#lib-dotnet)
	- [Elixir](#lib-elixir)
	- [Haskell] (#lib-haskell)
	- [SQL](#lib-sql)
	- [Lua](#lib-lua)
- [Tools](#tools)
- [Services](#services)
- [Examples](#example)
	- [Javascript](#example-js)
	- [Ruby](#example-rb)
	- [Go](#example-go)
	- [Scala](#example-scala)
	- [Python](#example-python)
	- [Elixir](#example-elixir)
- [Videos](#video)
- [Posts](#post)
- [Workshoppers](#workshopper)

<!-- /MarkdownTOC -->

<a name="spec" />
## Specification

* [facebook/graphql](http://facebook.github.io/graphql/) - Working Draft of the Specification for GraphQL created by Facebook.

<a name="lib" />
## Libraries

<a name="lib-js" />
### JavaScript Libraries

* [GraphQL.js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
* [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware.
* [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
* [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
* [codemirror-graphql](https://github.com/graphql/codemirror-graphql) - GraphQL mode and helpers for CodeMirror.
* [graphql-schema](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface.
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
* [graffiti](https://github.com/RisingStack/graffiti) - Node.js GraphQL ORM.
* [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) - Mongoose (MongoDB) adapter for graffiti (Node.js GraphQL ORM).
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
* [adrenaline](https://github.com/gyzerok/adrenaline) - React bindings for Redux with Relay in mind.
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
* [graph.ql](https://github.com/matthewmueller/graph.ql) - Faster and simpler technique for creating and querying GraphQL schemas.
* [react-reach](https://github.com/kennetpostigo/react-reach) - A library to communicate with Graphql through Redux
* [Lokka](https://github.com/kadirahq/lokka) - Simple JavaScript client for GraphQL, which you can use anywhere.
* [Strapi](http://strapi.io/documentation/graphql) - Open-source Node.js framework that supports "GraphQL" out of the box.
* [GraysQL](https://github.com/larsbs/graysql) - A GraphQL manager and loader.
* [graysql-orm-loader](https://github.com/larsbs/graysql-orm-loader) - A GraysQL extension to load a GraphQL schema from an ORM.
* [Annotated GraphQL](https://github.com/almilo/annotated-graphql) - Proof of Concept for annotations in GraphQL (i.e.: transform an existing REST api into a GraphQL endpoint).

##### Relay Related

* [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
* [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
* [sequelize-relay](https://github.com/MattMcFarland/sequelize-relay) - Serverside library that connects sequelize and graphql-relay-js together.
* [babel-relay-plugin](https://www.npmjs.com/package/babel-relay-plugin) - Babel Relay Plugin for transpiling GraphQL queries for use with Relay.
* [react-router-relay](https://github.com/relay-tools/react-router-relay) - Relay integration for React Router.
* [relay-local-schema](https://github.com/relay-tools/relay-local-schema) - Use Relay without a GraphQL server.
* [relay-sink](https://github.com/acdlite/relay-sink) - Use Relay to fetch and store data outside of a React component.
* [recompose-relay](https://github.com/acdlite/recompose/tree/master/src/packages/recompose-relay) - Recompose helpers for Relay.
* [Graylay](https://github.com/larsbs/graysql#Graylay) - A GraysQL extension to create a Relay compatible Schema.

<a name="lib-rb" />
### Ruby Libraries

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
* [graphql-relay-ruby](https://github.com/rmosolgo/graphql-relay-ruby) - Relay helpers for GraphQL & Ruby.
* [graphql-parser](https://github.com/Shopify/graphql-parser) - A small ruby gem wrapping the libgraphqlparser C library for parsing GraphQL.

<a name="lib-php" />
### PHP Libraries

* [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
* [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for GraphQL & PHP.
* [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5.
* [laravel-graphql-relay](https://github.com/nuwave/laravel-graphql-relay) - A Laravel library to help construct a server supporting react-relay.
* [graphql-mapper](https://github.com/4rthem/graphql-mapper) - This library allows to build a GraphQL schema based on your model.
* [graphql-bundle](https://github.com/suribit/GraphQLBundle) - GraphQL Bundle for Symfony 2.

<a name="lib-py" />
### Python Libraries

* [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
* [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python.
* [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
* [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
* [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
* [django-graphiql](https://github.com/graphql-python/django-graphiql) - Integrate GraphiQL easily into your Django project.
* [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.

<a name="lib-java" />
### Java Libraries

* [graphql-java](https://github.com/andimarek/graphql-java) - GraphQL Java implementation.

<a name="#lib-c" />
### C/C++ Libraries

* [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.

<a name="lib-go" />
### Go Libraries

* [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js
* [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
* [graphql](https://github.com/tmc/graphql) - GraphQL parser and server for Go.
* [c-graphqlparser](https://github.com/tecbot/c-graphqlparser) - Go-gettable version of the libgraphqlparser C library for parsing GraphQL.
* [tallstreet-graphql](https://github.com/tallstreet/graphql) - GraphQL parser and server for Go that leverages libgraphqlparser

<a name="lib-scala" />
### Scala Libraries

* [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL client and server library.
* [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
* [graphql-scala](https://github.com/hrosenhorn/graphql-scala) - An attempt to get GraphQL going with Scala.

<a name="lib-dotnet" />
### .NET Libraries

* [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.

<a name="lib-elixir" />
### Elixir Libraries

* [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
* [graphql](https://github.com/asonge/graphql) - Elixir graphql library.
* [graphql-elixir](https://github.com/joshprice/graphql-elixir) - GraphQL parser for Elixir.
* [graphql_parser](https://github.com/aarvay/graphql_parser) - Elixir bindings for [libgraphqlparser](https://github.com/graphql/libgraphqlparser)
* [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.
* [plug_graphql](https://github.com/joshprice/plug_graphql) - Phoenix Plug integration for GraphQL Elixir

<a name="lib-haskell" />
### Haskell Libraries

* [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.

<a name="lib-sql" />
### SQL Libraries

* [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
* [sql-to-graphql](https://github.com/vaffel/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.

<a name="lib-lua" />
### Lua Libraries

* [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="tools" />
## Tools

* [graphiql](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
* [GraphiQL.app](https://github.com/skevy/graphiql-app) - A light, Electron-based wrapper around GraphiQL.
* [GraphQLviz](https://github.com/Macroz/GraphQLviz) - GraphQLviz marries GraphQL (schemas) with Graphviz.
* [Relay Playground](http://facebook.github.io/relay/prototyping/playground.html)
* [GraphQL AST Explorer](http://dferber90.github.io/graphql-ast-explorer/) - Explore the AST of a GraphQL document interactively
* [GraphQLHub](https://www.graphqlhub.com/) - Query public API's schemas (e.g. Reddit, Twitter, Github, etc) using GraphiQL
* [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
* [gdom](https://github.com/syrusakbary/gdom) - DOM Traversing and Scraping using GraphQL.
* [Annotated GraphQL Server](https://github.com/almilo/annotated-graphql-server) - Server for annotated GraphQL showing how to transform a REST api into a GraphQL endpoint with annotations.

<a name="services" />
## Services

* [Reindex](https://www.reindex.io/) - Instant GraphQL Backend for Your React Apps.

<a name="example" />
## Examples

<a name="example-js" />
### JavaScript Examples

* [relay-starter-kit](https://github.com/relayjs/relay-starter-kit) - Barebones starting point for a Relay application.
* [react-starter-kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate (Node.js/Express, GraphQL, React)
* [swapi-graphql](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping [swapi](http://swapi.co/).
* [graphql-server](https://github.com/RisingStack/graphql-server) - GraphQL server with Mongoose (MongoDB) and Node.js.
* [graphql-intro](https://github.com/clayallsopp/graphql-intro) - https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2
* [graphql-aws](https://github.com/jonsharratt/graphql-aws) - Amazon AWS GraphQL API Server.
* [graffiti-todo](https://github.com/RisingStack/graffiti-todo) - Example Relay TodoMVC application using graffiti-mongoose.
* [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
* [codefoundries/isomorphic-material-relay-starter-kit](https://github.com/codefoundries/isomorphic-material-relay-starter-kit) - Isomorphic Relay with authentication using JWT, Material-UI.
* [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql)
* [relay-skeleton](https://github.com/fortruce/relay-skeleton) - React, Relay, GraphQL project skeleton
* [simple-relay-starter](https://github.com/mhart/simple-relay-starter) - A very simple starter for React Relay using Browserify.
* [relay-chat](https://github.com/transedward/relay-chat) - an chat example showing Relay with routing and pagination.
* [relay-todomvc](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing.
* [graphql-express-sqlite](https://github.com/mrblueblue/graphql-express-sqlite) - GraphQL server with Sqlite and Express
* [koa-graphql-relay-example](https://github.com/chentsulin/koa-graphql-relay-example) - Example of [koa-graphql](https://github.com/chentsulin/koa-graphql)
* [relay-fullstack](https://github.com/lvarayut/relay-fullstack) - Relay Starter Kit integrated with Relay, GraphQL, Express, ES6/ES7, JSX, Webpack, Babel, Material Design Lite, and PostCSS.
* [serverless-graphql-blog](https://github.com/serverless/serverless-graphql-blog) - A Serverless Blog leveraging GraphQL to offer a REST API with only 1 endpoint



<a name="example-rb" />
### Ruby Examples

* [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.

<a name="example-go" />
### Go Examples

* [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
* [golang-graphql-playground](https://github.com/graphql-go/playground) - An example Golang GraphQL server written with graphql-go and graphql-relay-go. Try live demo at: http://golanggraphqlplayground-sogko.rhcloud.com
* [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.

<a name="example-scala" />
### Scala Examples

* [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](http://sangria-graphql.org)
* [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="example-python" />
### Python Examples

* [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](http://graphene-python.org) - [View demo online](http://swapi.graphene-python.org).

<a name="example-elixir" />
### Elixir Examples

* [absinthe_example](https://github.com/absinthe-graphql/absinthe_example) - Example usage of Absinthe GraphQL
* [hello_graphql_phoenix](https://github.com/joshprice/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix - [View demo online](http://playground.graphql-elixir.org).

<a name="video" />
## Videos

* [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
* [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
* [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
* [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
* [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
* [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
* [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
* [Introduction to GraphQL](https://vimeo.com/144817545)
* [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
* [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
* [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
* [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)

<a name="post" />
## Posts

* [Introducing Relay and GraphQL](https://facebook.github.io/react/blog/2015/02/20/introducing-relay-and-graphql.html)
* [GraphQL Introduction](http://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)
* [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
* [Your First GraphQL Server](https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2)
* [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
* [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
* [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
* [Start using GraphQL with Graffiti](https://blog.risingstack.com/start-using-graphql-with-graffiti/?utm_source=nodeweekly&utm_medium=email)
* [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
* [GraphQL at The Financial Times](http://www.slideshare.net/LondonReact/graph-ql?ref=https://twitter.com/i/cards/tfw/v1/628886457357352960?cardname=player&earned=true)
* [Relay for visual learners](http://sgwilym.github.io/relay-visual-learners/)
* [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9)
* [Learn Golang + GraphQL + Relay, Part 1: Your first Golang GraphQL server](https://wehavefaces.net/learn-golang-graphql-relay-1-e59ea174a902)
* [Learn Golang + GraphQL + Relay, Part 2: Your first Relay application](https://wehavefaces.net/learn-golang-graphql-relay-2-a56cbcc3e341)
* [From REST to GraphQL](https://blog.jacobwgillespie.com/from-rest-to-graphql-b4e95e94c26b)
* [GraphQL: A data query language](http://graphql.org/blog/graphql-a-query-language/)
* [Subscriptions in GraphQL and Relay](http://graphql.org/blog/subscriptions-in-graphql-and-relay/)
* [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)

<a name="workshopper" />
## Workshoppers

* [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.
* [Let's Learn GraphQL](https://learngraphql.com) - Lessons/walkthrough of GraphQL concepts.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
