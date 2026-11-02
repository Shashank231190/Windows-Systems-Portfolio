# PerformanceAnalyzer

**Windows storage diagnostics | C# | PowerShell | .NET | ETW / PerfMon | MCP**

## Problem

Storage-performance investigations involve several measurement layers. Engineers
need to view related evidence together without confusing one layer's timings with
another's or turning correlation into an unsupported root-cause claim.

## Project overview

PerformanceAnalyzer is an engineering tool for Windows storage-performance
capture, visualization, and guided investigation.

At a capability level, the work includes:

- Bringing performance-counter and storage-tracing evidence into an interactive
  investigation experience.
- Supporting storage and minifilter-oriented analysis workflows.
- Improving dashboard usability through graph organization and saved layouts.
- Providing MCP-based integration for assisted exploration of diagnostic evidence.
- Separating capture/distribution concerns from the analysis experience.

## Engineering themes

The project brings together Windows performance troubleshooting, desktop tooling,
data presentation, and AI-assisted engineering workflows.

The important distinction is between **what was observed** and **what can be
concluded**. Different telemetry sources cover different boundaries; an attractive
graph or an AI explanation is not proof of causation.

## Confidentiality boundary

This page describes the problem, user-facing capabilities, and technology stack
only. Source code, parsing and correlation logic, internal data models, scoring or
aggregation algorithms, API/tool contracts, implementation diagrams, customer
captures, and release payloads are intentionally not published.

## Status and claims

An engineering diagnostic tool with private development variants. This showcase
does not assert a measured investigation-time reduction, customer adoption,
benchmark advantage, or a correctness guarantee.

## Resume wording

> Developed Windows storage-diagnostics tooling using C# and PowerShell, combining
> performance-counter and tracing evidence with an interactive dashboard and
> MCP-assisted investigation workflows.
