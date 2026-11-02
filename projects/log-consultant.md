# LogConsultant

**Windows servicing diagnostics | C# | .NET | PowerShell | MCP**

## Problem

Windows servicing logs can contain multiple attempts, failures, retries, and
later outcomes. A useful investigation needs to preserve context rather than
treat every error-looking line as the current problem.

## Project overview

LogConsultant explores evidence-oriented servicing-log investigation and
AI-assisted troubleshooting.

At a capability level, the work includes:

- Organizing servicing evidence for a bounded diagnostic investigation.
- Helping engineers distinguish historical attempts from current outcomes.
- Exposing diagnostic capabilities through an MCP-based experience.
- Exploring an approval-aware handoff from investigation to a separate lab-side
  integration prototype.
- Keeping machine-changing actions distinct from evidence gathering.

## Engineering themes

The project connects Windows diagnostics, structured evidence presentation,
integration boundaries, and explicit human approval.

An explanation produced by an AI client is not itself remediation approval or
proof that a servicing problem was resolved.

## Confidentiality boundary

Core analysis rules, correlation logic, source code, internal contracts,
implementation diagrams, handoff/signing details, endpoint identifiers,
customer logs, and executable packages remain private.

This page does not disclose or publish Microsoft's internal Get Help application.

## Status and claims

Diagnostic tooling with a separate lab integration prototype. It is not presented
as a supported replacement for Windows servicing components or production Get
Help integration.

## Resume wording

> Built C#/.NET servicing-diagnostics tooling with MCP integration, structured
> evidence presentation, and a lab prototype that separates investigation from
> explicitly approved follow-on actions.
