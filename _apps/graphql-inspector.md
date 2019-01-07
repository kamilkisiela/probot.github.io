---
title: GraphQL Inspector
description: Tooling for GraphQL. Compare schemas, validate documents, find breaking changes, find similar types, schema coverage
slug: graphql-inspector
screenshots:
- https://graphql-inspector.netlify.com/img/cli/github.jpg
- https://graphql-inspector.netlify.com/img/cli/diff.jpg
authors: [ kamilkisiela ]
repository: kamilkisiela/graphql-inspector
host: https://graphql-inspector.netlify.com/
---

GraphQL Inspector ouputs a list of changes between two GraphQL schemas. Every change is precisely explained and marked as breaking, non-breaking or dangerous. It helps you validate documents and fragments against a schema and even find similar or duplicated types.

![Example](https://graphql-inspector.netlify.com//img/cli/demo.gif)

> GraphQL Inspector has a **CLI** and also a **programatic API**, so you can use it however you want to and even build tools on top of it.

### Github App

Have a per-repository, self-hosted GraphQL Inspector service or deploy it with Docker.

![Github](https://graphql-inspector.netlify.com/img/cli/github.jpg)

### Compare GraphQL Schemas

Detects every change (both neutral, dangerous or breaking).

![Diff](https://graphql-inspector.netlify.com/img/cli/diff.jpg)

### Validate documents agains a schema

Validates documents against a schema and looks for deprecated usage.

![Validate](https://graphql-inspector.netlify.com/img/cli/validate.jpg)

### Find duplicated types

Finds similar / duplicated types.

![Similar](https://graphql-inspector.netlify.com/img/cli/similar.jpg)

### Schema coverage

Schema coverage based on documents. Find out how many times types and fields are used in your application.

![Coverage](https://graphql-inspector.netlify.com/img/cli/coverage.jpg)

### Serve faked GraphQL API

Serves a GraphQL server with faked data and GraphQL Playground

```bash
✅ Serving the GraphQL API on http://localhost:4000/
```

### Introspect GraphQL server

Introspects a GraphQL Server and writes the result to a file

```bash
✅ Introspection result saved to schema.json
```
