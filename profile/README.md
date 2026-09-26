# Governed Db2 MCP Server

A security-focused Java 21 MCP server that enables AI assistants to explore IBM Db2 metadata and execute bounded, read-only diagnostic queries.

## Purpose

Governed Db2 MCP Server provides typed MCP tools for controlled access to Db2 metadata, stored procedures, reference data, and diagnostic SQL queries.

The project treats the connected AI assistant as untrusted and applies defensive controls such as:

- read-only database access
- structural SQL validation
- least-privilege configuration
- bounded query execution
- resource limits
- sanitized logging and auditability
- explicit, typed MCP tool contracts

## Project status

The project is currently being prepared for republication. The main source repository will be linked here when the revised public distribution is ready.

## Maintainer

Created and maintained by **Marek Pompura**.

Contact: [marek.pompura.it@gmail.com](mailto:marek.pompura.it@gmail.com)

## Disclaimer

Db2 is a trademark of IBM. This is an independent project and is not affiliated with, sponsored by, or endorsed by IBM.
