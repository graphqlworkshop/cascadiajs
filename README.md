<p align="center">
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://begin-static-p6uw2-production.s3.us-west-2.amazonaws.com/forest-1dg/images/cjs-sunbreak-logo.svg" width="100" alt="cascadiajs"/>
</p>

# CascadiaJS GraphQL Workshop

Welcome! We're really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Alex Banks**: [Twitter](https://twitter.com/moontahoe) | [Email](mailto:alex@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## Day 1

### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Moon Highway Vote Playground](http://vote.moonhighway.com)
- [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [SWAPI: Star Wars API](http://graphql.org/swapi-graphql/)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### GraphQL Schema Definition Language

- [Schema Definition Language](https://slides.com/moonhighway/schema-definition-language/)
- [City to City Through Types](https://codesandbox.io/s/5vzn2rkzxn)
- [Modular Schema](https://github.com/eveporcello/schema-workshop/tree/master/06-extras/modularizing-a-schema/finished)
- [Lab Instructions](https://slides.com/moonhighway/schema-lab/)
- [Possible Lab Solutions](https://github.com/graphqlworkshop/schema-activity)

### Building a GraphQL API

- [Exercise Start Files](https://github.com/graphqlworkshop/snowtooth-api)
- [Lab Instructions](https://slides.com/moonhighway/server-lab/)
- [Sample Data](https://bit.ly/2VF5zJU)
- [Starting Schemas](https://github.com/graphqlworkshop/schema-activity)
- [Simple Strava Sample](https://github.com/eveporcello/simple-strava-sample/blob/master/index.js)
- [REST Data Sources](https://github.com/MoonHighway/countries-datasources)

### Mid Class Evaluation

- [Anonymous Evaluation](https://docs.google.com/forms/d/e/1FAIpQLSe0W190l4q11dG0rsW-1y6nc5grqwCEsLgz_HwznmZrCq4UKw/viewform?usp=sf_link)

## Day 2

### Unions and Interfaces

- [Unions & Interfaces Slides](https://slides.com/moonhighway/unions-interfaces)
- [Refactored Pet Library](http://funded-pet-library.moonhighway.com/)
- [Union Types](https://codesandbox.io/s/rm2rx3opqm)
- [Interfaces](https://codesandbox.io/s/71x8n304r1)
- [Event Interfaces](https://codesandbox.io/s/mm36pp93p9)
- [Union Search - Complete](https://github.com/graphqlworkshop/snowtooth-unions/tree/complete)
- [Employee Interface - Complete](https://github.com/graphqlworkshop/interface-lab/tree/complete)

### Apollo Client

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### React & Apollo

- [React Overview](https://slides.com/moonhighway/react-overview)
- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Lab Instructions](https://slides.com/moonhighway/client-lab/)

## Final Evaluation

- [Evaluation](https://docs.google.com/forms/d/e/1FAIpQLSeWm2NsU1lPN-U3fIyAGpmZiu2Q3a685zheg1cvzzH4oF2n5Q/viewform?usp=sf_link)
