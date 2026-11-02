---
layout: default
---

<link rel="stylesheet" href="{{ '/css/oss-contributions.css' | relative_url }}">
<div id="oss-contributions" markdown="1">

### OSS Contributions

#### System & Toolchain Software

| Project | Contribution |
| :--- | :--- |
| LLVM | Fix `clang-cl` dependency file naming and default targets with `-o` · [#235578](https://github.com/llvm/llvm-project/pull/235578) <span class="oss-meta">Under review</span> |
| Zephyr-RTOS | Introduce type-safe socket polling interfaces · MISRA C Rule 17.1 · [#118426](https://github.com/zephyrproject-rtos/zephyr/pull/118426) · <span class="oss-meta">Milestoned for v4.6.0</span> |

#### Sanitizers & Static Analysis

| Project | Contribution |
| :--- | :--- |
| LLVM | Enable `strlcpy`/`strlcat` sanitizer interceptors on glibc 2.38+ · [#236414](https://github.com/llvm/llvm-project/pull/236414) |
| <span class="oss-cont"></span> | Fix MemorySanitizer false positives from `addrinfo` structure padding · [#219124](https://github.com/llvm/llvm-project/pull/219124) |
| <span class="oss-cont"></span> | Make `std::call_once` synchronization visible to ThreadSanitizer · <span class="oss-meta">Under review</span> |
| Cppcheck | Track static global buffer sizes to detect out-of-bounds access · [#8828](https://github.com/cppcheck-opensource/cppcheck/pull/8828) · <span class="oss-meta">Under review</span> |
| <span class="oss-cont"></span> | Fix missing dead-code alarms in C/C++ `switch` statements · [#8815](https://github.com/cppcheck-opensource/cppcheck/pull/8815) |

#### Fuzzing & Unit Testing

| Project | Contribution |
| :--- | :--- |
| MsQuic | Extract raw packet parsers and add libFuzzer coverage · [#6349](https://github.com/microsoft/msquic/pull/6349) · <span class="oss-meta">Design Discussion</span> |
| <span class="oss-cont"></span> | Add unit tests for valid and malformed IPv4/UDP packets · [#6312](https://github.com/microsoft/msquic/pull/6312) · <span class="oss-meta">Reviewed, pending</span> |
| Google OSS-Fuzz | Exercise previously untested functionality · Continuous fuzz testing |
| <span class="oss-cont"></span> | (libplist[#316](https://github.com/libimobiledevice/libplist/pull/316), oss-fuzz[#16203](https://github.com/google/oss-fuzz/pull/16203#event-32196194130)) (yyjson[#288](https://github.com/ibireme/yyjson/pull/288), oss-fuzz[#15858](https://github.com/google/oss-fuzz/pull/15858)) |

#### Regression & CI Validation

| Project | Contribution |
| :--- | :--- |
| Zephyr | Fix CI test selection errors that caused required tests to be skipped · [#116998](https://github.com/zephyrproject-rtos/zephyr/pull/116998) |
| <span class="oss-cont"></span> | Prevent CI from skipping tests affected by snippet changes · [#121480](https://github.com/zephyrproject-rtos/zephyr/pull/121480) |
| LLVM | Add regression test for Clang frontend crash · [#224798](https://github.com/llvm/llvm-project/pull/224798) |

</div>

<br>

### Teaching Assistant
- DiscreteMath \[[2019F](https://github.com/hongshin/DiscreteMath/tree/2019fall)\], \[[2020F](https://github.com/hongshin/DiscreteMath/tree/2020fall)\] 
- Operating System \[[2019S](https://github.com/hongshin/OperatingSystem/tree/2019spring)\], \[[2020S](https://github.com/hongshin/OperatingSystem/tree/2020spring)\], \[[2023S](https://github.com/hongshin/OperatingSystem/tree/2023spring)\]
- Software Engineering \[2019S\]
- Programming Language Theory \[[2024F](https://github.com/hongshin/proglang)\]
- Data Structures \[[2023S](https://github.com/hongshin/DataStructures/tree/2023)\], \[[2024S](https://github.com/hongshin/DataStructures)\]

<br>

### Teaching Activity
- Tutor, Programming Basics for North Korean defectors \[2019S\]

<br>
