# Hash Utils Ai

> By [MEOK AI Labs](https://meok.ai) — MEOK AI Labs MCP Server

Hash Utils AI MCP Server

## Installation

```bash
pip install hash-utils-ai-mcp
```

## Usage

```bash
# Run standalone
python server.py

# Or via MCP
mcp install hash-utils-ai-mcp
```

## Tools

### `hash_text`
Hash text using various algorithms.

**Parameters:**
- `text` (str)
- `algorithm` (str)
- `encoding` (str)

### `verify_hash`
Verify if a text matches an expected hash.

**Parameters:**
- `text` (str)
- `expected_hash` (str)
- `algorithm` (str)

### `generate_uuid`
Generate UUID(s) of various versions.

**Parameters:**
- `version` (int)
- `count` (int)
- `namespace` (str)
- `name` (str)

### `generate_nanoid`
Generate nanoid-style short unique identifiers.

**Parameters:**
- `size` (int)
- `alphabet` (str)
- `count` (int)


## Authentication

Free tier: 15 calls/day. Upgrade at [meok.ai/pricing](https://meok.ai/pricing) for unlimited access.

## Links

- **Website**: [meok.ai](https://meok.ai)
- **GitHub**: [CSOAI-ORG/hash-utils-ai-mcp](https://github.com/CSOAI-ORG/hash-utils-ai-mcp)
- **PyPI**: [pypi.org/project/hash-utils-ai-mcp](https://pypi.org/project/hash-utils-ai-mcp/)

## License

MIT — MEOK AI Labs
