# Importing a Postman collection

Bruno version:  v0.20.0 (Mac M1)

## API used testing

I have a [Postman workspace](https://www.postman.com/dcoomber/workspace/bruno-comparison/overview) that includes copies of these collections.

1. [The Rick and Morty API](https://rickandmortyapi.com/) / [Postman collection](https://github.com/loopDelicious/rick-and-morty-postman)
1. [EskomSePush](https://documenter.getpostman.com/view/1296288/UzQuNk3E0

## Issues

### Rick and Morty API

1. GraphQL request is imported as a HTTP request.  I had to create a GraphQL request and copy the relevant details from Postman.

### EskomSePush API

1. Collection variables are not imported.  Collection variables must be set at runtime.  Seems that you have to add these into an environment.  (TODO: should collection variables be imported into an "import" environment?)
1. Collection Authorisation settings are not imported (as with collection variables, the settings likely have to be set at runtime)
1. Requests with brackets in name are renamed (bracket changed to `-`)... yet brackets are supported by Bruno
1. Request API token authorisation settings are not imported

## Workarounds (i.e. probably not an issue)

1. Path variables aren't supported.  Workaround is to add the collection / request variable directly to the URL
