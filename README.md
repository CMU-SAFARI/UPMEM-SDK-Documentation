# UPMEM SDK Documentation

This repository hosts the documentation of the UPMEM DPU SDK (version 2025.1.0) for students of the SAFARI computer architecture courses and the UPMEM lab. UPMEM no longer offers the SDK or its documentation on sdk.upmem.com, so we keep a copy here.

**Read the documentation online at https://cmu-safari.github.io/UPMEM-SDK-Documentation/**

## Where to start

If you are new to UPMEM, read these pages in order.

| Step | Page |
|---|---|
| 1 | [Toolchain at a glance](https://cmu-safari.github.io/UPMEM-SDK-Documentation/00_ToolchainAtAGlance.html) |
| 2 | [Hello World](https://cmu-safari.github.io/UPMEM-SDK-Documentation/02_HelloWorld.html) |
| 3 | [Programming with UPMEM DPUs](https://cmu-safari.github.io/UPMEM-SDK-Documentation/03_ProgrammingWithUpmemDpu.html) |
| 4 | [Tasklets](https://cmu-safari.github.io/UPMEM-SDK-Documentation/030_DPURuntimeService_Tasklets.html) |
| 5 | [Memory (WRAM and MRAM)](https://cmu-safari.github.io/UPMEM-SDK-Documentation/031_DPURuntimeService_Memory.html) |
| 6 | [Communication with the host](https://cmu-safari.github.io/UPMEM-SDK-Documentation/032_DPURuntimeService_HostCommunication.html) |
| 7 | [Controlling DPUs from the host](https://cmu-safari.github.io/UPMEM-SDK-Documentation/06_ControllingDPUFromHost.html) |
| 8 | [Measuring performance](https://cmu-safari.github.io/UPMEM-SDK-Documentation/071_MeasuringPerformances.html) |

## Reference

| Topic | Page |
|---|---|
| Host C API | [C API](https://cmu-safari.github.io/UPMEM-SDK-Documentation/CAPI/index.html) |
| DPU runtime library | [DPU runtime](https://cmu-safari.github.io/UPMEM-SDK-Documentation/DPURT/index.html) |
| Debugging with LLDB | [Debugging](https://cmu-safari.github.io/UPMEM-SDK-Documentation/08_DebuggingWithUpmemDpu.html) |
| Profiling | [Profiling](https://cmu-safari.github.io/UPMEM-SDK-Documentation/260_Profiling.html) |
| Instruction set | [DPU instruction set](https://cmu-safari.github.io/UPMEM-SDK-Documentation/201_IS.html) |
| Coding tips | [Coding tips](https://cmu-safari.github.io/UPMEM-SDK-Documentation/fff_CodingTips.html) |
| Known issues | [Release notes and known issues](https://cmu-safari.github.io/UPMEM-SDK-Documentation/ggg_ReleaseNotesAndKnownIssues.html) |

The site also has a search box and a full index of the C++, Python, Java, and low-level C APIs.

## Reading the documentation offline

Clone the repository and open `docs/index.html` in a browser.

```bash
git clone https://github.com/CMU-SAFARI/UPMEM-SDK-Documentation.git
open UPMEM-SDK-Documentation/docs/index.html
```

On Linux, use `xdg-open` instead of `open`.

## Disclaimer

UPMEM published this documentation as part of the UPMEM DPU SDK. All rights belong to UPMEM, which is now part of Qualcomm. SAFARI hosts this copy for teaching only and has no affiliation with UPMEM or Qualcomm.
