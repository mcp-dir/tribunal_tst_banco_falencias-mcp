# Instalação detalhada

Tribunal TST: Banco de Falências é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tst_banco_falencias`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tst_banco_falencias` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tst_banco_falencias` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tst_banco_falencias` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tst_banco_falencias` (ou `servers.tribunal_tst_banco_falencias` no VS Code) do config do cliente e reinicie.
