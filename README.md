# automation-tools

Focused automation utilities for repetitive engineering workflows and operational tasks.

## Purpose

This repo exists to keep common workflow automation small, scriptable, and reusable across the ecosystem.

## Role in the ecosystem

- Neighbor to `devops-toolkit`
- Supports `internal-developer-platform`
- Used by `master-platform` and `saas-platform`

## Status

Starter Go CLI with one useful batch-style command.

## Tech stack

- Go

## Structure

```text
automation-tools/
├── cmd/
│   └── autom8/
│       └── main.go
├── docs/
│   └── usage.md
├── .editorconfig
├── .gitignore
├── README.md
├── ROADMAP.md
└── go.mod
```

## Getting started

```bash
go run ./cmd/autom8 run
```

## Related repositories

- `devops-toolkit`
- `internal-developer-platform`
- `master-platform`

## Future direction

Stay focused on glue automation rather than recreating a full CI system here.
