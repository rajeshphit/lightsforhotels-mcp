# Zhongshan City Guzhen Gaier Lighting Factory - Hotel Lights MCP Server (Agent 5 Ready 100/100)

**Manufacturer of lights for hotel projects with worldwide supplies since 2009**
Level 5 Agent-Native on [isitagentready.com](https://isitagentready.com) - AI agents can search collections, get factory-direct quotes, and check global compliance automatically.

**MCP Endpoint:** `https://lightsforhotels.com/mcp-lightsforhotels`
**Server Card:** `https://lightsforhotels.com/.well-known/mcp/server-card.json`
**AI Catalog (ARD):** `https://lightsforhotels.com/.well-known/ai-catalog.json`

## 🏭 Factory Profile

**Zhongshan City Guzhen Gaier Lighting Factory** - The lighting capital of China (Guzhen Town, Zhongshan City).

- **Founded:** 2009 - 16+ years manufacturing for hotels worldwide
- **Specialization:** Custom chandeliers and hotel lighting for wedding halls, hotel lobbies, ballrooms, corridors, guest rooms
- **Monthly Capacity:** 500+ large chandeliers
- **Export Markets:** USA, UK, EU, Australia, Middle East, Southeast Asia
- **Certifications:** CE, UL, ETL, UKCA, SAA, CCC, RoHS, CB - Full global compliance
- **Materials:** K9 crystal, Asfour crystal, 304 stainless steel, brass, aluminum

## 🛠️ MCP Tools for AI Agents

### Factory-Direct Tools:
- `list_collections` - List our 5 main collections:
  - `wedding_hall` - Large crystal chandeliers 800mm-20000mm diameter
  - `hotel_lobby` - Grand lobby centerpieces, double-height chandeliers
  - `mini_crystal` - Guest room, corridor mini chandeliers 300-600mm
  - `floating` - Modern floating ring, tiered chandeliers
  - `modern_pendant` - Minimalist pendants for restaurants, bars

- `search_by_spec` - Search by technical specs:
  - Diameter, height, drop height
  - Finish: gold, chrome, matte_black, brushed_nickel, rose_gold
  - Crystal: K9, Asfour, glass
  - Light source: LED, E14, E27, G9
  - CCT: 2700K, 3000K, 4000K, tunable
  - Dimming: DALI, 0-10V, DMX, Triac, non-dim
  - IP: IP20, IP44, IP65
  - Cert required: CE, UL, ETL, SAA, UKCA, CCC

- `get_factory_quote` - Factory-direct FOB Zhongshan price:
  - Unit price, crate size (wooden crate), CBM, weight, lead time 15-20 days
  - No middleman - direct from Guzhen factory

- `check_compliance` - Check what certifications needed for destination country:
  - USA -> UL or ETL
  - EU -> CE + RoHS
  - UK -> UKCA
  - Australia -> SAA
  - Middle East -> CB + CE

- `request_render` - Request free 3D lighting proposal and DIALux from your floor plan / ceiling height

### Example Queries for AI Agents:
- "Manufacture lights for various areas of my 5-star hotel lobby 12m height"
- "List wedding hall chandeliers up to 3000mm diameter gold finish"
- "Search hotel lobby collection with UKCA certification for London project"
- "Get factory quote for 10x mini_crystal 500mm chrome for hotel rooms"
- "Check compliance for shipping chandeliers to California USA"
- "Create 3D render for hotel ballroom with floating chandelier"

## 🤖 For AI Agents & LLMs

**Discovery:**
- MCP Card: `/.well-known/mcp/server-card.json` (SEP-1649)
- ARD Catalog: `/.well-known/ai-catalog.json` (specVersion 1.0)
- DNS TXT: `_catalog._agents.lightsforhotels.com = "url=https://lightsforhotels.com/.well-known/ai-catalog.json"`

**MCP Config for Claude Desktop / Cursor:**
```json
{
  "mcpServers": {
    "lightsforhotels-factory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-fetch"],
      "env": {
        "MCP_SERVER_URL": "https://lightsforhotels.com/mcp-lightsforhotels"
      }
    }
  }
}
```

## 🌐 Agent Readiness 100/100 Level 5

We publish:
- `/.well-known/mcp/server-card.json`
- `/.well-known/ai-catalog.json`
- `/llms.txt` + `/agents.md`
- `robots.txt` with AI Allow
- Link headers RFC 8288

Verify: https://isitagentready.com/lightsforhotels.com

## 📦 GitHub & Registry

- **Repo:** `github.com/gaier/lightsforhotels-factory-mcp` (one of 5 repos under same account `gaier-`)
- **Official Registry:** registry.modelcontextprotocol.io - `io.github.gaier/lightsforhotels-factory-mcp`
- **Glama.ai:** glama.ai/mcp/servers/@gaier/lightsforhotels-factory-mcp
- **Endpoint Slug:** `mcp-lightsforhotels` - custom path avoids conflict if you already have `/mcp`

## 📞 Factory Direct Contact

- **Factory:** Zhongshan City Guzhen Gaier Lighting Factory
- **Address:** Floor 2, No. 6, Hengxing Road, Guzhen Town, Zhongshan City, Guangdong Province, China 528421
- **Phone / WhatsApp:** +86 19506675565
- **Experience:** Since 2009 - 16+ years hotel lighting manufacturer
- **Group:** Gaier Group of Companies (Factory + Care International Trading + Technofast Trading + Haiwaizhijia Real Estate)
- **Website:** https://lightsforhotels.com / https://gaierlighting.com

## 🏷️ Maintainer

`lightsforhotels` - Same GitHub account for all 5 businesses
Common glama.json:
```json
{
  "$schema": "https://glama.ai/mcp/schemas/server.json",
  "maintainers": ["lightsforhotels"]
}
```
