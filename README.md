# GraphQL Character Pagination Query

This project demonstrates how to fetch a paginated list of characters using a GraphQL API.

## Objective

Fetch characters from page 1 through 4 and retrieve the following fields:

- `id`
- `name`
- `status`
- `image`

## Files

- `characters-page-{1-4}.graphql` – Contains the GraphQL query for each page.
- `characters-page-{1-4}-output.json` – Stores the JSON output from the GraphQL server response.

## Example Query

```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
```
