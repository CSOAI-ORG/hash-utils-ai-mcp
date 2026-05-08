<div align="center">

# Hash Utils Ai MCP

**Hash Utils AI MCP Server**

[![PyPI](https://img.shields.io/pypi/v/meok-hash-utils-ai-mcp)](https://pypi.org/project/meok-hash-utils-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-MCP_Server-purple)](https://meok.ai)

</div>

## Overview

Hash Utils AI MCP Server
Hashing, UUID, and ID generation tools powered by MEOK AI Labs.

## Tools

| Tool | Description |
|------|-------------|
| `hash_text` | Hash text using various algorithms. |
| `verify_hash` | Verify if a text matches an expected hash. |
| `generate_uuid` | Generate UUID(s) of various versions. |
| `generate_nanoid` | Generate nanoid-style short unique identifiers. |

## Installation

```bash
pip install meok-hash-utils-ai-mcp
```

## Usage with Claude Desktop

Add to your Claude Desktop MCP config (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "hash-utils-ai": {
      "command": "python",
      "args": ["-m", "meok_hash_utils_ai_mcp.server"]
    }
  }
}
```

## Usage with FastMCP

```python
from mcp.server.fastmcp import FastMCP

# This server exposes 4 tool(s) via MCP
# See server.py for full implementation
```

## License

MIT © [MEOK AI Labs](https://meok.ai)
