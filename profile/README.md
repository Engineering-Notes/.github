<!-- This file is the public profile of the Engineering Notes organisation on GitHub. -->

# Engineering Notes

**Systems engineering, measured.**

Engineering Notes is a body of technical writing where every claim comes with code you can run. Each article takes one problem that real systems get wrong, such as double charges, lost webhooks, stale reads or runaway retries, reproduces it, measures it, and shows the fix that holds under test.

The articles are published on [codemwangi.substack.com](https://codemwangi.substack.com). The code behind every number lives here.

## Series

| Series | Repository | Status | Topics |
|---|---|---|---|
| **Payment Systems** | [`payment-systems`](https://github.com/Engineering-Notes/payment-systems) | 18 articles, November 2026 to January 2027 | Double-entry ledgers, idempotency, outbox, webhooks, reconciliation, isolation levels, locking, rate limiting, M-Pesa, stablecoins, proof of reserves |
| **Distributed Systems** | [`distributed-systems`](https://github.com/Engineering-Notes/distributed-systems) | From 19 January 2027 | Clocks, Raft, quorums, CRDTs, consistent hashing, failure detection, queues, backpressure, caching, sagas, linearizability |
| **AI Engineering** | [`ai-engineering`](https://github.com/Engineering-Notes/ai-engineering) | From February 2027 | Evaluations, retrieval, agents and guardrails, structured outputs, cost and latency budgets, observability |

## How the work is done

- **Every number is reproducible.** Each article has a folder with its own tests, and CI runs every folder on every change.
- **Failures are injected on purpose.** Crashes, timeouts, duplicates, reordering and attackers are part of every test.
- **Sources are primary.** Specifications, RFCs, official documentation and the original papers.
- **Corrections are public.** If an article is wrong, the fix is made in the code and noted in the article.

## Get involved

- Read and subscribe at [codemwangi.substack.com](https://codemwangi.substack.com).
- Found a wrong result or an error in an article? Open an issue in the series repository using the forms provided.
- Want to discuss an idea or propose a topic? Start a thread in [Discussions](https://github.com/orgs/Engineering-Notes/discussions).
- Read the [contributing guide](https://github.com/Engineering-Notes/.github/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/Engineering-Notes/.github/blob/main/CODE_OF_CONDUCT.md) before contributing.

## Maintainer

Founded and maintained by [Joseph Mwangi](https://github.com/JosephNjorog) ([@code_mwangi](https://x.com/code_mwangi)), a backend and blockchain engineer based in Kenya.

All code is released under the MIT License unless a repository states otherwise.
