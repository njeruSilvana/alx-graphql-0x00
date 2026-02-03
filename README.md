# alx-graphql-0x00 — GraphQL Fundamentals

## Project Description

This repository contains the foundational GraphQL queries written against the **Rick and Morty GraphQL API** (`https://rickandmortyapi.com/graphql`). The purpose of this project is to demonstrate a solid understanding of how to construct GraphQL queries, use arguments to filter data, and structure queries to fetch only the fields that are needed — avoiding over-fetching.

## What Was Done

- Wrote GraphQL queries to fetch a **single character by ID** using the `character(id: ID!)` field.
- Wrote GraphQL queries to fetch a **paginated list of characters** using the `characters(page: Int)` field.
- Wrote GraphQL queries to fetch a **single episode by ID** using the `episode(id: ID!)` field.
- Executed every query against the live Rick and Morty GraphQL endpoint and saved the exact JSON responses as output files.

## Key Concepts Demonstrated

- **Query syntax** — Using the `{ }` block to define what data to request.
- **Arguments** — Passing `id` and `page` arguments to filter or paginate results.
- **Field selection** — Selecting only the required fields (e.g., `id`, `name`, `status`) instead of pulling everything.
- **Single resource vs. collection** — Understanding the difference between querying one item (`character(id: 1)`) and a list (`characters(page: 1)`).

## Project Structure


alx-graphql-0x00/
├── character/
│   ├── README.md
│   ├── character-id-1.graphql
│   ├── character-id-1-output.json
│   ├── character-id-2.graphql
│   ├── character-id-2-output.json
│   ├── character-id-3.graphql
│   ├── character-id-3-output.json
│   ├── character-id-4.graphql
│   ├── character-id-4-output.json
│   ├── characters-page-1.graphql
│   ├── characters-page-1-output.json
│   ├── characters-page-2.graphql
│   ├── characters-page-2-output.json
│   ├── characters-page-3.graphql
│   ├── characters-page-3-output.json
│   ├── characters-page-4.graphql
│   └── characters-page-4-output.json
└── episode/
    ├── README.md
    ├── episode-id-1.graphql
    ├── episode-id-1-output.json
    ├── episode-id-2.graphql
    ├── episode-id-2-output.json
    ├── episode-id-3.graphql
    ├── episode-id-3-output.json
    ├── episode-id-4.graphql
    └── episode-id-4-output.json


## API Endpoint

All queries were executed against:


https://rickandmortyapi.com/graphql


## Author

Silvana Njeru
