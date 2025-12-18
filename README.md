# Playgent Documentation

Documentation for the Playgent agent experimentation and prompt management platform.

## Overview

Playgent provides:

- **Instrumented Tracing** - Capture agent execution at the span level
- **Advanced Evaluation** - RAGAS metrics, hallucination detection, custom scorers
- **Prompt Optimization** - Automated prompt improvement using feedback from failed tests
- **A/B Testing** - Statistical analysis of different agent configurations

## Documentation Structure

```
docs/
├── index.mdx              # Introduction
├── quickstart.mdx         # Getting started guide
└── api-reference/         # Full API documentation
    ├── agents/            # Agent management
    ├── test-cases/        # Test case creation
    ├── runs/              # Test execution
    ├── tracing/           # Span-level tracing
    ├── evaluation/        # Evaluation metrics
    ├── optimization/      # Prompt optimization & A/B tests
    ├── webhooks/          # Event webhooks
    └── analytics/         # Performance analytics
```

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run local preview:

```bash
mint dev
```

View at `http://localhost:3000`.

## Publishing

Changes pushed to the default branch are automatically deployed via Mintlify GitHub app.
