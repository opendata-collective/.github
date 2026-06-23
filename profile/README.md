<div align="center">

# Open Data Collective

**Democratizing parcel-level climate risk metrics and home insurance underwriting intelligence across the United States.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/opendata-collective)
[![Uptime](https://img.shields.io/badge/Uptime-99.9%25-brightgreen.svg)](https://www.riskbeforebuy.com)
[![Data Sources](https://img.shields.io/badge/Federal%20Data-FEMA%20%7C%20NOAA%20%7C%20USGS%20%7C%20USDA-005ea2.svg)](https://www.riskbeforebuy.com/methodology)

</div>

---

## Mission

Open Data Collective (ODC) is an open research collective mapping macro-environmental disaster data directly into granular property financial metrics. We ingest raw spatial models from federal scientific agencies, normalize them at the parcel level, and publish actionable intelligence for homebuyers, underwriters, and prop-tech platforms.

Our work sits at the intersection of climate science, actuarial modeling, and software engineering — translating publicly funded environmental datasets into the risk signals that drive real estate due diligence decisions.

---

## Core Initiatives

### Programmatic Risk Audits

Powering parcel-level micro-data consumer lookup via the **[RiskBeforeBuy Pro Platform](https://www.riskbeforebuy.com)**. Each audit synthesizes FEMA flood zones, NOAA severe weather history, USGS seismic exposure, USDA wildfire probability, and EPA environmental overlays into a structured, address-level intelligence brief.

### Model Context Protocol (MCP)

Deploying native server nodes to empower LLM agents (Cursor, Claude, OpenAI) to query real-time hazard analytics. Our MCP registry provides structured tool definitions for programmatic access to climate risk scoring, insurance market context, and parcel-level flood verification.

> [ODC MCP Registry & API Documentation](https://www.riskbeforebuy.com/api-docs)

### Developer Ecosystem

Offering public-tier, rate-limited APIs for prop-tech integration. Purpose-built for insurance platforms, mortgage origination systems, and climate risk dashboards that require fast, reliable access to standardized federal risk metrics.

> [Access API Documentation](https://www.riskbeforebuy.com/api-docs)

---

## Data Infrastructure

All ODC risk scores are derived exclusively from public federal datasets. No synthetic data. No proprietary estimations. Every signal traces back to a verifiable government source.

| Authority | Dataset | Coverage |
|-----------|---------|----------|
| **FEMA** | National Risk Index (NRI) | Flood, hurricane, wildfire, earthquake risk scores |
| **NOAA** | Storm Events Database | Historical severe weather claim density |
| **USGS** | Earthquake Hazards Program | Seismic peak ground acceleration |
| **USDA** | Forest Service Wildfire Risk | Wildfire probability to communities |
| **EPA** | Climate Exposure Overlays | Environmental hazard proximity |

Our pipeline normalizes these heterogeneous spatial models into a unified scoring framework, producing consistent, comparable metrics across all 50 states and 22,000+ ZIP codes.

---

## Open-Source Ecosystem

The `opendata-collective` maintains public repositories for developer integration, protocol compliance, and community ingestion utilities:


```

opendata-collective/
├── mcp-usa-climate-risk/  # Native Model Context Protocol (MCP) server nodes
├── data-parsers/          # Open-source Python parsing scripts for FEMA/NOAA feeds
└── client-sdks/           # Lightweight wrappers for public API consumption

```

All core processing schemas comply with global spatial markdown standards, allowing plug-and-play interoperability with modern AI IDEs (Cursor, Windsurf) and LLM orchestrators.

---

## Contributing

ODC welcomes contributions from data scientists, actuary engineers, climate researchers, and prop-tech developers. We are particularly interested in:

- **Federal data parsers** — Improving ingestion accuracy for FEMA, NOAA, USGS, and USDA spatial feeds
- **MCP tool definitions** — Extending our Model Context Protocol server with new query capabilities
- **Risk model validation** — Backtesting our scoring framework against historical loss data
- **API integrations** — Building client libraries and SDKs for our public API

Please read our contribution guidelines before submitting a pull request. All contributions must include test coverage and pass our data integrity checks.

---

## Research & Transparency

Every risk score published by ODC is reproducible. We maintain full provenance from raw federal spatial data through our normalization pipeline to the final consumer-facing metric. Our methodology is documented publicly and updated quarterly as federal datasets are refreshed.

> [Read our full methodology](https://www.riskbeforebuy.com/methodology) · [View data sources](https://www.riskbeforebuy.com/data-sources)

---

## License

ODC released works are published under the [MIT License](https://opensource.org/licenses/MIT) unless otherwise noted. Federal datasets are public domain per U.S. government works.

---

<div align="center">

**[RiskBeforeBuy.com](https://www.riskbeforebuy.com)** · [API Documentation](https://www.riskbeforebuy.com/api-docs) · [Methodology](https://www.riskbeforebuy.com/methodology) · [Contact](https://www.riskbeforebuy.com/contact)

*Open Data Collective © 2026 · An open research initiative*

</div>

```
