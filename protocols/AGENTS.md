# protocols/

On-chain protocol indexing: Substreams modules that extract state from the chain, and the
tooling to test and validate those integrations. Each sub-directory has its own toolchain
and workspace — see the relevant `AGENTS.md` for details.

| Directory | Description |
|---|---|
| [`substreams/`](substreams/AGENTS.md) | WASM modules extracting on-chain state → protobuf for `tycho-indexer` |
| [`testing/`](testing/AGENTS.md) | End-to-end integration test runner for Substreams implementations |
| [`adapter-integration/`](adapter-integration/AGENTS.md) | Foundry fork tests for `tycho-execution` VM adapter contracts |
