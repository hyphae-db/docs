# HyphaeDB documentation

The developer documentation for [HyphaeDB](https://hyphaedb.com), served at
[docs.hyphaedb.com](https://docs.hyphaedb.com) via Mintlify.

**This repo is a read-only mirror.** The source of truth is the `docs-site/`
directory of the core repository, where the docs version alongside the code
they describe: quickstart commands are CI-executed against the server, the
REST reference is generated from the code's OpenAPI document, and the MCP tool
roster is consistency-checked against the protocol spec. Content lands here by
sync from that repo — do not open content PRs against this mirror; they will
be overwritten.

## Local preview

```bash
npm i -g mint
mint dev          # http://localhost:3000
```
