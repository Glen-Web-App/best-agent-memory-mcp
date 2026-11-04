# Contributing to Best Agent Memory MCP

Pull requests that add a server, fix a fact or flag a dead project are welcome. One server per pull request.

## Inclusion rules

An entry must:

1. **Be maintained.** At least one commit or release in the last 6 months. Archived, winding-down or stale projects go to "Deprecated or not recommended", not the ranking.
2. **Ship an MCP server for memory.** The server's job is storing and recalling what an agent learns. Generic database tools, code indexes and servers where memory is a side feature do not qualify.
3. **Have a source for every fact.** Link the README, docs page, pricing page or release for each claim: storage, transport, auth, pricing, license, benchmarks. A fact without a link will be removed.

## How to write an entry

- Lead with the one fact that sets the server apart, not its name.
- Mark every benchmark score **(self-reported)** unless an independent party ran it, and link the run.
- Say where stars cover a whole monorepo rather than the server.
- List real weaknesses. An entry with no weaknesses will not be merged.
- No marketing language and no em dashes.

## Ranking changes

Rank moves follow the criteria in the README's "How we ranked" section. Explain in the pull request which criterion changed (for example, a new release, a new capture hook, a license change). First place is the maintainer's pick and is disclosed as such in the README.

## Corrections from maintainers

If you maintain a listed project and something is wrong or out of date, open an issue or pull request with a link to the current source.
