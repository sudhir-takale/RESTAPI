#### RestApi Design Practices

### Good Practices

- 1) Use Descriptive URIs: URI should be meaningful 

- 2) HTTP Verbs for Actions: use HTTP methods appropriately. 
    - Use GET for reading resources,
      -  POST for creating new resources,
       - PUT for updating resources, 
      -  DELETE for deleting resources,
       - PATCH for partial updates.

- 3) Use HTTP Status Codes Correctly: Return correct HTTP status codes to indicate the success or failure of the request. 

- 4) Error Handling: provide error message for clear understanding of error cause

- 5) Input Validation: Validate input parameters 

- 6) Use HTTPS: Always use HTTPS over HTTP as it provides more security

- 7) Provide Documentation: provide documentation for the API


#### Bad Practices:

- 1) Overuse of HTTP Methods: avoid using a one HTTP method for all operations. 

- 2) Poor Error Handling: poor error handling can make it difficult for clients to understand and handle errors. 

- 3) Excessive Nesting: Avoid excessive nesting in URIs or JSON responses. 

- 4) Overloading Endpoints: Don't overload endpoints with too many functionalities. Keep endpoints focused on specific resource types and actions.

- 5) Inconsistent Naming conventions: Maintain consistency in naming conventions.
