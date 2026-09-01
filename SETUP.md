# Publica Now plugin setup

The plugin connects to the public Publica Now MCP server at:

`https://publica.now/mcp`

No account, API key, or OAuth flow is required to connect or use its public catalog, creator, pricing, and publishing-option tools.

The optional creator-signup tool asks for a user-provided email address and display name only after the user explicitly requests signup. It sends a private confirmation link to that inbox. Never request that the user paste the link or a verification code into Claude.

If the tools do not appear after installation:

1. Confirm the plugin is enabled.
2. Reload plugins or restart the Claude session.
3. Confirm `https://publica.now/mcp` is reachable.
4. Review the connector permissions and allow the relevant read-only tool or signup action.

Documentation: `https://publica.now/devs`

Support: `support@publica.now`
