# Awesome Relay [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome resources for [Relay](https://github.com/facebook/relay), based on the [Awesome](https://github.com/sindresorhus/awesome/) project

# Table of Contents
- [Learning Resources](https://github.com/expede/awesome-relay#learning-resources)
  - [Documentation](https://github.com/expede/awesome-relay#documentation)
  - [Tutorials](https://github.com/expede/awesome-relay#tutorials)
  - [Overviews](https://github.com/expede/awesome-relay#overviews)
  - [FAQs](https://github.com/expede/awesome-relay#faqs)
  - [Example Implementations](https://github.com/expede/awesome-relay#example-implementations)
  - [Lists of Lists](https://github.com/expede/awesome-relay#lists-of-lists)
- [Ecosystem](https://github.com/expede/awesome-relay#ecosystem)
  - [Libraries & Packages](https://github.com/expede/awesome-relay/blob/master/README.md#libraries--packages)
  - [Other Language Support](https://github.com/expede/awesome-relay/blob/master/README.md#other-language-support)
  - [Tooling](https://github.com/expede/awesome-relay#tooling)
- [Miscellaneous](https://github.com/expede/awesome-relay#miscellaneous)

# Learning Resources
## Documentation
- [Official Docs](https://facebook.github.io/relay/docs/getting-started.html#content) - Official Relay documentation.

## Tutorials
- [Getting Started with Relay](https://auth0.com/blog/2015/10/06/getting-started-with-relay/) - One of the few detailed walk throughs of hand-on Relay.
- [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6#.1i64q1pf9) - A complete workable example.
- [Facebook Relay talk - Lunch and Learn session](https://www.youtube.com/watch?v=sP3n-nht0Xo) - Walkthrough of building a simple app, and demonstration of [GraphiQL](https://github.com/graphql/graphiql).

## Overviews
- [React Data Fetching with Relay](http://www.sitepoint.com/react-data-fetching-with-relay/) - Clear conceptual overview of Relay's moving parts and magic.
- - [Joseph Savona - Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg) - Conceptual overview of Relay from the Facebook team.
- [F8 2015 - React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU) - Overview of Relay, some about the philosophy.
- [Relay - Daniel Dembach - Hamburg React.js Meetup](https://www.youtube.com/watch?v=dvWTxy1eY6s) - A good general overview of Relay, some discussion of alternatives. Common questions are covered in Q&A at the end.
- [Facebook Relay talk - Lunch and Learn session](https://www.youtube.com/watch?v=sP3n-nht0Xo) - Walkthrough of building a simple app, and demonstration of [GraphiQL](https://github.com/graphql/graphiql).
- [React with Relay and GraphQL with Andrew Smith](https://www.youtube.com/watch?v=Cfna8gwt9h8) - High level overview of Relay and GraphQL, with some useful discussion from the audience. Some discussion of other front-end frameworks, as well.

## FAQs
- [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47) - Common questions answered! Relay resources are scarce at the moment, so this is very helpful if you get stuck.
 
## Example Implementations
- [`relay-chat`](https://github.com/transedward/relay-chat) - Relay with routing and pagination.
- [`koa-graphql-relay-example`](https://github.com/chentsulin/koa-graphql-relay-example) - "TODO" app with [`koa-graphql`](https://github.com/chentsulin/koa-graphql) and `relay`.

## Lists of Lists
- [Relay and GraphQL Introduction Materials](https://quip.com/oLxzA1gTsJsE)

# Ecosystem
## Libraries & Packages
- [`graphql-relay-js`](https://github.com/graphql/graphql-relay-js) - Simplifies creating a JS GraphQL server for `react-relay`.
- [Babel Relay Plugin](https://www.npmjs.com/package/babel-relay-plugin) - Use Relay the latest ES6+ syntax.
- [`react-router-relay`](https://github.com/relay-tools/react-router-relay) - `react-router` bindings for Relay. Greatly simplifies many local state UI uses cases.
  - [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9#.h91614i65) - A well-articulated walk through of `react-router-relay`, and the problems that it solves.
  - [`relay-nested-routes`](https://www.npmjs.com/package/relay-nested-routes) - Generate nested routes that reflect nested data. Helpful for managing deep data.
- [`relay-decorator`](https://github.com/4Catalyzer/relay-decorators) - Simply syntax for Relay containers with ES7 decorators (`@` syntax)
- [`recompose-relay`](https://www.npmjs.com/package/recompose-relay) - Ease composition of Relay containers by currying and providing the component after the container.
- [`relay-local-schema`](https://github.com/relay-tools/relay-local-schema) - Use a local schema; no need for a remote GraphQL server.
- [`react-native-relay`](https://github.com/lenaten/react-native-relay) - Use Relay with React Native.
  - May be supported [out of the box](https://github.com/facebook/relay/issues/26) in the future.
- [`relay-sink`](https://github.com/acdlite/relay-sink) - Use Relay to fetch and store data outside of a React component.
 
## Other Language Support
- [`graphql-relay-ruby`](https://github.com/rmosolgo/graphql-relay-ruby) - Relay helpers for GraphQL & Ruby.
- [`graphql-relay-py`](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a `graphql-py` server supporting `react-relay`.
- [Go Relay](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a graphql-go server supporting react-relay.
- [`sangria-relay`](https://github.com/sangria-graphql/sangria-relay) - Relay support for [Sangria](http://sangria-graphql.org) (Scala).

## Tooling
- [GraphiQL](https://github.com/graphql/graphiql) - A library to introspect GraphQL, test queries and mutations.
  - [GraphiQL App](https://github.com/skevy/graphiql-app) - A standalone app for viewing GraphQL, introspection docs, and testing queries/mutations. Invaluable for debugging your Relay app.

# Miscellaneous
- [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit) - An app that it already set up with a basic setup. Just clone and tweak to suit your needs!
- [Simple Relay Starter](https://github.com/mhart/simple-relay-starter) - A Browserify version of the [Relay Starter Kit](https://github.com/relayjs/relay-starter-kit).
