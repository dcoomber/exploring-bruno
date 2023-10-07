# Importing a Postman collection

Bruno version:  v0.10.2 (Mac M1)

## API used testing

1. [The Rick and Morty API](https://rickandmortyapi.com/) / [Postman collection](https://github.com/loopDelicious/rick-and-morty-postman)
1. [EskomSePush](https://documenter.getpostman.com/view/1296288/UzQuNk3E0

## Issues

1. GraphQL body did not import.  I cannot figure out where to capture the query body in Bruno (TODO: come back to this)
1. Collection variables are not imported.  Seems that you have to add these into an environment.  (TODO: should collection variable be imported into an "import" environment)

### Workarounds (i.e. probably not an issue)

1. Path variables aren't supported.  Workaround is to add the collection / request variable directly to the URL
