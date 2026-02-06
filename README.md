# Vulcn Documentation

This is the official documentation for [Vulcn](https://github.com/vulcnize/vulcn), a security testing tool that records browser interactions and replays them with security payloads.

## Development

### Prerequisites

- Node.js v18-24 (Mintlify CLI doesn't support Node 25+)
- npm

### Install Mintlify CLI

```bash
npm i -g mint
```

### Run locally

```bash
mint dev
```

Open [http://localhost:3000](http://localhost:3000) to view the docs.

### Build

The docs are automatically deployed via Mintlify when changes are pushed to the main branch.

## Structure

```
docs/
├── index.mdx              # Introduction
├── quickstart.mdx         # Getting started guide
├── installation.mdx       # Installation guide
├── cli/                   # CLI command reference
│   ├── overview.mdx
│   ├── record.mdx
│   ├── run.mdx
│   ├── payloads.mdx
│   ├── plugin.mdx
│   └── init.mdx
├── config/                # Configuration reference
│   ├── overview.mdx
│   ├── plugins.mdx
│   └── settings.mdx
├── plugins/               # Plugin documentation
│   ├── overview.mdx
│   ├── hooks.mdx
│   ├── plugin-payloads.mdx
│   ├── plugin-detect-xss.mdx
│   ├── plugin-detect-reflection.mdx
│   ├── creating-plugins.mdx
│   └── plugin-api.mdx
├── api/                   # Programmatic API
│   ├── overview.mdx
│   ├── recorder.mdx
│   ├── runner.mdx
│   ├── plugin-manager.mdx
│   └── types.mdx
└── docs.json              # Mintlify config
```

## License

AGPL-3.0
