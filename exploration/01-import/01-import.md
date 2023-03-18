# Importing a Postman collection

Bruno version:  v0.10.2 (Mac M1)

## Issues

1. GraphQL body did not import.  I cannot figure out where to capture the query body in Bruno (TODO: come back to this)
1. Collection variables are not imported.  Seems that you have to add these into an environment.  (TODO: should collection variable be imported into an "import" environment)

### Workarounds (i.e. probably not an issue)

1. Path variables aren't supported.  Workaround is to add the collection / request variable directly to the URL
