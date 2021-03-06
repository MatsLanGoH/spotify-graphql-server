# spotify-graphql-server

[![Greenkeeper badge](https://badges.greenkeeper.io/lowsky/spotify-graphql-server.svg)](https://greenkeeper.io/)

This demonstrates how to build a GraphQL server which fetches data from an external API (Spotify),
see [german blog post](https://blog.codecentric.de/2017/09/graphql-mit-spotify-teil-1-server) or
 [english blog post](https://blog.codecentric.de/en/2017/01/lets-build-spotify-graphql-server)

Use the [Live Demo](https://spotify-graphql-server.herokuapp.com/) as a playground for graphql queries.

## Get started

### prerequisites

For running this example locally, you must 
register your own application at spotify and 
adapt the [./.env.example] file.

Install any `node.js` >= 8, with support for async/await.

Run `npm install`. 

### run server

`npm start` to start the graphql server, then open http://localhost:4000/

`npm run watch` to start the graphql server which automatically restarts when any sources were changed (driven by `nodemon`)

### run tests

`npm test`

### print GraphQL schema idl

`npm run printSchema`

![Analytics](https://ga-beacon.appspot.com/UA-72383363-1/lowsky/spotify-graphql-server/README.md)
