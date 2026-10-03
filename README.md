# mt5-trading-intelligence-mcp
Production-grade read-only Trading Intelligence MCP for MetaTrader 5 and Claude.
Status
🚧 Early development — V4.1 architecture.
Principles
READ_ONLY by design
No trade execution in V1
Demo account first
Security and data integrity are priorities
Phone-first development workflow
Multi-market support
Architecture
Android → Claude Code → MCP → MT5 Bridge → MetaTrader 5
The real MT5 terminal and Python bridge will run on a remote Windows VPS.
Development
The project will be developed progressively according to the V4.1 specification.
No production trading should be enabled without explicit validation.
