# Building an MCP Server

A practical, deeply technical walkthrough — from a 30-line skeleton to production-shaped servers. Tools, resources, prompts, sampling, elicitation, errors, progress, cancellation, logging, and conformance testing with the MCP Inspector. Python and TypeScript SDKs side-by-side.

Covers both protocol eras. In revision `2026-07-28` a server no longer sends sampling/elicitation/roots requests; it returns `resultType: "input_required"` and the client retries (new slide 06b, multi round-trip requests). Sampling, Roots and Logging are deprecated. SDK notes cover `mcp` 2.x (`MCPServer`, dual-era; the snippet was run against 2.3.0) and TypeScript SDK v2. Sources: the [2026-07-28 specification](https://modelcontextprotocol.io/specification/2026-07-28/changelog) (accessed 2026-10-08). Animated companion: [Agent Protocols Explained](https://agent-protocols-explained.vercel.app).

**Live site:** https://brendanjameslynskey.github.io/MCP_03_Building_a_Server/

Part of the [Model Context Protocol series](https://github.com/BrendanJamesLynskey/LLMs#model-context-protocol-mcp).
