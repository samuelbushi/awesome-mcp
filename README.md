# Awesome MCP

A curated, PR-friendly directory maintained by WunderCorp. Entries live as JSON files under `servers/<category>/<slug>/server.json`. The README is generated from those files.

## Contributing

Add one entry per pull request, run the validator, regenerate this README, and keep the entry in the correct category folder.

```bash
node scripts/validate-catalog.mjs
node scripts/generate-readme.mjs
```

## Directory

### Data

| Server | Description | Transport | Links |
|---|---|---|---|
| The Stall | 191 pay-per-call data tools via x402 on Base — stocks, crypto/DeFi, macro, SEC filings, compliance, global news, social momentum. No API keys. | streamable-http | [Homepage](https://the-stall.intuitek.ai)<br>[GitHub](https://github.com/thebrierfox/the-stall) |

## Repository format

- `CONTRIBUTING.md` explains the review policy.
- `.github/pull_request_template.md` keeps submissions consistent.
- `.github/workflows/validate.yml` validates JSON and README generation.
- `schema/` documents the expected metadata shape.

## License

Directory metadata is MIT licensed unless an entry says otherwise. Each listed project keeps its own license.
