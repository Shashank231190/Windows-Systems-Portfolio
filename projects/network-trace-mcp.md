# NetworkTraceMcpAnalyzer

**C# | .NET | MCP | Network-trace tooling | AI-client integration**

## Problem

AI-assisted trace investigation is more useful when explanations are grounded in
tool-produced evidence rather than unsupported assumptions about a capture.

## Project overview

A two-console-application starter prototype:

- An MCP server exposes network-trace investigation tools.
- A client discovers the tools and uses an AI integration to help explain the
  returned evidence.

The project uses existing network-trace tooling and separates the diagnostic
server from the conversational client.

## Why this is a useful portfolio project

It connects systems diagnostics with practical AI integration. Alongside the
kernel and WinDbg work, it illustrates a progression from understanding low-level
behavior to making investigation tools accessible to other engineers.

## Current scope

The repository describes a starter design, not a production network-analysis
platform. This showcase does not claim complete protocol coverage, a deployed
service, benchmark results, or fully validated AI conclusions.

The public page includes no packet captures, cloud endpoints, credentials,
private tool contracts, or implementation source.

## Resume wording

> Prototyped a C# network-trace investigation workflow with an MCP tool server
> and a separate AI client for evidence-grounded explanations.
