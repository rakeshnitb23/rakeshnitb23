# Rakesh Singh

AI backend engineer building agent guardrails: what they may do, what they cost, and whether their answers are grounded.

## Building

- [**toolism**](https://github.com/rakeshnitb23/toolism): toolslim measures and cuts the tokens spent re-sending tool schemas, and tests that the slimmed schema accepts the same calls. Safe rules cut tool-definition tokens 37.4% across 159 tools from 13 MCP servers (73% on Notion).

- [**opfence**](https://github.com/sudheer215s/opfence): checks each request a coding agent makes, then lets it run, asks you, or blocks it. The catalog has 7,057 rules, including 29 MCP servers, each replayed from a recorded request. Early development, not ready to protect a production account. How a request gets its decision: [architecture](https://github.com/sudheer215s/opfence/blob/main/docs/ARCHITECTURE.md).
- [**opfence**](): checks each request a coding agent makes, then lets it run, asks you, or blocks it. The catalog has 7,057 rules, including 29 MCP servers, each replayed from a recorded request. Early development, not ready to protect a production account. How a request gets its decision: [architecture](https://github.com/sudheer215s/opfence/blob/master/docs/ARCHITECTURE.md).


- [**groundeddocs**](https://github.com/rakeshnitb23/groundeddocs): document Q&A that abstains unless every citation matches a chunk retrieved for that question. An answer left with no valid citation is returned as an abstain.

- [**fuel-route-planner**](https://github.com/rakeshnitb23/fuel-route-planner): Django and PostGIS API that picks where to buy fuel on a US road trip. New York to Los Angeles on the [live demo](https://fuel.lazymonk.si): 2,800.6 miles, 17 stops, $846.76.

## Technical Blogs

- [Your AI Agent Just Showed Customer A's Orders to Customer B](https://www.linkedin.com/pulse/your-ai-agent-just-showed-customer-orders-b-rakesh-singh--bhmfc/) · 10 Oct 2026
- [Your AI Agent Just Charged the Customer Twice. Here Is Why.](https://www.linkedin.com/pulse/your-ai-agent-just-charged-customer-twice-here-why-rakesh-singh--sipbc/) · 09 Oct 2026
- [You Probably Have a Context Problem, Not an Agent-Count Problem](https://www.linkedin.com/pulse/you-probably-have-context-problem-agent-count-rakesh-singh--hvhyc/) · 08 Oct 2026
- [Rate Limiting an Agentic System with Redis: Count Tokens, Not Requests](https://www.linkedin.com/pulse/rate-limiting-agentic-system-redis-count-tokens-requests-singh--iuzwc/) · 07 Oct 2026

All posts: [https://www.lazymonk.si](https://www.lazymonk.si)

**Now:** Opfence's catalog and proxy are in progress. It does not guard a production account yet.

[Portfolio](https://www.lazymonk.si/) · [LinkedIn](https://linkedin.com/in/rakesh-singh-58926a116) · [X](https://x.com/rakeshK77998015) · [Email](mailto:rakeshnitb23@gmail.com)
