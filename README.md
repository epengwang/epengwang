# Building PDFLean

I build **[PDFLean](https://pdflean.com)** — a PDF toolkit for people and for AI agents.

## PDFLean MCP Server

A hosted remote MCP server with 17 PDF tools for AI agents: PDF/A validation, accessibility checking, signature verification, text and form extraction, PII scanning, AI summarize/translate, merge, split, compress, Office conversion, OCR, digital signing, redaction and saved workflows.

- Endpoint: `https://mcp.pdflean.com/mcp` (Streamable HTTP, OAuth 2.1)
- Repo: [pdflean-mcp](https://github.com/epengwang/pdflean-mcp)
- Official MCP Registry: `com.pdflean/mcp`

## PDFLean Skills

Agent skills that wrap the PDFLean public API — a general PDF toolkit skill and a contract review pipeline (extract → PII scan → redact, with evidence reports).

- Repo: [pdflean-skills](https://github.com/epengwang/pdflean-skills)

## Links

- Website: https://pdflean.com
- API docs: https://pdflean.com/workflows/api
