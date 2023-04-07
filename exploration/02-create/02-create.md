# Create a collection

Bruno version:  v0.10.2 (Mac M1)

## Issues

1. No prompt to save changes when closing a request tab
1. Changing the order of requests is inconsistent (appears to randomly change the sort order)

## Ideas

1. A collection screen that allow users to capture metadata regarding the collection and its purpose
1. Set a default environment (auto-selected when first opening a collection)

### Logged / actioned
1. Adding a collection / request / folder dialog
   1. Tab order is not limited to the dialog, it includes elements on the main application (logged as https://github.com/usebruno/bruno/issues/129)
1. Adding a request
   1. HTTP vs. Http; Graphql vs. GraphQL (update proposed in https://github.com/usebruno/bruno/pull/130)
1. Exception occurs when request script references an element out of bounds in a response array (logged as https://github.com/usebruno/bruno/issues/127)
1. Cannot use CMD-A to select all text in the key column when adding headers, assertions or vars on requests.  CMD+A works as expected on the value column (logged as https://github.com/usebruno/bruno/issues/131)
1. Asserting on `res.body isJson` returns the error "Invalid Chai property: json. Did you mean "to"?" (logged as https://github.com/usebruno/bruno/issues/132)
