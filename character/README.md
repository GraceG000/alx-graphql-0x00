# Character Queries

This directory contains GraphQL queries and their outputs for fetching Rick and Morty characters by ID using the Rick and Morty GraphQL API.

## Files

- `character-id-1.graphql` / `character-id-1-output.json`
- `character-id-2.graphql` / `character-id-2-output.json`
- `character-id-3.graphql` / `character-id-3-output.json`
- `character-id-4.graphql` / `character-id-4-output.json`

Each `.graphql` file contains a query using `character(id: ID!)` to fetch the following fields: `id, name, status, species, type, gender`.

---

# Characters Queries

This directory contains GraphQL queries and outputs for retrieving a paginated list of Rick and Morty characters.

## Description

Each query uses the `characters(page: Int)` field to fetch characters from the Rick and Morty GraphQL API.

## Fields Retrieved

- id
- name
- status
- image

## Files

- characters-page-1.graphql / characters-page-1-output.json
- characters-page-2.graphql / characters-page-2-output.json
- characters-page-3.graphql / characters-page-3-output.json
- characters-page-4.graphql / characters-page-4-output.json
