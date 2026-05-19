# Schema Drift Gate MCP

Block breaking MCP tool-schema changes before agents call the wrong interface.

Paid remote MCP for schema drift checks, tool-schema approvals, compatibility receipts, breaking-change explanations, and release audit logs.

## Public Endpoints

- Website: https://schemadriftgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://schemadriftgate.clauxel.com/mcp
- Server card: https://schemadriftgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.schemadriftgate/schemadriftgate-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_schema_drift`
- `approve_tool_schema`
- `record_tool_receipt`
- `explain_breaking_change`
- `export_audit_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://schemadriftgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://schemadriftgate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://schemadriftgate.clauxel.com/server-card.json
- MCP endpoint: https://schemadriftgate.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
