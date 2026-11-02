# Windows Kernel & Driver Development Labs

**C / C++ | Windows Driver Kit | KMDF | WDM | WinDbg | WPP / ETW**

## Purpose

Explore Windows kernel programming through focused driver/client projects rather
than treating the kernel as a black box. The collection covers driver models,
I/O flow, user/kernel interaction, concurrency, and observability.

These are controlled learning and engineering labs, not a production driver suite.

## Areas represented

| Area | Representative projects | Engineering focus |
| --- | --- | --- |
| Driver models | BoosterKMDF, BeepFilter | KMDF and legacy WDM examples; user-mode clients and filter-driver concepts |
| File-system filtering | LatencyFilterDriver, FilterDeleteProtect | Controlled I/O-behavior experiments and file-operation filtering |
| Process notifications | ProcNotify, bProcNotifyKernel | Callback-based process events and user/kernel interaction |
| Layered I/O | LayeredDriverCompletionRoutine | Requests moving through driver layers and completion handling |
| Deferred and threaded work | DpcDriverSample, WorkerThreadDriver | DPCs and kernel-worker-thread examples |
| Synchronization | SynchronizationPrimitives, DebuggingDispatcherObjects | Coordination primitives, events, mutexes, and thread behavior |
| Producer/consumer patterns | kProcStatCustomCallBack | Callback-oriented communication between cooperating components |
| Observability | WppTracingDriver, TraceMini | WPP and TraceLogging examples alongside driver/client projects |
| Debugging | DebugExt, ObjHandleDrv | Debugger-extension and object/handle investigation labs |

## What this work communicates

- Experience navigating both kernel-mode code and supporting user-mode clients.
- Breadth across I/O, callbacks, concurrency, tracing, and debugger-assisted work.
- A lab-based approach to understanding behavior before making conclusions.
- Awareness that code which changes timing or filters operations needs strict
  isolation from production workloads.

## Safety and scope

Timing-altering, blocking, or fault-oriented experiments belong in isolated test
VMs. No driver installation steps, interception techniques, fault-triggering code,
or deployable binaries are published here.

The collection does not establish production readiness, driver certification,
security assurance, or universal compatibility across Windows builds.

## Resume wording

> Developed Windows kernel-driver labs in C/C++ covering KMDF/WDM, file-system
> filtering, process callbacks, layered I/O completion, deferred work,
> synchronization, and WPP/TraceLogging, with supporting user-mode clients.
