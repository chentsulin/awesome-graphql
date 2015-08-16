# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
    - [facebook/graphql](http://facebook.github.io/graphql/)
- [Libraries](#lib)
    - [Javascript](#lib-js)
        - [GraphQL.js](https://github.com/graphql/graphql-js)
        - [express-graphql](https://github.com/graphql/express-graphql)
        - [graphql-relay-js](https://github.com/graphql/graphql-relay-js)
        - [graphql-parser](https://github.com/ooflorent/graphql-parser)
        - [graphql-schema](https://github.com/devknoll/graphql-schema)
        - [graphqljs](https://github.com/cobbweb/graphqljs)
        - [graphqlite](https://github.com/madjam002/graphqlite)
        - [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize)
        - [graffiti](https://github.com/RisingStack/graffiti)
        - [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose)
        - [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql)
        - [koa-graphql](https://github.com/chentsulin/koa-graphql)
        - [redux-graphql](https://github.com/gyzerok/redux-graphql)
        - [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf)
    - [Ruby](#lib-rb)
        - [graphql-ruby](https://github.com/rmosolgo/graphql-ruby)
    - [PHP](#lib-php)
        - [graphql-php](https://github.com/webonyx/graphql-php)
        - [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql)
    - [Python](#lib-py)
        - [graphql-py](https://github.com/dittos/graphql-py)
    - [Java](#lib-java)
        - [graphql-java](https://github.com/andimarek/graphql-java)
    - [Go](#lib-go)
        - [go-graphql](https://github.com/cryptix/go-graphql)
    - [Scala](#lib-scala)
        - [sangria](https://github.com/OlegIlyenko/sangria)
        - [graphql-scala](https://github.com/hrosenhorn/graphql-scala)
    - [.NET](#lib-dotnet)
        - [graphql-dotnet](https://github.com/joemcbride/graphql-dotnet)
    - [Elixir](#lib-elixir)
        - [graphql](https://github.com/asonge/graphql)
    - [PostgresSQL](#lib-pgsql)
        - [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL)
- [Examples](#example)
    - [Javascript](#example-js)
        - [relay-starter-kit](https://github.com/facebook/relay-starter-kit)
        - [graphql-server](https://github.com/RisingStack/graphql-server)
        - [graphql-intro](https://github.com/clayallsopp/graphql-intro)
        - [redux-react-graphql-example](https://github.com/gyzerok/redux-react-graphql-example)
        - [graphql-aws](https://github.com/redbadger/graphql-aws)
        - [graffiti-example](https://github.com/RisingStack/graffiti-example)
        - [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
        - [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql)
        - [redux-react-graphql-example](https://github.com/gyzerok/redux-react-graphql-example)
    - [Ruby](#example-rb)
        - [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo)
    - [Scala](#example-scala)
        - [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example)
- [Videos](#video)
    - [React.js Conf 2015 - Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
    - [F8 2015 - React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
    - [Lee Byron - Exploring GraphQL at react-europe 2015](https://www.youtube.com/watch?v=WQLzZf34FJ8)
    - [Nick Schrock & Dan Schafer - Creating a GraphQL Server at react-europe 2015](https://www.youtube.com/watch?v=gY48GW87Feo)
    - [GraphQL at The Financial Times- Viktor Charypar London React August 2015](https://www.youtube.com/watch?v=S0s935RKKB4)
- [Posts](#post)
    - [Introducing Relay and GraphQL](https://facebook.github.io/react/blog/2015/02/20/introducing-relay-and-graphql.html)
    - [GraphQL Introduction](http://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)
    - [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
    - [Your First GraphQL Server](https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2)
    - [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
    - [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
    - [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
    - [Start using GraphQL with Graffiti](https://blog.risingstack.com/start-using-graphql-with-graffiti/?utm_source=nodeweekly&utm_medium=email)
    - [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
    - [London React August - GraphQL at The Financial Times - Viktor Charypar](http://www.slideshare.net/LondonReact/graph-ql?ref=https://twitter.com/i/cards/tfw/v1/628886457357352960?cardname=player&earned=true)
- [Workshoppers](#workshopper)
    - [learning-graphql](https://github.com/mugli/learning-graphql)

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
* [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
* [graphql-parser](https://github.com/ooflorent/graphql-parser) - Experimental Facebook's GraphQL parser.
* [graphql-schema](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface.
* [graphqljs](https://github.com/cobbweb/graphqljs) - GraphQL parser written in JavaScript.
* [graphqlite](https://github.com/madjam002/graphqlite) - A Javascript Parser for Facebook's GraphQL.
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
* [graffiti](https://github.com/RisingStack/graffiti) - Node.js GraphQL ORM.
* [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) - Mongoose (MongoDB) adapter for graffiti (Node.js GraphQL ORM).
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
* [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
* [redux-graphql](https://github.com/gyzerok/redux-graphql) - Relay-like functionality for Redux-based applications.
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.

<a name="lib-rb" />
### Ruby Libraries

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.

<a name="lib-php" />
### PHP Libraries

* [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
* [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5.

<a name="lib-py" />
### Python Libraries

* [graphql-py](https://github.com/dittos/graphql-py) - GraphQL implementation for Python.

<a name="lib-java" />
### Java Libraries

* [graphql-java](https://github.com/andimarek/graphql-java) - GraphQL Java implementation.

<a name="lib-go" />
### Go Libraries

* [go-graphql](https://github.com/cryptix/go-graphql) - GraphQL packages for golang.

<a name="lib-scala" />
### Scala Libraries

* [sangria](https://github.com/OlegIlyenko/sangria) -Scala GraphQL client and server library.
* [graphql-scala](https://github.com/hrosenhorn/graphql-scala) - An attempt to get GraphQL going with Scala.

<a name="lib-dotnet" />
### .NET Libraries

* [graphql-dotnet](https://github.com/joemcbride/graphql-dotnet) - https://github.com/joemcbride/graphql-dotnet.

<a name="lib-elixir" />
### Elixir Libraries
        
* [graphql](https://github.com/asonge/graphql) - Elixir graphql library.

<a name="lib-pgsql" />
### PostgresSQL Libraries

* [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.

<a name="example" />
## Examples

<a name="example-js" />
### JavaScript Examples

* [relay-starter-kit](https://github.com/facebook/relay-starter-kit) - Barebones starting point for a Relay application.
* [graphql-server](https://github.com/RisingStack/graphql-server) - GraphQL server with Mongoose (MongoDB) and Node.js.
* [graphql-intro](https://github.com/clayallsopp/graphql-intro) - https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2.
* [redux-react-graphql-example](https://github.com/gyzerok/redux-react-graphql-example) - graphql-example with react and redux.
* [graphql-aws](https://github.com/redbadger/graphql-aws) - Amazon AWS GraphQL API Server.
* [graffiti-example](https://github.com/RisingStack/graffiti-example) - Example server for the graffiti GraphQL ORM.
* [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
* [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql)
* [redux-react-graphql-example](https://github.com/gyzerok/redux-react-graphql-example)

<a name="example-rb" />
### Ruby Examples

* [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - https://github.com/rmosolgo/graphql-ruby-demo.

<a name="example-scala" />
### Scala Examples

* [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](http://sangria-graphql.org)

<a name="video" />
## Videos

* [React.js Conf 2015 - Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
* [F8 2015 - React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
* [Lee Byron - Exploring GraphQL at react-europe 2015](https://www.youtube.com/watch?v=WQLzZf34FJ8)
* [Nick Schrock & Dan Schafer - Creating a GraphQL Server at react-europe 2015](https://www.youtube.com/watch?v=gY48GW87Feo)
* [GraphQL at The Financial Times- Viktor Charypar London React August 2015](https://www.youtube.com/watch?v=S0s935RKKB4)

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
* [London React August - GraphQL at The Financial Times - Viktor Charypar](http://www.slideshare.net/LondonReact/graph-ql?ref=https://twitter.com/i/cards/tfw/v1/628886457357352960?cardname=player&earned=true)

<a name="workshopper" />
## Workshoppers

* [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
