# Japan Camera & Lens Resale Price Research API MCP Server

MCP server wrapping the Japan Camera & Lens Resale Price Research API (RapidAPI FREEMIUM).

## Tools

- `get_api_info()` — metadata and RapidAPI URL
- `query_api(params)` — proxy call to RapidAPI endpoint (requires RAPIDAPI_KEY)

## Links

- **RapidAPI**: https://rapidapi.com/atsushi-noriduki/api/japan-camera-lens-resale-price-research-api
- **Apify Store**: https://apify.com/fruitful_quintessence
- **GitHub**: https://github.com/atushi1841/japan-camera-mcp
- **Smithery**: https://smithery.ai/server/atushi1841/japan-camera-mcp

## Install (Smithery)

```bash
smithery install @atushi1841/japan-camera-mcp
```

## Run locally

```bash
pip install fastmcp
python server.py          # stdio MCP transport
python server.py --http   # streamable-http at /mcp
```

## Environment

- `RAPIDAPI_KEY` (optional): free key from https://rapidapi.com/atsushi-noriduki/api/japan-camera-lens-resale-price-research-api
