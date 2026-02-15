---
url: https://entgo.io/docs/getting-started/
type: article
tags: [go, ent, orm, database, tutorial]
date_saved: 2026-02-15
---
# Quick Introduction | ent
## Summary
A practical getting-started guide for Ent (entity framework for Go) that walks through schema creation, code generation, migrations, CRUD operations, and relationship modeling.

## Key Points
- Ent models schema as Go code and generates strongly typed APIs for data access.
- The tutorial shows a full first workflow: define schema, run `go generate`, open a client, and run migrations.
- Query patterns use generated predicates and fluent builders (`Create`, `Query`, `Where`, `Only`, etc.).
- Relationships are modeled through edges (for example, one-to-many between users and cars).

## Related
- [[database-transactions-in-go]]
- [[good-api-design]]
