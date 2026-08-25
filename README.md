# MDX documentation examples

A public Mintlify documentation workspace with MDX guides, component examples, and an OpenAPI reference.

## Status

Prototype. Default branch: `main`. Visibility: public. The current pages document Mintlify authoring and preview workflows. They are not Adminifi product documentation.

## Use it

Install Node.js 19 or newer, then install the Mintlify CLI:

```bash
npm i -g mint
```

From the repository root, preview the site:

```bash
mint dev
```

Open `http://localhost:3000`. Check internal links with:

```bash
mint broken-links
```

## Layout

| Path | Purpose |
|---|---|
| `docs.json` | Mintlify site configuration and navigation |
| `index.mdx` | Landing page |
| `quickstart.mdx` | Quickstart guide |
| `essentials/` | MDX, navigation, settings, code, images, and snippets |
| `api-reference/` | API introduction and `openapi.json` |
| `ai-tools/` | Claude Code, Cursor, and Windsurf guides |
| `development.mdx` | Local preview and validation workflow |
| `images/`, `logo/`, `favicon.svg` | Site assets |

## Gate

`mint broken-links` is the repository's documented quality check. No package-level test command is defined.

## Links

- [Contributor guide](CONTRIBUTING.md)
- [Project instructions](AGENTS.md)
