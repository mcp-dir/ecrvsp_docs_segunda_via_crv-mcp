# Instalação detalhada

ECRVSP Documentos: Segunda Via de CRV é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_ecrvsp_docs_segunda_via_crv`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_ecrvsp_docs_segunda_via_crv` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_ecrvsp_docs_segunda_via_crv` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_ecrvsp_docs_segunda_via_crv` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.ecrvsp_docs_segunda_via_crv` (ou `servers.ecrvsp_docs_segunda_via_crv` no VS Code) do config do cliente e reinicie.
