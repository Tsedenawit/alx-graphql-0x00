## Get Specific Episode by ID

This query retrieves a specific episode from the Rick and Morty API using its unique ID.

**File:** `episode/episode-page-1.graphql`

**Query Example:**

### Field retrieved

- id
- name
- episode
- air_date

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
