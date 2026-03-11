# automata

Focused automation utilities for repetitive engineering workflows and operational tasks.

## Purpose

This repo exists to keep common workflow automation small, scriptable, and reusable across the ecosystem.

## Role in the ecosystem

- Neighbor to `anvil`
- Supports `relay`
- Used by `orbit` and `summit`

## Status

Starter Go CLI with one useful batch-style command.

## Tech stack

- Go

## Structure

```text
automata/
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

- `anvil`
- `relay`
- `orbit`

## Future direction

Stay focused on glue automation rather than recreating a full CI system here.
