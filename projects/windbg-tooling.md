# WinDbg Tooling

**WinDbg | JavaScript | Windows kernel debugging | Storage diagnostics**

## Problem

Kernel debugging can involve a large amount of repetitive navigation before an
engineer identifies the useful questions. Debugger extensions can organize
evidence without replacing the engineer's interpretation.

## Projects

### Boot and hang triage

A WinDbg JavaScript extension helps narrow the initial investigation space in
boot and runtime-hang scenarios. Structured output supports exploratory
debugger queries instead of relying only on a long text report.

A single dump does not, by itself, prove that a thread or subsystem caused a hang.

### Storage Spaces Direct exploration

A read-only WinDbg extension organizes storage-state evidence into a navigable
debugging experience. The project includes investigation notebooks and
documentation to support repeatable exploration.

This showcase intentionally omits private Windows type layouts, debugger
expressions, build-specific offsets, and implementation details.

## What this demonstrates

- Extending an existing engineering tool instead of building a separate debugger.
- Using JavaScript and the debugger data-model experience to structure evidence.
- Translating repeated investigative tasks into reusable tooling.
- Documenting limitations alongside useful output.

## Resume wording

> Developed WinDbg JavaScript extensions for boot/hang triage and storage-state
> exploration, with structured investigation output and supporting notebooks.
