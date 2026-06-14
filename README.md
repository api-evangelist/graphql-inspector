# GraphQL Inspector

GraphQL Inspector is schema change detection and validation tooling that checks for breaking changes, deprecated fields, and coverage gaps between GraphQL schema versions, available as CLI, CI, and GitHub Action. Maintained by The Guild as a fully open-source (MIT licensed) project.

**Website:** https://the-guild.dev/graphql/inspector  
**Documentation:** https://the-guild.dev/graphql/inspector/docs  
**GitHub Org:** https://github.com/graphql-hive  
**Blog:** https://the-guild.dev/blog/tag/graphql-inspector  
**GitHub Marketplace:** https://github.com/marketplace/graphql-inspector  

## APIs / Tooling

- **GraphQL Inspector CLI** — `npx @graphql-inspector/cli` — Compare schemas, validate documents, measure coverage, and introspect live GraphQL endpoints from the command line.

## Key Features

- Breaking, dangerous, and non-breaking schema change classification
- Document and fragment validation against a schema
- Schema coverage analysis based on operations and fragments
- Similar and duplicate type detection
- GitHub Action for automated PR schema checks
- GitHub Application with Slack/Discord/webhook notifications
- Programmatic API for embedding in custom tooling
- Docker image support

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider index
- `plans/graphql-inspector-plans.md` — Free/open-source, GitHub Application (free), self-hosted options
- `rate-limits/graphql-inspector-rate-limits.md` — No rate limits on CLI; GitHub Actions limits apply in CI
- `finops/graphql-inspector-finops.md` — Zero direct cost; CI/CD infrastructure costs minimal

## Maintained by

Kin Lane — kin@apievangelist.com
