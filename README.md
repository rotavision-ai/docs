# Rotavision Documentation

Official documentation for Rotavision AI Trust Infrastructure, built with [Mintlify](https://mintlify.com).

## Local Development

Install Mintlify CLI:

```bash
npm i -g mintlify
```

Run the development server:

```bash
mintlify dev
```

The docs will be available at `http://localhost:3000`.

## Structure

```
├── mint.json              # Mintlify configuration
├── introduction.mdx       # Getting started
├── quickstart.mdx         # Quick start guide
├── authentication.mdx     # API authentication
├── errors.mdx            # Error handling
├── concepts/             # Core concepts
├── api-reference/        # API documentation
│   ├── vishwas/         # Fairness & Explainability
│   ├── guardian/        # Monitoring
│   ├── dastavez/        # Document AI
│   ├── sankalp/         # LLM Gateway
│   ├── orchestrate/     # Multi-Agent Workflows
│   └── gati/            # Fleet Intelligence
├── sdks/                 # SDK documentation
├── guides/               # How-to guides
└── integrations/         # Integration guides
```

## Deployment

Push to main branch to trigger automatic deployment via Mintlify.

## License

Apache 2.0
