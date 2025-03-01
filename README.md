<br>
<h3 align="center">
  Relay Modern Boilerplate
</h3>
<p align="center">
  <a href="https://www.docker.com/">Docker</a>
  +
  <a href="https://www.postgresql.org/">Postgres</a>
  +
  <a href="https://www.graphile.org/postgraphile/">PostGraphile</a>
  +
  <a href="https://webpack.js.org/">Webpack</a>
  +
  <a href="https://reactjs.org/">React</a>
  +
  <a href="https://www.typescriptlang.org/">TypeScript</a>
  +
  <a href="http://facebook.github.io/relay/docs/en/thinking-in-relay.html">Relay Modern</a>
  =
  <b>Awesomeness</b>
</p>
<br>

# Quick start

1.  Make sure that you have [Docker](https://www.docker.com/products/docker-engine) and [Docker Compose](https://docs.docker.com/compose/install/) installed
2.  Clone this repo using `git clone --depth=1 https://github.com/enisdenjo/relay-modern-boilerplate.git`
3.  Change directory to `relay-modern-boilerplate`
4.  Run `docker-compose up` to build and start [Postgres](https://www.postgresql.org/) + [PostGraphile](https://www.graphile.org/postgraphile/) + [webpack-dev-server](https://github.com/webpack/webpack-dev-server)<br>
    _Initial build may take some time because we need to install [Watchman](https://facebook.github.io/watchman/) from source_
    - Postgres database is exposed at: **[postgres://localhost:5432/graphql](postgres://localhost:5432/graphql)**
    - GraphQL endpoint is located at: **[http://localhost:4400/graphql](http://localhost:4400/graphql)**<br>
      _Explore the schema using [GraphiQL](https://github.com/graphql/graphiql) at: [http://localhost:4400/graphiql](http://localhost:4400/graphiql)_
    - The application is located at: **[http://localhost:4401](http://localhost:4401)**<br>
      _Use `john@doe.com:password` to login_

# Documentation

Detailed documentation coming soon, for now happy code digging. 😁
