Forked from [example usage](https://github.com/OneGraph/graphiql-explorer-example) of [OneGraph](https://www.onegraph.com)'s open source [GraphiQL explorer](https://github.com/OneGraph/graphiql-explorer).

## Setup

Install dependencies:

```
npm install
# or
yarn install
```

## Run

Choose your endpoint by overriding `REACT_APP_GRAPHQL_ENDPOINT` env var - you can do this by creating `.env.local` file.

The default `.env` points to Bratislava homepage staging strapi instance.

Start the server:

```
npm run start
# or
yarn start
```

Your browser will automatically open to http://localhost:3000 with the explorer open.
