# Derpibooru API Docs
Unofficial API docs for https://derpibooru.org.

Written using the [OpenAPI](https://swagger.io/docs/specification/about/) specification and presented using [Swagger UI](https://swagger.io/swagger-ui/).

## See it in action here: https://derpi-api.nerd.horse/

### Building
`json-refs` is used to merge all the components into a single `.yaml.` spec file:
```sh
npm install -g json-refs
json-refs resolve src/index.yaml --filter relative --force > derpibooru-openapi.gen.yaml
```
