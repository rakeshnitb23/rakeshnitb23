# Rakesh Singh

AI backend engineer building agent guardrails: what they may do, what they cost, and whether their answers are grounded.

## Building

- [**opfence**](https://github.com/rakeshnitb23/opfence): checks each request a coding agent makes, then lets it run, asks you, or blocks it. The catalog has 7,057 rules, including 29 MCP servers, each replayed from a recorded request. Early development, not ready to protect a production account. How a request gets its decision: [architecture](https://github.com/rakeshnitb23/opfence/blob/main/docs/ARCHITECTURE.md).

- [**toolism**](https://github.com/rakeshnitb23/toolism): toolslim measures and cuts the tokens spent re-sending tool schemas, and tests that the slimmed schema accepts the same calls. Safe rules cut tool-definition tokens 37.4% across 159 tools from 13 MCP servers (73% on Notion).

- [**groundeddocs**](https://github.com/rakeshnitb23/groundeddocs): document Q&A that abstains unless every citation matches a chunk retrieved for that question. An answer left with no valid citation is returned as an abstain. [Citations get checked, not trusted](https://portfolio-sage-gamma-15.vercel.app/writing/citations-get-checked-not-trusted).

- [**fuel-route-planner**](https://github.com/rakeshnitb23/fuel-route-planner): Django and PostGIS API that picks where to buy fuel on a US road trip. New York to Los Angeles on the [live demo](https://fuel.lazymonk.si): 2,800.6 miles, 17 stops, $846.76.

## Writing

- [Citations get checked, not trusted](https://portfolio-sage-gamma-15.vercel.app/writing/citations-get-checked-not-trusted) · Feb 2026
- [Abstention is the default path](https://portfolio-sage-gamma-15.vercel.app/writing/abstention-is-the-default-path) · Feb 2026
- [Idempotency at the schema](https://portfolio-sage-gamma-15.vercel.app/writing/idempotency-at-the-schema) · Aug 2025

All posts: [portfolio-sage-gamma-15.vercel.app/writing](https://portfolio-sage-gamma-15.vercel.app/writing)

**Now:** Opfence's catalog and proxy are in progress. It does not guard a production account yet.

[Portfolio](https://portfolio-sage-gamma-15.vercel.app) · [LinkedIn](https://linkedin.com/in/rakesh-singh-58926a116) · [X](https://x.com/rakeshK77998015) · [Email](mailto:rakeshnitb23@gmail.com)
