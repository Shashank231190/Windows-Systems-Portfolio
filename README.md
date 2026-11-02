# Windows Systems Portfolio

**Windows kernel-development labs, debugging extensions, storage diagnostics,
and AI-assisted investigation tools.**

This is a documentation-only showcase of my engineering work. It describes the
problems I explore, the technologies involved, and the boundaries of each
project. It does not publish private implementations.

## Start here

| Project | Focus | Project type |
| --- | --- | --- |
| [Windows driver labs](projects/kernel-driver-labs.md) | KMDF/WDM, filtering, callbacks, concurrency, tracing | Hands-on lab collection |
| [PerformanceAnalyzer](projects/performance-analyzer.md) | Windows storage-performance investigations | Engineering diagnostic tool |
| [LogConsultant](projects/log-consultant.md) | Windows servicing evidence and assisted investigation | Diagnostic tool with an integration prototype |
| [WinDbg tooling](projects/windbg-tooling.md) | Boot/hang triage and storage-state exploration | Debugger extensions |
| [RCT tools and lab automation](projects/storage-rct-labs.md) | Hyper-V change tracking, backup experiments, lab deployment | Engineering tools and proof of concept |
| [NetworkTraceMcpAnalyzer](projects/network-trace-mcp.md) | Network-trace evidence exposed to an AI client | Starter prototype |

## Technical themes

- **Kernel engineering:** driver models, user/kernel interaction, file-system
  filtering, callbacks, I/O completion, deferred work, synchronization, and tracing.
- **Systems investigation:** WinDbg, crash/hang evidence, storage telemetry, and
  measurement boundaries.
- **Tool development:** C/C++, C#, PowerShell, JavaScript, .NET, and MCP integration.
- **Engineering discipline:** repeatable labs, explicit limitations, and separation
  between diagnostic evidence and remediation.

## Publication boundaries

All pages are high-level descriptions. This repository contains no driver source,
private PerformanceAnalyzer or LogConsultant logic, algorithms, internal Windows
structure layouts, endpoint contracts, implementation diagrams, customer captures,
raw logs, credentials, or runnable binaries.

Existing implementation repositories retain their original visibility. No page
requires access to a private repository, and no demo or download is implied unless
explicitly provided.

Lab work, proof-of-concept tools, and diagnostic prototypes have different
readiness levels. They are not represented as production-qualified drivers,
commercial backup software, or supported Windows remediation products.

## Resume summary

Windows systems engineering work spanning kernel-driver labs, WinDbg extensions,
storage and virtualization diagnostics, and evidence-oriented AI/MCP prototypes.
See the individual project pages for specific capabilities and limitations.
