# sortie-kit

Small Go tool: declutter ~/Downloads in one command

Started as a weekend hack, grew on me.

## Highlights

- Dry-run prints the plan before moving anything
- Skips hidden files and folders by default
- Single static binary, no runtime deps
- Groups files into folders by extension

## Usage

```bash
./bin/sortie-kit ~/Downloads --dry-run
./bin/sortie-kit ~/Downloads
```

## Getting started

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```
