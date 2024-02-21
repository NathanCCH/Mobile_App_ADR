
# Data Storage

## Status
Proposed

## Context
The mobile app needs to store user profiles, ride history, and payment information. The database we choose will impact these features.

## Decision
We propose to use a SQL database like PostgreSQL for data storage. SQL databases provide strong data integrity guarantees and support complex queries, which are important for our use case.

## Consequences
Choosing a SQL database will ensure data integrity and support complex queries. However, we'll need to carefully design the schema and indexes to ensure good performance.