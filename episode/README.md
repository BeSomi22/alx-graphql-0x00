# Episode Query by ID – GraphQL Task

## Objective

Fetch the details of a specific episode using the `episode(id: ID!)` GraphQL field.

## GraphQL API Endpoint

You can use the Rick and Morty GraphQL API:

## Task

Write a GraphQL query to retrieve the following episode fields:

- `id`
- `name`
- `air_date`
- `episode`

## Files

Each query and its result should be stored in:

- `episode-id-1.graphql` – The query for episode ID 1
- `episode-id-1-output.json` – The JSON response from the GraphQL API

## Sample Query

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
```
