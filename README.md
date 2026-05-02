<!-- studiomeyer-mcp-stack-banner:start -->
> **Part of the [StudioMeyer MCP Stack](https://studiomeyer.io)** — Built in Mallorca 🌴 · ⭐ if you use it
<!-- studiomeyer-mcp-stack-banner:end -->

# StudioMeyer Crew

> Agent Personas for Claude — 10 MCP tools, 8 personas, 3 workflows. Zero API cost. Free tier available.

[![MCP Registry](https://img.shields.io/badge/MCP-Registry-blue)](https://registry.modelcontextprotocol.io/servers/io.studiomeyer/crew)
[![MCPize](https://img.shields.io/badge/MCPize-Marketplace-purple)](https://mcpize.com/mcp/studiomeyer-crew)
[![Glama](https://glama.ai/mcp/servers/studiomeyer-io/studiomeyer-crew/badges/score.svg)](https://glama.ai/mcp/servers/studiomeyer-io/studiomeyer-crew)
[![Free](https://img.shields.io/badge/Price-Free-brightgreen)](https://studiomeyer.io/en/services/crew/)

## What is this?

StudioMeyer Crew turns Claude into specialized expert roles — CEO, CFO, CMO, CTO, PM, Analyst, Support, Creative Director — with domain-specific frameworks, decision models, and chained workflows. **Zero extra API cost** because it runs within your Claude subscription.

**10 MCP tools** for persona activation, status, feedback, custom personas, and multi-persona workflows.

## Connect in 10 Seconds

### Claude Desktop / Cowork
Settings → Connectors → Add URL:
```
https://crew.studiomeyer.io/mcp
```

### Claude Code
```bash
claude mcp add --transport http crew https://crew.studiomeyer.io/mcp
```

### Cursor / VS Code / Windsurf / Zed
```bash
npx mcp-remote https://crew.studiomeyer.io/mcp
```

### MCPize
```bash
npx mcp-remote https://studiomeyer-crew.mcpize.run
```

You will receive a sign-in link via email to verify your identity — no passwords needed. All 10 tools are immediately available.

## 8 Built-in Personas

| Persona | Category | Frameworks | Use When... |
|---------|----------|------------|-------------|
| **CEO** | Business | OKR, Eisenhower Matrix, 3-Question Decision Check | Strategy, prioritization, delegation |
| **CFO** | Business | 11 SaaS Metrics (CAC, LTV, MRR, NRR, Rule of 40), Unit Economics | Financial analysis, pricing, ROI |
| **CMO** | Business | AARRR Pirate Metrics, Content Distribution Matrix, SEO/GEO | Marketing, content, growth |
| **PM** | Business | RICE/ICE Scoring, Jobs-to-be-Done, PRD Template | Product decisions, feature prioritization |
| **CTO** | Tech | ADR Template, DORA Metrics, Tech Debt Quadrant | Architecture, code review, tech decisions |
| **Analyst** | Ops | SWOT, PESTLE, Porter's Five Forces | Research, competitive intelligence |
| **Support** | Ops | Escalation Decision Tree, 5 Response Templates | Customer communication |
| **Creative** | Creative | Brand Voice Spectrum, 10 Headline Formulas | Design direction, copywriting, brand |

Every persona ships with: domain frameworks, few-shot examples, anti-patterns, chain-of-thought thinking process, and cross-persona handoffs.

## 10 Tools

| Tool | Description |
|------|-------------|
| `crew_guide` | Help and onboarding (5 topics) |
| `crew_list` | List personas by category |
| `crew_activate` | Activate a persona with optional business context |
| `crew_deactivate` | Return to default Claude |
| `crew_status` | Show active persona + duration |
| `crew_feedback` | Rate persona performance (1–5) |
| `crew_create` | Create custom persona |
| `crew_delete` | Delete custom persona (built-in protected) |
| `crew_workflow_list` | List multi-persona workflows |
| `crew_workflow_run` | Run a workflow (sequential persona chain) |

## 3 Workflows

Workflows chain multiple personas for complex tasks:

- **Strategy Review** — CEO analyzes → CFO evaluates financials → CTO checks feasibility
- **Content Pipeline** — CMO drafts → Analyst fact-checks → Creative polishes
- **Product Launch** — PM scopes → Creative writes copy → CMO plans distribution

## Pricing

- **Free** — All 10 tools, all 8 personas, all 3 workflows. No credit card.
- **Pro / Team / Scale** — coming soon (custom personas at scale, team SSO, audit logs)

See [studiomeyer.io/en/services/crew](https://studiomeyer.io/en/services/crew/) for plan details.

## Why this approach?

Multi-agent fleets are expensive. Every agent needs its own LLM API call.

Crew runs as **one MCP server** that swaps Claude's persona on demand. The reasoning still happens in your normal Claude subscription — no extra inference costs, no agent orchestration layer, no token accounting per persona.

You get the focused-expert effect (CFO answers financial questions like a CFO, not a generalist) without the bills.

## Hosting

- EU-hosted (Frankfurt, Germany)
- Magic-link email login — no passwords stored
- Memory-bridge optional: connect [StudioMeyer Memory](https://github.com/studiomeyer-io/studiomeyer-memory) so personas auto-load your business context across sessions

## Links

- **Website:** https://studiomeyer.io/en/services/crew/
- **MCP Endpoint:** https://crew.studiomeyer.io/mcp
- **MCPize:** https://studiomeyer-crew.mcpize.run
- **Status:** https://crew.studiomeyer.io/health

## Support

- **Issues:** https://github.com/studiomeyer-io/studiomeyer-crew/issues
- **Email:** hello@studiomeyer.io
- **Security:** see [SECURITY.md](SECURITY.md)

## About StudioMeyer

[StudioMeyer](https://studiomeyer.io) is an AI and design studio based in Palma de Mallorca, working with clients worldwide. We build custom websites and AI infrastructure for small and medium businesses. Production stack on Claude Agent SDK, MCP and n8n, with Sentry, Langfuse and LangGraph for observability and an in-house guard layer.

## License

MIT — see [LICENSE](LICENSE).

This repository contains the public connector documentation only. The server source code is proprietary and not published.