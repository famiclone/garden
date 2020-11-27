# GraphQL

GraphQL is a query language for API, that add ability to get many resources in a single request.

```javascript
// Scheme
type User {
  name: String
  tagline: String
  contributors: [User]
}

// GraphQL request
{
  project(name: "GraphQL") {
    tagline
    name
  }
}

// Response
{
  "project": {
    "tagline": "A query language for APIs",
    "name": "John"
  }
}
```
