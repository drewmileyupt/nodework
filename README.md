# nodework

Learning TypeScript by building tiny CLIs

Built for my own use; public in case it helps someone.

## What it does

- Ships as an ESM binary
- npm link friendly
- Strict tsconfig, no any
- commander-based subcommands

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```
