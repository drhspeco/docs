# Peeko Docs

This repository powers the public Peeko documentation site at `https://docs.getpeeko.ai`.

The current documentation focuses on the Peeko MCP developer platform:

- Native browser OAuth setup for Cursor and remote MCP clients.
- MCP tool schemas and response examples.
- Credit pricing, billing behavior, rate limits, and errors.
- Internal RAG search vs hybrid live search behavior.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

Check links before publishing:

```
mint broken-links
```

## Publishing changes

The Mintlify GitHub app deploys changes from the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
