# Awesome GraphQL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A query language and runtime for APIs that prioritizes precise data fetching and strongly typed schemas.

## Contents

- [Specifications](#specifications)
- [Foundations](#foundations)
- [Communities](#communities)
- [Meetups](#meetups)
- [Implementations](#implementations)
- [Tools](#tools)
- [Databases](#databases)
- [Services](#services)
- [Books](#books)
- [Videos](#videos)
- [Podcasts](#podcasts)
- [Style Guides](#style-guides)
- [Blogs](#blogs)
- [Posts](#posts)
- [Tutorials](#tutorials)

<a name="spec" />

## Specifications

- [GraphQL](https://github.com/graphql/graphql-spec) - Working draft of the specification for GraphQL.
- [GraphQL over HTTP](https://github.com/graphql/graphql-over-http) - Working draft of "GraphQL over HTTP" specification.
- [GraphQL Relay](https://relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
- [OpenCRUD](https://github.com/opencrud/opencrud) - CRUD API specification for GraphQL databases.
- [Apollo Federation](https://www.apollographql.com/docs/federation/federation-spec/) - Specification for composing multiple GraphQL services.
- [GraphQXL](https://gabotechs.github.io/graphqxl/) - Extension of the GraphQL language for creating large, scalable server-side schemas.
- [GraphQL Scalars](https://www.graphql-scalars.com/) - Hosts community-defined custom scalar specifications for use with `@specifiedBy`.

<a name="foundation" />

## Foundations

- [GraphQL Foundation](https://graphql.org/foundation/) - Organization supporting GraphQL under the Linux Foundation.

<a name="community" />

## Communities

- [Discord - GraphQL](https://discord.graphql.org/) - Official GraphQL.org Discord channel.
- [GraphQL Weekly](https://www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
- [Apollo GraphQL Community](https://community.apollographql.com/) - Connect with other developers and share knowledge about every part of the Apollo GraphQL platform.
- [Discord - Reactiflux](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
- [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
- [X](https://x.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers using the tag `graphql`.
- [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs.
- [/r/GraphQL](https://www.reddit.com/r/graphql/) - A subreddit for GraphQL news, resources, and discussions.

<a name="meetup" />

## Meetups

- [Relay Meetup](https://relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
- [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/) - Local GraphQL meetup community.
- [Bangalore](https://www.meetup.com/graphql-bangalore/) - Local GraphQL meetup community.
- [Berlin](https://www.meetup.com/graphql-berlin/) - Local GraphQL meetup community.
- [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/) - Local GraphQL meetup community.
- [Copenhagen](https://www.meetup.com/Copenhagen-GraphQL-Meetup-Group/) - Local GraphQL meetup community.
- [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/) - Local GraphQL meetup community.
- [Hamburg](https://www.meetup.com/GraphQL-Hamburg/) - Local GraphQL meetup community.
- [London](https://www.meetup.com/GraphQL-London/) - Local GraphQL meetup community.
- [Melbourne](https://www.meetup.com/GraphQL-Melbourne/) - Local GraphQL meetup community.
- [Munich](https://www.meetup.com/GraphQL-Munich/) - Local GraphQL meetup community.
- [New York City](https://www.meetup.com/GraphQL-NYC/) - Local GraphQL meetup community.
- [San Francisco](https://www.meetup.com/GraphQL-SF/) - Local GraphQL meetup community.
- [Seattle](https://www.meetup.com/Seattle-GraphQL/) - Local GraphQL meetup community.
- [Sydney](https://www.meetup.com/GraphQL-Sydney/) - Local GraphQL meetup community.
- [Tel Aviv](https://www.meetup.com/GraphQL-TLV/) - Local GraphQL meetup community.
- [Wrocław](https://www.meetup.com/GraphQL-Wroclaw/) - Local GraphQL meetup community.
- [Singapore](https://www.meetup.com/GraphQL-SG/) - Local GraphQL meetup community.
- [Zurich](https://www.meetup.com/GraphQL-Zurich/) - Local GraphQL meetup community.

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

- [graphql-js](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
- [graphql-jit](https://github.com/zalando-incubator/graphql-jit) - GraphQL execution using a JIT compiler.
- [Gra**fast**](https://grafast.org) - A cutting edge planning and execution engine for GraphQL.

#### Clients

- [apollo-client](https://github.com/apollographql/apollo-client) - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
- [graphql-request](https://github.com/prisma-labs/graphql-request) - A minimal GraphQL client for Node and browsers.
- [typescript-graphql-request](https://graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.
- [graphql-zeus](https://github.com/graphql-editor/graphql-zeus) - GraphQL Zeus creates autocomplete client library for `JavaScript` or `TypeScript` which provides autocompletion for strongly typed queries.
- [graphqurl](https://github.com/hasura/graphqurl) - Curl for GraphQL with autocomplete, subscriptions, and GraphiQL, plus a universal JavaScript GraphQL client.
- [aws-amplify](https://github.com/aws-amplify/amplify-js) - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.
- [gqty](https://github.com/gqty-dev/gqty) - No-query-language GraphQL client for TypeScript.
- [genql](https://github.com/remorses/genql) - Type safe TypeScript client for any GraphQL API.
- [zodql](https://github.com/mattiasahlsen/zodql) - Type-safe GraphQL client that uses Zod schemas as the single source of truth to build queries, infer response types, and validate responses at runtime.

##### Frontend Framework Integrations

- [vue-apollo](https://github.com/vuejs/vue-apollo) - Apollo/GraphQL integration for VueJS.
- [apollo-angular](https://github.com/kamilkisiela/apollo-angular) - A fully-featured, production ready caching GraphQL client for Angular and every GraphQL server.
- [svelte-apollo](https://github.com/timhall/svelte-apollo) - Svelte integration for Apollo GraphQL.
- [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client) - An ember-cli addon for Apollo Client and GraphQL.
- [apollo-elements](https://github.com/apollo-elements/apollo-elements) - GraphQL web components that work in any frontend framework.
- [sveltekit-kitql](https://github.com/jycouet/kitql) - A set of tools, helping you building efficient apps in a fast way with SvelteKit and GraphQL.

###### React

- [react-apollo](https://www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.
- [relay](https://github.com/facebook/relay) - JavaScript framework for building data-driven React applications.
- [urql](https://github.com/FormidableLabs/urql) - A simple caching GraphQL client for React.
- [graphql-hooks](https://github.com/nearform/graphql-hooks) - Minimal hooks-first GraphQL client with caching and server-side rendering support.
- [mst-gql](https://github.com/mobxjs/mst-gql) - Bindings for mobx-state-tree and GraphQL.
- [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.

#### Servers

- [apollo-server](https://github.com/apollographql/apollo-server) - Spec-compliant and production ready JavaScript GraphQL server that lets you develop in a schema-first way. Built for Express, Connect, Hapi, Koa, and more.
- [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
- [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) - HAPI plugin for GraphiQL integration.
- [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa) - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
- [koa-graphql](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
- [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts) - GraphQL Koa 1 file simplified. Useful for quick test.
- [gql](https://github.com/deno-libs/gql) - Universal GraphQL HTTP middleware for Deno.
- [mercurius](https://github.com/mercurius-js/mercurius) - GraphQL plugin for Fastify.
- [graphql-yoga](https://github.com/prisma-labs/graphql-yoga) - Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
- [graphitejs](https://github.com/graphitejs/server) - Node.js framework for GraphQL.
- [graphql-helix](https://github.com/contrawork/graphql-helix) - A highly evolved GraphQL HTTP Server.
- [pylon](https://github.com/getcronit/pylon) - Write full-feature APIs with just functions. No more boilerplate code, no more setup. Just write functions and deploy.
- [modus](https://github.com/hypermodeinc/modus) - Serverless runtime based on WebAssembly that delivers auto-generated GraphQL APIs.

##### Databases & ORMs

- [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
- [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
- [join-monster](https://github.com/acarl005/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.
- [Simfinity.js](https://github.com/simtlix/simfinity.js) - Generates GraphQL queries, mutations, relationships, and MongoDB or PostgreSQL storage from GraphQL object types.

##### PubSub

- [graphql-ably-pubsub](https://github.com/ably-labs/graphql-ably-pubsub) - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

- [graphql-scalars](https://github.com/Urigo/graphql-scalars) - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.

#### Type

- [type-graphql](https://github.com/19majkel94/type-graphql) - Create GraphQL schema and resolvers with TypeScript, using classes and decorators!
- [graphql-nexus](https://github.com/graphql-nexus/nexus) - Code-First, Type-Safe, GraphQL Schema Construction.
- [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) - GraphQL code generator with flexible support for custom plugins and templates such as TypeScript, React Hooks, and resolver signatures.
- [pothos](https://github.com/hayes/pothos) - Plugin-based GraphQL schema builder for TypeScript.
- [garph](https://github.com/stepci/garph) - Full-stack framework for building type-safe GraphQL APIs in TypeScript.
- [gqloom](https://github.com/modevol-com/gqloom) - GraphQL weaver for TypeScript/JavaScript that weaves GraphQL schema and resolvers using Valibot, Zod, or Yup.
- [fast-graphql](https://github.com/idurar/fast-graphql) - GraphQL tools to structure and combine resolvers and merge schema definitions for Node.js, Next.js, and Apollo Server.
- [graphql-to-type](https://github.com/lkster/graphql-to-type) - GraphQL query parser written entirely in TypeScript's type system for creating interfaces from a provided query.
- [gql.tada](https://github.com/0no-co/gql.tada) - GraphQL document authoring library, inferring the result and variables types of GraphQL queries and fragments in the TypeScript type system.

#### Miscellaneous

- [graphql-tools](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers.
- [graphql-tag](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries.
- [load-gql](https://github.com/KunalSin9h/load-gql) - A tiny, zero dependency GraphQL schema loader from files and folders.
- [graphql-compose](https://github.com/graphql-compose/graphql-compose) - Tool for constructing flexible GraphQL schemas from different data sources via plugins.
- [graphql-modules](https://github.com/Urigo/graphql-modules) - Separate GraphQL server into smaller, reusable parts by modules or features.
- [graphql-shield](https://github.com/maticzav/graphql-shield) - Library for creating a permission layer for a GraphQL API.
- [graphql-shield-generator](https://github.com/omar-dulaimi/graphql-shield-generator) - Emits a GraphQL Shield from your GraphQL schema.
- [graphqlgate](https://github.com/oslabs-beta/GraphQL-Gate) - GraphQL rate-limiting library with query complexity analysis for Node.js.
- [graphql-let](https://github.com/piglovesyou/graphql-let) - Webpack loader for importing type-protected code generation results directly from GraphQL documents.
- [graphql-config](https://github.com/kamilkisiela/graphql-config) - One configuration for all your GraphQL tools (supported by most tools, editors & IDEs).
- [graphql-cli](https://github.com/urigo/graphql-cli) - A command line tool for common GraphQL development workflows.
- [graphql-toolkit](https://github.com/ardatan/graphql-toolkit) - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
- [graphql-mesh](https://github.com/urigo/graphql-mesh) - Use the GraphQL query language to access data in remote APIs that may not run GraphQL.
- [sofa](https://github.com/Urigo/sofa) - Generate REST API from your GraphQL API.
- [graphback](https://github.com/aerogear/graphback) - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
- [graphql-middleware](https://github.com/maticzav/graphql-middleware) - Split up your GraphQL resolvers in middleware functions.
- [graphql-relay-js](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
- [graphql-normalizr](https://github.com/monojack/graphql-normalizr) - Normalize GraphQL responses for persisting in the client cache/state.
- [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
- [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema.
- [graphql-ws](https://github.com/enisdenjo/graphql-ws) - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
- [graphql-live-query](https://github.com/n1ru4l/graphql-live-query) - Realtime GraphQL Live Queries with JavaScript.
- [GraphVinci](https://github.com/Comcast/graphvinci) - An interactive schema visualizer for GraphQL APIs.
- [supertest-graphql](https://github.com/alexstrat/supertest-graphql) - Extends supertest to easily test a GraphQL endpoint.
- [schemathesis](https://github.com/schemathesis/schemathesis) - Runs arbitrary queries matching a GraphQL schema to find server errors.
- [microfiber](https://github.com/anvilco/graphql-introspection-tools) - Query and manipulate GraphQL introspection query results in useful ways.
- [graphql-armor](https://github.com/Escape-Technologies/graphql-armor) - An instant security layer for production GraphQL Endpoints.
- [goctopus](https://github.com/Escape-Technologies/goctopus) - Fast GraphQL discovery and fingerprinting toolbox.
- [GraphQL Constraint Directive](https://github.com/confuser/graphql-constraint-directive) - Allows `@constraint` directives to validate input data, inspired by the Constraints Directives RFC and OpenAPI.
- [Validator.js Wrapper Directive](https://github.com/ktutnik/graphql-directive/tree/master/packages/validator) - Wraps Validator.js functionality in validation directives.
- [WunderGraph Cosmo](https://github.com/wundergraph/cosmo) - Open source GraphQL federation solution with schema registry, composition checks, analytics, metrics, tracing, and routing.
- [graphql-sunset](https://github.com/sophiabits/graphql-sunset) - Quickly and easily add support for the `Sunset` header to your GraphQL server, to better communicate upcoming breaking changes.
- [Schemato](https://www.schemato.top/graphql-to-typescript) - Browser-only GraphQL SDL converter for generating TypeScript, Zod, Pydantic, Go, Rust, and other typed models.

<a name="js-example" />

#### JavaScript Examples

- [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - Frontend starter kit using React, Relay, GraphQL, and JAMstack architecture.
- [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping SWAPI.
- [Relay TodoMVC](https://github.com/taion/relay-todomvc) - TodoMVC example with Relay and routing.
- [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
- [F8 App 2017](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects.
- [Apollo React example for GitHub GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) - Example using Apollo React with the GitHub GraphQL API and Create React App.
- [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql) - Type-protected GraphQL example on Next.js running graphql-codegen under the hood.
- [GraphQL StackBlitz Starter](https://stackblitz.com/fork/graphql) - Live, editable demo that starts in a browser in about two seconds.
- [NAPERG](https://github.com/alan345/naperg) - Fullstack Boilerplate GraphQL. Made with React & Prisma + authentication & roles.
- [VulcanJS](http://vulcanjs.org) - Full-stack React and GraphQL framework.
- [RAN Toolkit](https://github.com/sly777/ran) - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.

<a name="ts-example" />

#### TypeScript Examples

- [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter) - Yarn v2 based monorepo template (code-first GraphQL API, PostgreSQL, PnP, Zero-install, serverless).
- [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter) - Next.js starter project focused on developer experience.
- [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter) - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
- [Mocked Managed Federation - Apollo Server 3](https://github.com/setchy/apollo-server-3-mocked-federation) - Example of mocking a managed federation subgraph using Apollo Server 3.x.
- [Mocked Managed Federation - Apollo Server 4](https://github.com/setchy/apollo-server-4-mocked-federation) - Example of mocking a managed federation subgraph using Apollo Server 4.x.
- [Next.js Advanced GraphQL CRUD MongoDB Starter](https://github.com/idurar/starter-advanced-graphql-crud-next-js-mongodb) - Generic CRUD starter with an advanced Apollo GraphQL server, Next.js, MongoDB, and TypeScript.

<a name="rb" />

### Ruby

- [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
- [graphql-batch](https://github.com/Shopify/graphql-batch) - Query batching executor for the GraphQL Ruby gem.
- [graphql-auth](https://github.com/o2web/graphql-auth) - A JWT auth wrapper working with devise.
- [agoo](https://github.com/ohler55/agoo) - Ruby web server that implements Facebook's GraphQL.
- [GQLi](https://github.com/contentful-labs/gqli.rb) - A GraphQL client and DSL. Allowing to write queries in native Ruby.

<a name="rb-example" />

#### Ruby Examples

- [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.
- [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API.
- [relay-on-rails](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server.
- [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) - Demo weblog powered by GraphQL, Relay, and a standard Rails application.
- [to_eat_app](https://github.com/jcdavison/to_eat_app) - Sample GraphQL, Rails, and Relay application with a related three-part article series.
- [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) - Use of the Agoo server to demonstrate a simple GraphQL application.
- [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql) - Rails 6 boilerplate with Devise, GraphQL, and JWT authentication.

<a name="php" />

### PHP

- [graphql-php](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
- [graphql-relay-php](https://github.com/ivome/graphql-relay-php) - Relay helpers for webonyx/graphql-php implementation of GraphQL.
- [lighthouse](https://github.com/nuwave/lighthouse) - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
- [graphql-laravel](https://github.com/rebing/graphql-laravel) - Laravel wrapper for Facebook's GraphQL.
- [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
- [wp-graphql](https://github.com/wp-graphql/wp-graphql) - GraphQL API for WordPress.
- [graphqlite](https://github.com/thecodingmachine/graphqlite) - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
- [siler](https://github.com/leocavalcante/siler) - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
- [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder) - Builds request payload in GraphQL structure.
- [Drupal GraphQL](https://www.drupal.org/project/graphql) - Craft and expose a GraphQL schema for Drupal 9 and 10.
- [jerowork/graphql-schema-builder](https://github.com/jerowork/graphql-attribute-schema) - Easily build your GraphQL schema for webonyx/graphql-php using PHP attributes instead of large configuration arrays.

<a name="php-example" />

#### PHP Examples

- [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql) - An example GraphQL server written with Siler.

<a name="py" />

### Python

- [graphql-parser](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
- [graphql-core](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python based on the GraphQL.js v16.3.0 reference implementation.
- [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
- [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
- [graphene](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
- [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE).
- [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) - Integrate GraphiQL easily into your Django project.
- [flask-graphql](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.
- [python-graphql-client](https://github.com/prisma/python-graphql-client) - Simple GraphQL client for Python 2.7+.
- [python-graphjoiner](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
- [graphene-django](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene.
- [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) - An authentication library for Flask inspired from flask-jwt-extended.
- [tartiflette](https://github.com/dailymotion/tartiflette) - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
- [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio with an official tutorial available on tartiflette.io.
- [Ariadne](https://github.com/mirumee/ariadne) - Library for implementing GraphQL servers using a schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular web frameworks with comprehensive documentation.
- [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth) - Django registration and authentication with GraphQL.
- [strawberry](https://github.com/strawberry-graphql/strawberry) - A new GraphQL library for Python.
- [turms](https://github.com/jhnnsrs/turms) - Pythonic GraphQL code generator built around graphql-core and Pydantic.
- [rath](https://github.com/jhnnsrs/rath) - Apollo-like GraphQL client with asynchronous and synchronous interfaces.
- [sgqlc](https://github.com/profusion/sgqlc) - Simple GraphQL Client makes working with GraphQL API responses easier in Python.

<a name="py-example" />

#### Python Examples

- [swapi-graphene](https://github.com/graphql-python/swapi-graphene) - GraphQL schema and server using Graphene.
- [Python Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/python/) - Tutorial on creating a GraphQL server with Strawberry and a client with Qlient.

<a name="java" />

### Java

- [graphql-java](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation.
- [DGS Framework](https://github.com/Netflix/dgs-framework) - A GraphQL server framework for Spring Boot, developed by Netflix.
- [graphql-java-generator](https://github.com/graphql-java-generator) - Maven and Gradle plugins that generate both the **client** and the **server** (POJOs and utility classes). The server part is based on graphql-java and hides its boilerplate code.
- [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) - Automatically generates types for use with GraphQL Java.
- [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
- [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java.
- [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers, inspired by graphql-tools for JS.
- [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin) - Schema-first Maven plugin for generating Java types and resolver interfaces. Works with graphql-java-tools and was inspired by swagger-codegen-maven-plugin.
- [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin) - Schema-first Gradle plugin for generating Java types and resolver interfaces. Works with graphql-java-tools and was inspired by gradle-swagger-generator-plugin.
- [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
- [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) - Comprehensive schema-first GraphQL client with type-safe types, queries, and results, no code generators, no POJOs, and no annotations. Includes IDE support for IntelliJ IDEA and Android Studio. See the [Java example](#java-examples) below.
- [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library.
- [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters.
- [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices.
- [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
- [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) - Java 8+ API for rapid development of GraphQL services.
- [Light Java GraphQL](https://github.com/networknt/light-graphql-4j) - Lightweight, fast microservices framework with cross-cutting concerns addressed and support for GraphQL schemas.
- [Elide](https://elide.io) - Java library that exposes a JPA-annotated data model as a GraphQL service over a relational database.
- [federation-jvm](https://github.com/apollographql/federation-jvm) - Apollo Federation on the JVM.
- [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java) - Orchestrator and gateway library that combines schemas from multiple GraphQL microservices using schema stitching and Apollo Federation directives.
- [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) - Provides extended validation of fields and field arguments for graphql-java.
- [dgs-extended-formatters](https://github.com/setchy/dgs-extended-formatters) - An experimental set of DGS Directives for common formatting use-cases.

#### Custom Scalars

- [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.
- [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) - Extended scalars for graphql-java.

<a name="java-example" />

#### Java Examples

- [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) - Examples of Light Java GraphQL and tutorials.
- [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
- [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app) - A simple application, both client and server, demonstrating the Manifold GraphQL library.
- [graphql-java-kickstart_samples](https://github.com/graphql-java-kickstart/samples) - Samples for using the GraphQL Java Kickstart projects.
- [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example) - A GraphQL Java Kickstart federation example.
- [dgs-federation-example](https://github.com/Netflix/dgs-federation-example) - A Netflix DGS federation example.
- [Spring Boot backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/java/) - A tutorial creating a GraphQL server and client using Spring Boot and Netflix DGS.

<a name="kotlin" />

### Kotlin

- [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) - GraphQL Kotlin implementation.
- [KGraphQL](https://github.com/aPureBase/KGraphQL) - Pure Kotlin implementation for setting up a GraphQL server.
- [Kobby](https://github.com/ermadmi78/kobby) - Codegen plugin of Kotlin DSL Client by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.
- [Graphkt](https://github.com/cufyorg/graphkt) - DSL-based GraphQL server library for Kotlin, backed by graphql-java.

<a name="kotlin-example" />

#### Kotlin Examples

- [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app) - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

- [libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.
- [agoo-c](https://github.com/ohler55/agoo-c) - High-performance GraphQL server written in C with published benchmarks.
- [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen) - C++ GraphQL schema service generator.
- [CaffQL](https://github.com/caffeinetv/CaffQL) - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

- [GraphQL](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go that follows graphql-js.
- [graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use.
- [gql](https://github.com/kadirpekel/gql) - Code-first schema builder based on the reference Go implementation.
- [gqlgen](https://github.com/99designs/gqlgen) - Go generate-based GraphQL server library.
- [graphql-relay-go](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
- [graphjin](https://github.com/dosco/graphjin) - Instant GraphQL-to-SQL compiler for building APIs quickly.
- [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools) - GraphQL router and API gateway framework written in Go, focused on correctness, extensibility, and performance.
- [Thunder](https://github.com/Raezil/Thunder) - Scalable microservices framework powered by Go, gRPC-Gateway, Prisma, and Kubernetes that exposes REST, gRPC, and GraphQL.
- [grpc-graphql-gateway](https://github.com/ysugimoto/grpc-graphql-gateway) - Protoc plugin that generates GraphQL execution code from Protocol Buffers.
<a name="go-example" />

#### Go Examples

- [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
- [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
- [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example) - A GraphQL schema and server that demonstrates GraphQL [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md) over WebSocket to consume [Apache Kafka](https://kafka.apache.org/) messages.
- [Go Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/go/) - A tutorial showing how to make a Go GraphQL server and client using code generation.

<a name="scala" />

### Scala

- [sangria](https://github.com/sangria-graphql/sangria) - Scala GraphQL server implementation.
- [sangria-relay](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
- [caliban](https://github.com/ghostdogpr/caliban) - Purely functional library for creating GraphQL backends in Scala.

<a name="scala-example" />

#### Scala Examples

- [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](https://sangria-graphql.github.io/)
- [sangria-playground](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

- [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
- [graphql-net](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET.
- [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) - GraphQL server for .Net Core and .NET Framework.
- [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe) - Type-safe GraphQL code generator for F# and Fable.
- [EntityGraphQL](https://github.com/EntityGraphQL/EntityGraphQL) - Library for building a GraphQL API on top of a data model with support for multiple data sources.
- [ZeroQL](https://github.com/byme8/ZeroQL) - Type-safe GraphQL client with a LINQ-like interface for C#.

<a name="net-example" />

#### .NET Examples

- [.NET backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/dotnet/) - A tutorial creating a GraphQL server and client with .NET.

<a name="elixir" />

### Elixir

- [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
- [graphql-elixir](https://github.com/graphql-elixir/graphql) - GraphQL Elixir. (No longer maintained)
- [plug_graphql](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir.
- [graphql_relay](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir.
- [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for libgraphqlparser.
- [GraphQL](https://github.com/asonge/graphql) - Elixir GraphQL parser.
- [plot](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.

<a name="elixir-example" />

#### Elixir Examples

- [hello_graphql_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix.

<a name="haskell" />

### Haskell

- [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.
- [morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql) - Haskell GraphQL Api, Client and Tools.

<a name="sql" />

### SQL

- [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
- [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.
- [PostGraphile](https://github.com/graphile/postgraphile) - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
- [Hasura](https://github.com/hasura/graphql-engine) - Provides instant real-time GraphQL APIs over new or existing PostgreSQL databases.
- [subZero](https://subzero.cloud/) - GraphQL and REST API for databases.

<a name="lua" />

### Lua

- [graphql-lua](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="elm" />

### Elm

- [elm-graphql](https://github.com/dillonkearns/elm-graphql) - GraphQL for Elm.

<a name="clojure" />

### Clojure

- [graphql-clj](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation.
- [Lacinia](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure.
- [graphql-query](https://github.com/district0x/graphql-query) - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

- [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

- [GraphQL](https://github.com/GraphQLSwift/GraphQL) - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

- [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml.

<a name="android" />

### Android

- [apollo-android](https://github.com/apollographql/apollo-android) - 📟 A strongly-typed, caching GraphQL client for Android, written in Java.

<a name="android-example" />

#### Android Examples

- [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

- [apollo-ios](https://github.com/apollographql/apollo-ios) - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
- [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit) - Apollo Client developer tools bridge for Apollo iOS.
- [Graphaello](https://github.com/nerdsupremacist/Graphaello) - Type Safe GraphQL directly from SwiftUI.

<a name="ios-example" />

#### iOS Examples

- [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

- [re-graph](https://github.com/oliyh/re-graph) - A GraphQL client for ClojureScript with bindings for re-frame applications.

<a name="reasonml" />

### ReasonML

- [reason-apollo](https://github.com/apollographql/reason-apollo) - ReasonML binding for Apollo Client.
- [ReasonQL](https://github.com/sainthkh/reasonql) - Type-safe and simple GraphQL Client for ReasonML developers.
- [reason-urql](https://github.com/FormidableLabs/reason-urql) - ReasonML binding for urql Client.

<a name="dart" />

### Dart

- [graphql-flutter](https://github.com/zino-app/graphql-flutter) - A GraphQL client for Flutter.
- [Artemis](https://github.com/comigor/artemis) - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

- [async-graphql](https://github.com/async-graphql/async-graphql) - High-performance server-side library that supports all GraphQL specifications.
- [juniper](https://github.com/graphql-rust/juniper) - GraphQL server library for Rust.
- [graphql-client](https://github.com/tomhoule/graphql-client) - GraphQL client library for Rust with WebAssembly support.
- [graphql-parser](https://github.com/graphql-rust/graphql-parser) - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.

<a name="rust-example" />

#### Rust Examples

- [Warp GraphQL Juniper](https://graphql-rust.github.io/) - Warp web framework integration example with a Juniper GraphQL server.

<a name="d" />

### D (dlang)

- [graphqld](https://github.com/burner/graphqld) - GraphQL server library for D.

<a name="r" />

### R (Rstat)

- [ghql](https://github.com/ropensci/ghql) - General purpose GraphQL R client.
- [GraphQL](https://github.com/ropensci/graphql) - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.
- [gqlr](https://github.com/schloerke/gqlr) - R GraphQL Implementation.

<a name="julia" />

### Julia

- [Diana.jl](https://github.com/codeneomatrix/Diana.jl) - A Julia GraphQL client/server implementation.
- [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl) - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

- [GraphQL](https://github.com/graphql-crystal/graphql) - Server library for Crystal.
- [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - Library inspired by graphql-ruby, go-graphql, and graphql-parser.
- [crystal-gql](https://github.com/itsezc/crystal-gql) - GraphQL client shard inspired by Apollo client.
- [graphql.cr](https://github.com/garymardell/graphql.cr) - GraphQL shard.

### Ballerina

- [GraphQL](https://github.com/ballerina-platform/module-ballerina-graphql) - Standard Ballerina library providing GraphQL client and server implementations with built-in subscription support.
- [GraphQL CLI](https://github.com/ballerina-platform/graphql-tools) - A CLI tool to generate Ballerina code from GraphQL schema and GraphQL schema from Ballerina code. It also provides functionality to generate usage-specific GraphQL clients using GraphQL schemas and documents.

#### Ballerina Samples

- [Ballerina GraphQL Examples](https://github.com/ballerina-platform/module-ballerina-graphql/tree/master/examples) - Sample implementations of GraphQL services in Ballerina.
- [Convert Weather REST API to GraphQL API](https://github.com/ThisaruGuruge/weather-rest-api-to-graphql) - Example demonstrating REST API conversion to GraphQL.

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

- [GraphiQL](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
- [GraphQL Editor](https://github.com/graphql-editor/graphql-editor) - Visual Editor & GraphQL IDE.
- [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph.
- [Altair GraphQL Client](https://github.com/altair-graphql/altair) - A beautiful feature-rich GraphQL Client for all platforms.
- [Brangr](https://github.com/networkimprov/brangr) - A unique, user-friendly data browser/viewer for any GraphQL service, with attractive result layouts.
- [Insomnia](https://insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
- [Postman](https://learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
- [Bruno](https://github.com/usebruno/bruno) - Fast, open source API client, which stores collections offline-only in a Git-friendly plain text markup language.
- [Escape GraphMan](https://github.com/Escape-Technologies/graphman) - Generate a complete Postman collection from a GraphQL endpoint.
- [Apollo Sandbox](https://sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
- [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye) - View any GraphQL schema as a dynamic and interactive graph.
- [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
- [Firecamp - GraphQL Playground](https://firecamp.io/graphql) - The fastest collaborative GraphQL playground.
- [CraftQL](https://github.com/yamafaktory/craftql) - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.
- [gqt](https://github.com/eerimoq/gqt) - Build and execute GraphQL queries in the terminal.
- [Hackolade](https://studio.hackolade.com/) - Visual GraphQL schema editor that generates Schema Definition Language files and documents existing endpoints with introspection.
- [Smart Formatter - GraphQL Query Formatter](https://smartformatter.com/tools/graphql-query-formatter) - A client-side, browser-only tool to format, beautify, and validate GraphQL queries and schemas instantly.
- [Mongrel](https://www.visorcraft.com/) - Desktop workbench with a GraphQL client, plus HTTP, WebSocket, and gRPC, inside a multi-database GUI.
- [GalleonQL](https://galleonql.com/) - A desktop API client built specifically for GraphQL (macOS, Windows, Linux), pairing an introspected schema browser with an incremental query builder and switchable endpoint profiles.


<a name="tool-testing" />

### Tools - Testing, Prototyping & Mocking

- [Beeceptor](https://beeceptor.com/graphql-mock-server/) - A no-code platform for creating AI-powered **GraphQL Mock Servers** from your schema (SDL) with rules, stateful mocking, mutation/subscription, to speed up development and integration testing.
- [graphql-to-karate](https://github.com/wbaldoumas/graphql-to-karate) - **Generate Karate API tests** from your GraphQL schemas.
- [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
- [GraphQL Inspector](https://the-guild.dev/graphql/inspector) - A tool to **validate schemas**, compare schema changes, find breaking changes, and check document coverage against a schema.
- [Microcks](https://microcks.io/) - Open source, cloud native tool for API mocking and testing with GraphQL support.
- [mockd](https://github.com/getmockd/mockd) - Multi-protocol mock server with GraphQL schema mocking, resolver configuration, and query validation. Also supports HTTP, gRPC, WebSocket, MQTT, and SOAP.
- [Keploy](https://keploy.io/) - Open-source AI Powered API testing tool that generates test cases and **data mocks automatically by recording real API traffic**. Supports GraphQL, REST, and gRPC.
- [Step CI](https://stepci.com) - Open source API **testing and monitoring** with GraphQL support.
- [MockBase](https://mockbase.org) - Hosted mock server for REST, GraphQL, and SOAP with fault injection, stateful mocks, and OpenAPI import.

<a name="tool-security" />

### Tools - Security

- [GraphCrawler - The all-in-one GraphQL Security toolkit](https://github.com/gsmith257-cyber/GraphCrawler) - Automated penetration testing toolkit for GraphQL, written in Python.
- [Escape - The GraphQL Security Scanner](https://graphql.security/) - One-click security scan of your GraphQL endpoints. Free, no login required.
- [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder) - Blazing fast GraphQL endpoint finder using subdomain enumeration, script analysis, and brute force.
- [StackHawk - GraphQL Vulnerability Scanner](https://www.stackhawk.com/blog/automated-graphql-security-testing) - Automated GraphQL security scanning and vulnerability detection.
- [InQL Scanner](https://github.com/doyensec/inql) - Burp extension for GraphQL security testing.
- [GraphQL Raider](https://portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) - Burp Suite extension for GraphQL security testing.
- [WAF for GraphQL](https://lab.wallarm.com/api-security-solution/) - Web application firewall for GraphQL APIs.
- [GraphQL Intruder](https://github.com/davinerd/gql_intruder) - Plugin-based Python script for performing GraphQL vulnerability assessments.
- [GraphQL Cop](https://github.com/dolevf/graphql-cop) - Security audit utility for GraphQL.
- [GraphQLer](https://github.com/omar2535/GraphQLer) - Dependency-aware dynamic GraphQL testing tool.
- [Vulert](https://vulert.com) - Detects vulnerabilities in open source dependencies without accessing code, with support for JavaScript, PHP, Java, Python, and more.
- [hasura-security](https://github.com/Perufitlife/hasura-security) - Active-probe security auditor for self-hosted Hasura GraphQL Engine that detects open introspection, public-role data leaks, and unauthenticated endpoints.

### Tools - Browser Extensions

- [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools) - GraphQL debugging tools for Apollo Client in the Chrome developer console.
- [GraphQL Network Inspector](https://chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln) - A simple and clean chrome dev-tools extension for GraphQL network inspection.

### Tools - Docs

- [graphdoc](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema.
- [gqldoc](https://github.com/Code-Hex/gqldoc) - The easiest way to make API documents for GraphQL.
- [spectaql](https://github.com/anvilco/spectaql) - Autogenerate static GraphQL API documentation.
- [graphql-markdown](https://graphql-markdown.github.io/) - Flexible documentation for GraphQL powered with Docusaurus.
- [xyd](https://xyd.dev) - Generate GraphQL API docs.
- [Cortex](https://github.com/cortex-docs/cortex) - Generates interactive API documentation and typed SDKs from GraphQL schemas.

### Tools - Editor Plugins

- [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that integrates with the Apollo platform.
- [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
- [vim-graphql](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
- [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom.

### Tools - Miscellaneous

- [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on a REST API described in Swagger that supports migrating from REST to GraphQL in five minutes.
- [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) - A language service plugin complete and validate GraphQL query in TypeScript template strings.
- [apollo-tracing](https://github.com/apollographql/apollo-tracing) - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
- [json-graphql-server](https://github.com/marmelab/json-graphql-server) - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
- [Prisma](https://github.com/prisma/prisma) - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
- [Typetta](https://github.com/twinlogix/typetta) - Node.js ORM written in TypeScript for type lovers and the GraphQL, Node.js, and TypeScript stack.
- [tuql](https://github.com/bradleyboy/tuql) - Automatically create a GraphQL server from any SQLite database.
- [Bit](https://github.com/teambit/bit) - Organize GraphQL API components for reuse across projects.
- [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql) - Convert OpenAPI Specification or Swagger definitions to GraphQL interfaces.
- [Retool](https://retool.com/) - Internal tools builder on top of GraphQL APIs with a GraphQL IDE and schema explorer.
- [dataloader-codegen](https://github.com/Yelp/dataloader-codegen) - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).
- [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector) - Validate schemas and operations, get schema change notifications, find breaking changes and similar types, and measure schema coverage.
- [amplication](https://github.com/amplication/amplication) - Open source low-code development tool that builds database applications with REST and GraphQL APIs.
- [Blendbase](https://github.com/blendbase/blendbase) - Single open source GraphQL API for connecting CRMs to SaaS applications.
- [DronaHQ](https://www.dronahq.com/) - Build internal tools, dashboards, and admin panels on top of GraphQL data in minutes.
- [Dynaboard](https://dynaboard.com) - Generate low-code web apps from any GraphQL API using AI.
- [gqlhash](https://github.com/romshark/gqlhash) - Lightning fast query hasher that ignores formatting diffs and comments and supports multiple hashing functions.
- [Apollo APQ Debugger](https://github.com/rookieInTraining/apq-debugger) - Reveal full GraphQL queries behind Apollo APQ hashes. Inspect fallback flow and debug Automatic Persisted Queries in DevTools.
  <a name="databases" />


## Databases

- [Cube](https://github.com/cube-js/cube.js) - Headless BI platform for building data applications with GraphQL, SQL, and REST APIs with sub-second latency.
- [Dgraph](https://dgraph.io/) - Scalable, distributed, low-latency, high-throughput graph database with GraphQL as the query language.
- [EdgeDB](https://edgedb.com/) - The next generation object-relational database with native GraphQL support.
- [ArangoDB](https://arangodb.com/) - Native multi-model database with GraphQL support through Foxx microservices.
- [Weaviate](https://github.com/semi-technologies/weaviate) - Cloud-native, modular, real-time vector search engine with a GraphQL interface that scales machine learning models.

<a name="services" />

## Services

- [AWS AppSync](https://aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps.

- [Moesif API Analytics](https://www.moesif.com/features/graphql-analytics) - A GraphQL analaytics and monitoring service to find functional and performance issues.
- [Booster framework](https://booster.cloud/) - An open-source framework that makes you _completely_ forget about infrastructure and allows you to focus exclusively on your business logic. It autogenerates a GraphQL API for your models, supporting mutations, queries, and subscriptions.
- [Nhost](https://nhost.io/) - Open source backend with a GraphQL API over Postgres, plus auth, storage and functions.
- [Saleor](https://github.com/mirumee/saleor/) - GraphQL-first headless e-commerce platform.
- [Stargate](https://stargate.io/docs/latest/quickstart/qs-graphql-cql-first.html) - Open source data gateway currently supporting Apache Cassandra&reg; and DataStax Enterprise.
- [Vedika](https://vedika.io) - Vedic astrology AI API with GraphQL support for horoscopes, birth charts, kundali matching, and 108+ endpoints.
- [Grafbase](https://grafbase.com) - Instant GraphQL APIs for any data source.
- [Unchained Engine](https://github.com/unchainedshop/unchained) - GraphQL-first open-source headless e-commerce framework for Node.js.
- [Codex](https://www.codex.io) - GraphQL API for real-time and historical on-chain data, including token prices, charts, and holders across 90+ networks.

### CDN

- [GraphCDN](https://graphcdn.io/) - GraphQL CDN for caching GraphQL APIs.

### CMS

- [DatoCMS](https://www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
- [Apito](https://apito.io/) - A Cloud Based Headless CMS with CDN, Webhooks, Team Collaborations, Content Revision, Cloud Functions.
- [Hygraph](https://hygraph.com/) - Build Scalable Content Experiences.
- [Cosmic](https://www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.
- [Graphweaver](https://graphweaver.com/) - Turn multiple datasources into a single GraphQL API.

<a name="book" />

## Books

- [The GraphQL Guide](https://graphql.guide) - Comprehensive GraphQL learning guide.
- [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - Guide to building GraphQL APIs in Elixir.
- [The Road to GraphQL](https://www.roadtographql.com/) - Full-stack GraphQL tutorial and learning resource.
- [Practical GraphQL](https://leanpub.com/book-graphql) - Practical guide to implementing GraphQL applications.
- [Production Ready GraphQL](https://book.productionreadygraphql.com) - Best practices for production GraphQL systems.
- [Full Stack GraphQL Applications](https://www.manning.com/books/fullstack-graphql-applications) - Complete guide to full-stack GraphQL development.

<a name="video" />

## Videos

- [GraphQL: The Documentary](https://www.youtube.com/watch?v=783ccP__No8) - Documentary on the history and development of GraphQL.
- [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY) - Quick introduction to GraphQL fundamentals.
- [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU) - Talk on data fetching patterns for React.
- [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU) - Presentation on React Native and Relay integration.
- [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8) - Overview of GraphQL concepts and capabilities.
- [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo) - Tutorial on building a GraphQL server.
- [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4) - Case study of GraphQL adoption at the Financial Times.
- [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg) - Introduction to the Relay framework for React applications.
- [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg) - Guide to building and deploying Relay applications.
- [Introduction to GraphQL](https://vimeo.com/144817545) - Introductory talk on GraphQL.
- [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0) - Strategies for scaling GraphQL APIs.
- [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be) - Future directions of the Phoenix web framework.
- [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M) - Discussion about GraphQL development.
- [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ) - Tutorial on building GraphQL servers with Node.js.
- [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU) - Comprehensive GraphQL server tutorial.
- [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8) - Podcast episode on REST to GraphQL migration.
- [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU) - Conference talk on the future of GraphQL.
- [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA) - Facebook's perspective on GraphQL usage.
- [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8) - Mobile development with GraphQL.
- [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68) - Video series on GraphQL server development.
- [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f) - Complete GraphQL tutorial series.
- [Five years of GraphQL](https://www.youtube.com/watch?v=s8meG38iZAM) - Retrospective on five years of GraphQL.
- [GraphQL is for Everyone by Moon Highway](https://moonhighway.teachable.com/p/graphql-is-for-everyone) - Beginner-friendly GraphQL course.

<a name="podcast" />

## Podcasts

- [GraphQL.FM](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) - Podcast series on GraphQL development and best practices.

<a name="style-guide" />

## Style Guides

- [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial) - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
- [GitLab GraphQL API Style Guide](https://docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
- [Yelp GraphQL Guidelines](https://yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
- [Principled GraphQL](https://principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

- [Official GraphQL blog](https://graphql.org/blog/) - News and technical articles from the GraphQL project.
- [Building Apollo](https://blog.apollographql.com/) - Product updates and engineering articles from Apollo GraphQL.
- [The Guild blog](https://medium.com/the-guild) - Articles from The Guild about GraphQL tools and practices.
- [Production Ready GraphQL blog](https://productionreadygraphql.com) - Guidance for designing and operating production GraphQL systems.

<a name="security-blog" />

### Blogs - Security

- [Escape - The GraphQL Security Blog](https://escape.tech/blog) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.
- [9 GraphQL Security Best Practices](https://escape.tech/blog/9-graphql-security-best-practices/) - Practical measures for protecting GraphQL APIs from common attacks.
- [Discovering GraphQL Endpoints and SQLi Vulnerabilities](https://medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e) - Walkthrough of GraphQL endpoint discovery and SQL injection testing.
- [Securing GraphQL API](https://lab.wallarm.com/securing-graphql-api/) - Overview of common GraphQL security risks and mitigations.
- [Security Points to Consider Before Implementing GraphQL](https://nordicapis.com/security-points-to-consider-before-implementing-graphql/) - Security considerations for teams adopting GraphQL.
- [Authorization Patterns in GraphQL](https://www.osohq.com/post/graphql-authorization) - Comparison of authorization patterns for GraphQL APIs.

<a name="post" />

## Posts

- [GraphQL federation example with Apollo Federation and Apollo GraphOS](https://cube.dev/blog/graphql-federation-example-with-apollo-federation-and-apollo-graphos) - Tutorial for federating services with Apollo Federation, GraphOS, and Cube.
- [GraphQL federation with Hasura GraphQL Engine and Cube](https://cube.dev/blog/graphql-federation-with-hasura-graphql-engine) - Tutorial for federating Hasura and Cube GraphQL APIs.
- [Using DataLoader to batch GraphQL requests](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433) - Guide to batching and caching data access with DataLoader.
- [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html) - Original announcement introducing Relay and GraphQL.
- [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html) - Early overview of GraphQL's design and query model.
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47) - Community answers to common questions about Relay.
- [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2) - Tutorial for creating a basic GraphQL server.
- [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/) - Introduction to building GraphQL APIs with Node.js.
- [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159) - Introduction to GraphQL and its benefits over REST APIs.
- [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247) - Account of migrating an API from REST to GraphQL.
- [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/) - Tutorial for implementing a basic GraphQL API.
- [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/) - Tutorial for connecting a Node.js GraphQL server to SQL.
- [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql) - Presentation about GraphQL adoption at the Financial Times.
- [Implementing GraphQL RBAC Authorization: A Practical Guide](https://www.permit.io/blog/implementing-graphql-authorization) - Guide to implementing role-based access control in GraphQL APIs.
- [From REST to GraphQL](https://jacobwgillespie.com/2015-10-09-from-rest-to-graphql) - Comparison of GraphQL's data model with REST APIs.
- [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/) - Original announcement explaining GraphQL's purpose and design.
- [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/) - Introduction to real-time GraphQL subscriptions with Relay.
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6) - Tutorial for building a Hacker News client with Relay.
- [GraphQL Schema Reference](https://graphql.org/learn/schema/) - Official documentation explaining GraphQL schema definition language and shorthand notation.
- [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/) - Introduction to the design of GitHub's GraphQL API.
- [GitHub GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61) - Tutorial for consuming GitHub's GraphQL API from React.
- [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e) - Guide to testing GraphQL queries and mutations with Jest.
- [How to implement viewerCanSee in GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464) - Guide to exposing field visibility through a GraphQL schema.
- [Preventing traversal attacks on your GraphQL API](https://blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/) - Techniques for limiting maliciously deep GraphQL queries.
- [Mock your GraphQL server realistically with faker.js](https://dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo) - Tutorial for generating realistic mock GraphQL data with Faker.
- [Create an infinite loading list with React and GraphQL](https://dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh) - Tutorial for cursor-based pagination with React and GraphQL.
- [REST vs GraphQL](https://www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/) - Comparison of REST and GraphQL API tradeoffs.
- [Authentication and Authorization for GraphQL APIs](https://www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/) - Guide to authentication and authorization patterns for GraphQL APIs.
- [Build a GraphQL API with Siler on top of Swoole](https://www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole) - Tutorial for building a PHP GraphQL API with Siler and Swoole.
- [Fluent GraphQL clients: how to write queries like a boss](https://hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/) - Survey of fluent GraphQL client libraries across several languages.
- [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/) - Guide to using GraphQL as a data layer for serverless applications.
- [A deep-dive into Relay, the friendly & opinionated GraphQL client](https://hasura.io/blog/deep-dive-into-relay-graphql-client/) - Detailed introduction to Relay's architecture and data-fetching model.
- [Make Your GraphQL API Easier to Adopt Through Components](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1) - Guide to packaging GraphQL schemas and resolvers as reusable components.
- [Undocumented: keeping parts of your GraphQL schema hidden from introspection](https://www.useanvil.com/blog/engineering/undocumented-directive/) - Guide to hiding selected schema elements from GraphQL introspection.
- [GraphQL Subscriptions with Apache Kafka in Ballerina](https://medium.com/ballerina-techblog/graphql-subscriptions-with-apache-kafka-in-ballerina-b3c296d333cd) - Tutorial for streaming Kafka messages through Ballerina GraphQL subscriptions.
- [How to Test your GraphQL Endpoints](https://escape.tech/blog/8-most-common-graphql-vulnerabilities/) - Overview of common GraphQL vulnerabilities and how to test for them.

<a name="tutorials" />

## Tutorials

- [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
- [Apollo Odyssey](https://odyssey.apollographql.com/) - Apollo's free interactive learning platform.
- [learning-graphql](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.
- [GraphQL Roadmap](https://roadmap.sh/graphql) - Step by step guide to learn GraphQL.
- [OWASP GraphQL Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/GraphQL_Cheat_Sheet.html) - Comprehensive guide for securing GraphQL endpoints and preventing vulnerabilities.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.
