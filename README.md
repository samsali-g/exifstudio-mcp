# ExifStudio MCP Server

[![mcptry](https://mcptry.com/badge/io.github.samsali-g/exifstudio)](https://mcptry.com/servers/io.github.samsali-g/exifstudio)
[![ExifStudio MCP connector](https://glama.ai/mcp/connectors/online.exifstudio/exif-studio/badges/score.svg)](https://glama.ai/mcp/connectors/online.exifstudio/exif-studio)

Remote Streamable HTTP MCP server for **[ExifStudio](https://www.exifstudio.online)** — a 100% client-side, zero-upload photo and PDF metadata privacy suite.

## Remote Endpoint

Connect any MCP client that supports Streamable HTTP directly to:

```
https://www.exifstudio.online/mcp
```

No API key, no account, and no file uploads required.

## Available Tools (Read-Only)

- `list_tools` — List all ExifStudio client-side metadata & imaging tools with canonical URLs.
- `get_tool` — Look up a specific tool (`metadata-editor`, `inspector`, `shutter-count`, `geotag-photos`, `pdf-metadata`, `dpi-converter`, `heic-to-jpg`).
- `get_skill` — Retrieve the ExifStudio AI agent skill guide (`SKILL.md`).

## Discovery

- Server Card: `https://www.exifstudio.online/.well-known/mcp/server-card.json`
- API Catalog: `https://www.exifstudio.online/.well-known/api-catalog`
- OpenAPI 3.1: `https://www.exifstudio.online/api/openapi.json`
- LLMs Guide: `https://www.exifstudio.online/llms-full.txt`
