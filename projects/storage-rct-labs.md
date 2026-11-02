# Storage, RCT & Virtualization Labs

**C++ | PowerShell | Windows Virtual Disk APIs | Hyper-V | VMware**

## Problem

Investigating virtual-disk change tracking requires understanding state before
and after an operation, while storage experiments need reproducible lab setups.

## Project family

| Project | Scope |
| --- | --- |
| RCT checker | Inspect change-tracking state and compare before/after observations |
| VHD backup prototype | Explore full/incremental backup chains and point-in-time restore behavior |
| VHDX locking tool | Investigate virtual-disk locking behavior in a controlled environment |
| S2D Lab Manager | Automate manifest-driven Hyper-V and VMware lab setup |
| RCT guides and branch demonstrations | Support focused experiments and explain observed state transitions |

## Engineering themes

- Combining native Windows tooling with PowerShell-based experiment orchestration.
- Keeping distinct diagnostic tools separate rather than presenting them as
  interchangeable versions of the same application.
- Capturing state around an operation to make lifecycle changes easier to explain.
- Using repeatable lab configuration to support systems investigation.

## Limitations

The backup implementation is an engineering proof of concept, not commercial
backup software. This showcase makes no claims about production durability,
security, retention, recovery guarantees, or supported internal interfaces.

Source code, internal control interfaces, on-disk layouts, machine manifests, and
customer data are not included here.

## Resume wording

> Developed C++ and PowerShell tools for Hyper-V RCT inspection, virtual-disk
> backup/restore experiments, and manifest-driven virtualization lab deployment.
