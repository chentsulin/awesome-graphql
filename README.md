# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL & Relay

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
- [Foundation](#foundation)
- [Community](#community)
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
	- [Haskell](#lib-haskell)
	- [SQL](#lib-sql)
	- [Lua](#lib-lua)
	- [Elm](#lib-elm)
	- [Clojure](#lib-clojure)
	- [Swift](#lib-swift)
	- [OCaml](#lib-ocaml)
	- [Android](#lib-android)
	- [iOS](#lib-ios)
	- [ClojureScript](#lib-clojurescript)
- [Tools](#tools)
- [Services](#services)
- [Databases](#databases)
- [Examples](#example)
	- [Javascript](#example-js)
	- [Typescript](#example-ts)
	- [Ruby](#example-rb)
	- [Go](#example-go)
	- [Scala](#example-scala)
	- [Python](#example-python)
	- [Elixir](#example-elixir)
	- [Java](#example-java)
	- [Android](#example-android)
	- [iOS](#example-ios)
	- [Clojure](#example-clojure)
- [Videos](#video)
- [Blogs](#blogs)
- [Posts](#post)
- [Workshoppers](#workshopper)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specification

* [facebook/graphql](https://facebook.github.io/graphql/) - Working Draft of the Specification for GraphQL created by Facebook.

<a name="foundation" />

## Foundation

* [GraphQL Foundation](https://gql.foundation/) - GraphQL Foundation under the Linux Foundation

<a name="community" />

## Community

* [Slack](https://graphql.slack.com/messages/general/) - Share and help people on the chat. Get your invite [here](https://graphql-slack.herokuapp.com/)
* [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing
* [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag #graphql
* [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag [graphql](https://stackoverflow.com/questions/tagged/graphql)
* [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs
* [GraphQL World](https://graphql-world.com) - The fastest growing community of GraphQL developers
* [/r/GraphQL](https://old.reddit.com/r/graphql/) - A Subreddit for interesting and informative GraphQL content and discussions.

<a name="meetups" />

## GraphQL Meetups

* [Bangalore](https://www.meetup.com/graphql-bangalore/)
* [Berlin](https://www.meetup.com/graphql-berlin/)
* [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
* [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
* [London](https://www.meetup.com/GraphQL-London/)
* [Manchester](https://www.meetup.com/GraphQL-Manchester/)
* [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
* [Munich](https://www.meetup.com/GraphQL-Munich/)
* [New York City](https://www.meetup.com/GraphQL-NYC/)
* [San Francisco](https://www.meetup.com/GraphQL-SF/)
* [Seattle](https://www.meetup.com/Seattle-GraphQL/)
* [Sydney](https://www.meetup.com/GraphQL-Sydney/)
* [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
* [Toronto](https://www.meetup.com/GraphQL-Toronto/)
* [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/)

<a name="lib" />

## Libraries

<a name="lib-js" />

### JavaScript Libraries

#### Clients
* [relay](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
* [Apollo Client](https://github.com/apollographql/apollo-client) - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
* [aws-amplify](https://github.com/aws-amplify/amplify-js) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.
* [graphql-hooks](https://github.com/nearform/graphql-hooks) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
* [graphql-request](https://github.com/prisma/graphql-request) - A minimal GraphQL client for Node and browsers.
* [FetchQL](https://github.com/gucheen/FetchQL) - A simple GraphQL query client using Fetch.
* [urql](https://github.com/FormidableLabs/urql) - A simple caching GraphQL client for React.
* [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.
* [Lokka](https://github.com/kadirahq/lokka) - Simple JavaScript client for GraphQL, which you can use anywhere.
* [react-reach](https://github.com/kennetpostigo/react-reach) - A library to communicate with Graphql through Redux.
* [Grafoo](https://github.com/grafoojs/grafoo) - A tiny yet fully fledged cache based GraphQL client

#### HTTP Server Bindings
* [express-graphql](https://github.com/graphql/express-graphql) - GraphQL Express Middleware.
* [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
* [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) - HAPI plugin for GraphiQL integration.
* [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.

#### Database & ORM
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
* [graphql-thinky](https://github.com/fenos/graphql-thinky) - Build an optimized GraphQL schema from Thinky RethinkDB models.
* [graphql-tools-sequelize](https://github.com/rse/graphql-tools-sequelize) - OO-style schema definition functions and schema resolver functions for GraphQL-Tools using Sequelize ORM
* [graysql-orm-loader](https://github.com/larsbs/graysql-orm-loader) - A GraysQL extension to load a GraphQL schema from an ORM.
* [GRelDAL](https://gql-dal.github.io/greldal/) - A simple micro-framework for bidirectional mapping between relational datastores and GraphQL APIs.

#### Miscellaneous

* [GraphQL.js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
* [codemirror-graphql](https://github.com/graphql/codemirror-graphql) - GraphQL mode and helpers for CodeMirror.
* [graphql-schema](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface.
* [graphql-tools-types](https://github.com/rse/graphql-tools-types) - Custom GraphQL types for use with GraphQL-Tools (Void, Int, Float, String, Date, UUID, JSON)
* [graphql-normalizr](https://github.com/monojack/graphql-normalizr) - Normalize GraphQL responses for persisting in the client cache/state
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
* [adrenaline](https://github.com/gyzerok/adrenaline) - React bindings for Redux with Relay in mind.
* [graph.ql](https://github.com/matthewmueller/graph.ql) - Faster and simpler technique for creating and querying GraphQL schemas.
* [Strapi](https://strapi.io/documentation/graphql) - Open-source Node.js framework that supports "GraphQL" out of the box.
* [GraysQL](https://github.com/larsbs/graysql) - A GraphQL manager and loader.
* [Annotated GraphQL](https://github.com/almilo/annotated-graphql) - Proof of Concept for annotations in GraphQL (i.e.: transform an existing REST api into a GraphQL endpoint).
* [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers.
* [graphql-anywhere](https://github.com/apollographql/graphql-anywhere) - Run a GraphQL query anywhere, against any data, with no schema.
* [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries.
* [modelizr](https://github.com/julienvincent/modelizr) - A library for simplifying the process of writing GraphQL queries, mocking them and normalizing their responses.
* [vue-apollo](https://github.com/Akryum/vue-apollo) - Vue integration for apollo.
* [graphql-pouch](https://github.com/MikeBild/graphql-pouch) - A GraphQL-API runtime on top of PouchDB created by GraphQL shorthand notation as a self contained service with CouchDB synchronization.
* [gql-tools](https://github.com/almilo/gql-tools) - Tool library with CLI for schema generation and manipulation.
* [graphql-iso-date](https://github.com/excitement-engineer/graphql-iso-date) - A GraphQL date scalar type to be used with GraphQL.js. This scalar represents a date in the ISO 8601 format YYYY-MM-DD.
* [graphql-compose](https://github.com/graphql-compose/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
* [node-graphjoiner](https://github.com/mwilliamson/node-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
* [Join Monster](https://github.com/acarl005/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.
* [graphql-factory](https://github.com/graphql-factory) - Create GraphQL types from JSON definitions
* [type-o-rama](https://github.com/stereobooster/type-o-rama) - JS type systems interportability.

#### Relay Related

* [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
* [sequelize-relay](https://github.com/MattMcFarland/sequelize-relay) - Serverside library that connects sequelize and graphql-relay-js together.
* [babel-relay-plugin](https://www.npmjs.com/package/babel-relay-plugin) - Babel Relay Plugin for transpiling GraphQL queries for use with Relay.
* [react-router-relay](https://github.com/relay-tools/react-router-relay) - Relay integration for React Router.
* [relay-local-schema](https://github.com/relay-tools/relay-local-schema) - Use Relay without a GraphQL server.
* [relay-sink](https://github.com/acdlite/relay-sink) - Use Relay to fetch and store data outside of a React component.
* [recompose-relay](https://github.com/acdlite/recompose/tree/master/src/packages/recompose-relay) - Recompose helpers for Relay.
* [Graylay](https://github.com/larsbs/graysql#Graylay) - A GraysQL extension to create a Relay compatible Schema.
* [react-relay-network-layer](https://github.com/relay-tools/react-relay-network-layer) - A network layer for Relay with query batching and middleware support (urlThunk, retryThunk, auth, defer and other).
* [relay-subscriptions](https://github.com/relay-tools/relay-subscriptions) - Subscription support for Relay.
* [Portfolio Relay Example](https://github.com/alex-cory/portfolio) - An example website that fetches data from various apis and uses Relay and GraphQL to feed the data to React components!

<a name="lib-rb" />

### Ruby Libraries

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
* [graphql-client](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries.
* [graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem.
* [agoo](https://github.com/ohler55/agoo) - Ruby web server that implements Facebook's GraphQL.

<a name="lib-php" />

### PHP Libraries

* [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
* [Railt](https://github.com/railt/railt) - High quality and loosely coupled framework for developing GraphQL applications using all the modern qualities of the language.
* [digiaonline](https://github.com/digiaonline/graphql-php) - Yet another PHP port of GraphQL reference implementation.
* [GraphQL](https://github.com/youshido-php/GraphQL) (*abandoned*) - Well documented PHP implementation with no dependencies.
* [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
* [lighthouse](https://github.com/nuwave/lighthouse) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
* [laravel-graphql](https://github.com/Folkloreatelier/laravel-graphql) (*abandoned*) - Facebook GraphQL for Laravel 5.
* [laravel-graphql-relay](https://github.com/nuwave/laravel-graphql-relay) - A Laravel library to help construct a server supporting react-relay.
* [graphql-mapper](https://github.com/4rthem/graphql-mapper) (*abandoned*) - This library allows to build a GraphQL schema based on your model.
* [graphql-bundle](https://github.com/hoticeking/GraphQLBundle) - GraphQL Bundle for Symfony 2.
* [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
* [GraphQL Symfony Bundle](https://github.com/youshido-php/GraphQLBundle) - GraphQL Bundle for the Symfony 3 (supports 2.6+).
* [graphql-wp](https://github.com/tim-field/graphql-wp) - WordPress plugin that exposes a GraphQL endpoint.
* [eZ Platform GraphQL Bundle](https://www.symfony.fi/entry/graphql-bundle-adds-protocol-support-to-ez-platform-symfony-cms) - GraphQL Bundle for the eZ Platform Symfony CMS.
* [GraphQL Middleware](https://github.com/stefanorg/graphql-middleware) - GraphQL Psr7 Middleware
* [Zend Expressive GraphiQL Extension](https://github.com/stefanorg/zend-expressive-graphiql) - GraphiQL extension for zend expressive

<a name="lib-py" />

### Python Libraries

* [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
* [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python.
* [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
* [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
* [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
* [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE).
* [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) - Integrate GraphiQL easily into your Django project.
* [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.
* [python-graphql-client](https://github.com/prisma/python-graphql-client) - Simple GraphQL client for Python 2.7+
* [python-graphjoiner](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
* [graphene-django](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene.
* [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) - An authentication library for Flask inspired from flask-jwt-extended.
* [tartiflette](https://github.com/dailymotion/tartiflette) - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
* [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio, [official tutorial available on tartiflette.io](https://tartiflette.io/docs/tutorial/getting-started).

<a name="lib-java" />

### Java Libraries

* [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation.
* [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - Auto-generates types for use with GraphQL Java
* [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
* [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java.
* [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers.  Inspired by [graphql-tools](https://github.com/apollographql/graphql-tools) for JS.
* [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
* [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library.
* [graphql-spring-boot](https://github.com/oembedler/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters.
* [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices.
* [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments
* [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) - Java 8+ API for rapid development of GraphQL services.
* [Light Java GraphQL](https://github.com/networknt/light-graphql-4j): A lightweight, fast microservices framework with all cross-cutting concerns addressed and ready to plug in GraphQL schema.

<a name="lib-c" />

### C/C++ Libraries

* [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.

<a name="lib-go" />

### Go Libraries

* [graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js
* [graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use.
* [GQLGen](https://github.com/99designs/gqlgen) - Go generate based graphql server library.
* [machinebox/graphql](https://github.com/machinebox/graphql) - Simple low-level GraphQL client for Go
* [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
* [graphql](https://github.com/tmc/graphql) - GraphQL parser and server for Go.
* [c-graphqlparser](https://github.com/tecbot/c-graphqlparser) - Go-gettable version of the libgraphqlparser C library for parsing GraphQL.
* [tallstreet-graphql](https://github.com/tallstreet/graphql) - GraphQL parser and server for Go that leverages libgraphqlparser
* [go-graphql](https://github.com/playlyfe/go-graphql) - A powerful GraphQL server implementation for Golang

<a name="lib-scala" />

### Scala Libraries

* [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL client and server library.
* [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
* [graphql-scala](https://github.com/hrosenhorn/graphql-scala) - An attempt to get GraphQL going with Scala.

<a name="lib-dotnet" />

### .NET Libraries

* [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
* [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET.
* [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL server for .Net Core and .NET Framework.

<a name="lib-elixir" />

### Elixir Libraries

* [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
* [graphql-elixir](https://github.com/graphql-elixir/graphql) - GraphQL Elixir.
* [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir.
* [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for [libgraphqlparser](https://github.com/graphql/libgraphqlparser)
* [graphql](https://github.com/asonge/graphql) - Elixir GraphQL parser.
* [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.

<a name="lib-haskell" />

### Haskell Libraries

* [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.

<a name="lib-sql" />

### SQL Libraries

* [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
* [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.
* [PostGraphile](https://github.com/graphile/postgraphile) - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
* [Hasura](https://github.com/hasura/graphql-engine) - Hasura gives Instant Realtime GraphQL APIs over PostgreSQL. Works with an existing database too.

<a name="lib-lua" />

### Lua Libraries

* [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="lib-elm" />

### Elm Libraries

* [elm-graphql](https://github.com/jahewson/elm-graphql) - GraphQL for Elm.

<a name="lib-clojure" />

### Clojure Libraries

* [graphql-clj](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation.
* [Lacinia](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure.
* [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="lib-swift" />

### Swift Libraries

* [GraphQL](https://github.com/GraphQLSwift/GraphQL) - The Swift implementation for GraphQL.

<a name="lib-ocaml" />

### OCaml Libraries

* [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml.

<a name="lib-android" />

### Android Libraries

* [apollo-android](https://github.com/apollographql/apollo-android) - ðŸ“Ÿ A strongly-typed, caching GraphQL client for Android, written in Java

<a name="lib-ios" />

### iOS Libraries

* [apollo-ios](https://github.com/apollographql/apollo-ios) - ðŸ“± A strongly-typed, caching GraphQL client for iOS, written in Swift

<a name="lib-clojurescript" />

### ClojureScript Libraries

* [re-graph](https://github.com/oliyh/re-graph) - A GraphQL client for ClojureScript with bindings for re-frame applications.
* [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="tools" />

## Tools

* [graphiql](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
* [GraphiQL.app](https://github.com/skevy/graphiql-app) - A light, Electron-based wrapper around GraphiQL.
* [GraphQLviz](https://github.com/Macroz/GraphQLviz) - GraphQLviz marries GraphQL (schemas) with Graphviz.
* [graphqlviz](https://github.com/sheerun/graphqlviz) - GraphQL API visualizer in Node.js
* [GraphQL AST Explorer](http://dferber90.github.io/graphql-ast-explorer/) - Explore the AST of a GraphQL document interactively
* [GraphQLHub](https://www.graphqlhub.com/) - Query public API's schemas (e.g. Reddit, Twitter, Github, etc) using GraphiQL
* [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
* [gdom](https://github.com/syrusakbary/gdom) - DOM Traversing and Scraping using GraphQL.
* [Annotated GraphQL Server](https://github.com/almilo/annotated-graphql-server) - Server for annotated GraphQL showing how to transform a REST api into a GraphQL endpoint with annotations.
* [Model Visualizer](http://nathanrandal.com/graphql-visualizer/) - A small webapp that generates an ERD-like visualization of a GraphQL endpoint from an introspection query.
* [GraphQL Network](https://github.com/Ghirro/graphql-network) - A chrome dev-tools extension for debugging GraphQL network requests.
* [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema.
* [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
* [vim-graphql](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
* [GraphQL CMS](https://github.com/sarkistlt/graphql-auto-generating-cms) - Use your existing GraphQL schema to generate simple for use, fully functional CMS in a couple steps.
* [graphdoc](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema.
* [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom.
* [GraphQL Code Generator](https://github.com/dotansimha/graphql-code-generator) - GraphQL code generator based on schema and documents.
* [GraphQL IDE](https://github.com/andev-software/graphql-ide) - An extensive IDE for exploring GraphQL API's.
* [Swagger to GraphQL](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
* [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph.
* [GraphQL Docs](https://graphql-docs.com) - Instantly create beautiful GraphQL API docs hosted online.
* [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) - ðŸŽ² Mock or extend your GraphQL API with faked data. No coding required.
* [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
* [Apollo Launchpad](https://launchpad.graphql.com/) - Like JSFiddle for GraphQL server code, write and deploy a GraphQL API directly from your browser.
* [Apollo Tracing](https://github.com/apollographql/apollo-tracing) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
* [Altair GraphQL Client](https://github.com/imolorhe/altair) - A beautiful feature-rich GraphQL Client for all platforms.
* [Apollo Storybook Decorator](https://github.com/abhiaiyer91/apollo-storybook-decorator) - Wrap your React Storybook stories with Apollo Client, provide mocks for isolated UI testing with GraphQL
* [GraphQL Metrics](https://github.com/Workpop/graphql-utils/tree/master/packages/graphql-metrics) - instrument GraphQL resolvers, logging response times and statuses (if there was an error or not) to the console as well as to InfluxDB.
* [GraphQL Rover](https://github.com/Brbb/graphql-rover) - GraphQL schema interactive navigation, rearrange nodes, search and explore types and fields.
* [json-graphql-server](https://github.com/marmelab/json-graphql-server) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
* [Insomnia](https://insomnia.rest/) â€“Â An full-featured API client with first-party GraphQL query editor
* [Prisma](https://github.com/prisma/prisma) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
* [tuql](https://github.com/bradleyboy/tuql) - Automatically create a GraphQL server from any sqlite database.
* [Bit](https://github.com/teambit/bit) - Organize GraphQL API as components to be consumed with NPM or modified from any project ([example](https://bitsrc.io/giladshoham/github-graphql)).
* [RAN Toolkit](https://github.com/sly777/ran) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.
* [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform
* [GRAPHQL DESIGNER](http://graphqldesigner.com/) - A developer's web-app tool to rapidly prototype a full stack CRUD implementation of GraphQL with React.
* [GraphQL Inspector](https://graphql-inspector.com/) - Tooling for GraphQL. Compare schemas, validate documents, find breaking changes, find similar types, schema coverage.

<a name="databases" />

## Databases

* [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language

<a name="services" />

## Services

* [DatoCMS](https://www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
* [GraphCMS](https://graphcms.com/) - GraphQL based Headless Content Management System.
* [Graphcool](https://www.graph.cool/) - Your own GraphQL backend in under 5 minutes. Works with every GraphQL client such as Relay and Apollo.

<a name="example" />

## Examples

<a name="example-js" />

### JavaScript Examples

* [react-starter-kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate (Node.js/Express, GraphQL, React)
* [graphql-starter-kit](https://github.com/kriasoft/nodejs-api-starter) - Project template for building a GraphQL server with Node.js v7+ and JavaScript
* [swapi-graphql](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping swapi.co.
* [graphql-server](https://github.com/RisingStack/graphql-server) - GraphQL server with Mongoose (MongoDB) and Node.js.
* [graphql-intro](https://github.com/clayallsopp/graphql-intro) - https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2
* [graphql-aws](https://github.com/jonsharratt/graphql-aws) - Amazon AWS GraphQL API Server.
* [graffiti-todo](https://github.com/RisingStack/graffiti-todo) - Example Relay TodoMVC application using graffiti-mongoose.  **WARNING** Graffiti is no longer actively maintained.  For hobbyist only.
* [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
* [UniversalRelayBoilerplate](https://github.com/MachineAcuity/rebar)
Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra.
* [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql)
* [relay-skeleton](https://github.com/fortruce/relay-skeleton) - React, Relay, GraphQL project skeleton
* [simple-relay-starter](https://github.com/mhart/simple-relay-starter) - A very simple starter for React Relay using Browserify.
* [relay-chat](https://github.com/transedward/relay-chat) - an chat example showing Relay with routing and pagination.
* [relay-todomvc](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing.
* [graphql-express-sqlite](https://github.com/mrblueblue/graphql-express-sqlite) - GraphQL server with Sqlite and Express
* [koa-graphql-relay-example](https://github.com/chentsulin/koa-graphql-relay-example) - Example of [koa-graphql](https://github.com/chentsulin/koa-graphql)
* [relay-fullstack](https://github.com/lvarayut/relay-fullstack) - Relay Starter Kit integrated with Relay, GraphQL, Express, ES6/ES7, JSX, Webpack, Babel, Material Design Lite, and PostCSS.
* [serverless-graphql-blog](https://github.com/serverless/serverless-graphql-blog) - A Serverless Blog leveraging GraphQL to offer a REST API with only 1 endpoint
* [relay-cart](https://github.com/soonlive/relay-cart) - A simple shopping cart example leveraging relay & GraphQL with routing and pagination.
* [graphql-loader](https://github.com/applification/graphql-loader) - Example project to illustrate GraphQL, Express and Facebook DataLoader to connect to third party REST API
* [swapi-graphql-lambda](https://github.com/alvinthen/swapi-graphql-lambda) - A GraphQL schema hosted in AWS Lambda wrapping swapi.co
* [Apollo Client documentation](https://www.apollographql.com/react/) - Documentation and example for building GraphQL apps using apollo client
* [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
* [f8-apollo](https://github.com/nnance/f8app-apollo) - Refactored version of the official F8 app of 2016, powered by React Native and the Apollo Stack.
* [f8app](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects. [makeitopen.com](https://makeitopen.com)
* [Reindex Examples](https://github.com/reindexio/reindex-examples) - Example projects for Reindex with using React Native and React.js for web.
* [Modelizr Documentation](https://julienvincent.io/modelizr/) - Documentation and Usage Examples for modelizr
* [Vue Apollo Example](https://github.com/Akryum/frontpage-vue-app) - Apollo example project for Vue 2.0.
* [angular2-graphql-rest](https://github.com/kamilkisiela/angular2-graphql-rest) - An example app with REST Api working side by side with GraphQL using Apollo Client with angular2-apollo. Includes step-by-step tutorial how to migrate from REST to GraphQL.
* [GraphQL-DataLoader-Boilerplate](https://github.com/entria/graphql-dataloader-boilerplate) - Boilerplate to start your GraphQL with DataLoader server
* [GraphQL-CEP](https://github.com/sibelius/graphql-cep) - Query address by CEP
* [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - Usage Examples Apollo React for Github GraphQL API with create-react-app
* [Intuitive GraphQL Resolver Example](https://github.com/xpepermint/graphql-example) - GraphQL application example using [contextable.js](https://github.com/rawmodel/framework).
* [GraphQL Tutorial](https://github.com/rse/graphql-tutorial) - A didactic 12-step introduction to GraphQL, starting from a simple Hello World to a network-based GraphQL server with a built-in GraphQL UI

<a name="example-ts" />

### TypeScript Examples

* [Basic Apollo Server](https://github.com/DxCx/webpack-graphql-server) - Basic Starter for Apollo Server, Using typescript and Webpack.

<a name="example-rb" />

### Ruby Examples

* [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.
* [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API.
* [relay-on-rails](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server.
* [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - A graphql, relay and standard rails application powered demo weblog.
* [to_eat_app] (https://github.com/jcdavison/to_eat_app) - A sample graphql/rails/relay application with a related 3-part article series.
* [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) - Use of the Agoo server to demonstrate a simple GraphQL application.

<a name="example-go" />

### Go Examples

* [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
* [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.

<a name="example-scala" />

### Scala Examples

* [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](http://sangria-graphql.org)
* [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="example-python" />

### Python Examples

* [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](https://graphene-python.org) - [View demo online](http://swapi.graphene-python.org).

<a name="example-elixir" />

### Elixir Examples

* [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix - [View demo online](http://playground.graphql-elixir.org).

<a name="example-java" />

### Java Examples

* [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) - Examples of Light Java GraphQL and tutorials.

<a name="example-android" />

### Android Examples

* [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) - ðŸ“„ Apollo "hello world" app, for Android

<a name="example-ios" />

### iOS Examples

* [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) - ðŸ“„ Apollo "hello world" app, for iOS

<a name="example-clojure" />

### Clojure Examples

* [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) - Example code for the Lacinia GraphQL framework tutorial.

<a name="example-java" />

### Java Examples

* [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) - An example GraphQL server written with Spring MVC and [graphql-spqr](https://github.com/leangen/GraphQL-SPQR)

<a name="video" />

## Videos

* [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
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
* [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
* [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
* [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
* [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
* [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)
* [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
* [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)


<a name="blogs" />

## Blogs
* [Official GraphQL blog](http://graphql.org/blog/)
* [Building Apollo](https://blog.apollographql.com/)
* [The Guild blog](https://medium.com/the-guild)

<a name="post" />

## Posts

* [Using DataLoader to batch GraphQL requests](http://gajus.com/blog/9/using-dataloader-to-batch-requests)
* [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
* [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
* [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
* [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
* [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
* [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
* [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
* [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
* [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
* [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
* [Relay for visual learners](http://sgwilym.github.io/relay-visual-learners/)
* [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9)
* [Learn Golang + GraphQL + Relay, Part 1: Your first Golang GraphQL server](https://wehavefaces.net/learn-golang-graphql-relay-1-e59ea174a902)
* [Learn Golang + GraphQL + Relay, Part 2: Your first Relay application](https://wehavefaces.net/learn-golang-graphql-relay-2-a56cbcc3e341)
* [From REST to GraphQL](https://jacobwgillespie.com/from-rest-to-graphql-b4e95e94c26b/)
* [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/ )
* [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/ )
* [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
* [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
* [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
* [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
* [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
* [How to implement viewerCanSee in  GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)

<a name="workshopper" />

## Workshoppers

* [GraphQL of Thrones](https://graphql-of-thrones.herokuapp.com/) - Total beginner tutorial focused on just GraphQL without all the tooling. Alternates between LEARN and PLAY modes roleplaying as Game of Thrones characters.
* [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more
* [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.
* [Let's Learn GraphQL](https://learngraphql.com) - Lessons/walkthrough of GraphQL concepts.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
