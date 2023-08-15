# cubejs sample repo

A quick start sample repository for [cubejs](https://cube.dev).

## steps

```shell
npm install -g cubejs-cli

npx cubejs create cube-sample-project -d postgres -t express

# explicitly install share, server-core, schema-compiler
npm i -S @cubejs-backend/server-core @cubejs-backend/schema-compiler @cubejs-backend/shared

# install all datasource drivers with the specific cube release(current: 0.33.47)
npm i -S @cubejs-backend/postgres-driver ... @cubejs-backend/databricks-jdbc-driver
```
