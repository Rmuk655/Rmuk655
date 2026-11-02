# Hi, I'm Krishnan 👋

Computer Science undergraduate at **IIT Hyderabad** (B.Tech CSE, 2024-2028). I like systems, compilers, computer architecture and ML inference: building things close to the machine and measuring whether they actually work.

## Currently

- Contributing to **LLVM**: an X86 backend crash on vector `atomicrmw` ([issue #226002](https://github.com/llvm/llvm-project/issues/226002), [PR #230788](https://github.com/llvm/llvm-project/pull/230788), open) and a `LoopBoundSplit` post-loop guard fix ([PR #233253](https://github.com/llvm/llvm-project/pull/233253), open)
- Compiler construction: DSL front ends and lowering to LLVM/MLIR
- Research on speculative decoding and draft-model distillation ([write-up on Medium](https://medium.com/p/405d2f0bf53f))

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [**LLVM contributions**](https://github.com/llvm/llvm-project/pulls?q=is:pr+author:Rmuk655) | [#230788](https://github.com/llvm/llvm-project/pull/230788): root-caused and fixed an X86 ISel crash, so vector `atomicrmw` is now expanded to a `cmpxchg` loop, with regression tests with and without `+cx16`. [#233253](https://github.com/llvm/llvm-project/pull/233253): `LoopBoundSplit` now builds its post-loop guard from the original exit condition. Both open | C++, LLVM |
| [**RISC-V Toolchain & Web Simulator**](https://github.com/Rmuk655/RISC-V-Toolchain-Web-Simulator) | Assembler, disassembler, debugger, cache simulator and pipeline hazard detector; compiles to WebAssembly for a browser front end | C++17, WASM |
| [**xv6 Kernel Extensions**](https://github.com/Rmuk655/xv6-Kernel-Extensions) | Syscall-aware MLFQ scheduler, clock page replacement with swap, FCFS/SSTF disk scheduling, RAID 0/1/5-backed swap | C, RISC-V |
| [**DistillSpec research**](https://github.com/Rmuk655/Distill-Spec-Research) | Multi-GPU platform for speculative-decoding research: 500+ tracked experiments, 71 checkpoints, multi-rollout distillation that beat the JSD baseline, and delayed tree branching extended to trained drafts ([write-up](https://medium.com/p/405d2f0bf53f)) | Python, PyTorch, vLLM |
| [**OCaml compiler extension**](https://github.com/Rmuk655/miniml-compiler-extension) | Exception handling across lexer, parser, AST, typechecker and runtime; submitted upstream to plzoo as [PR #41](https://github.com/andrejbauer/plzoo/pull/41) (open) | OCaml |
| [**FPU-assisted integer execution**](https://github.com/Rmuk655/Gem5-FPU-Pipeline-Optimization) | Splitting integer multiply chains across integer and FP units by a throughput model; measured on gem5 (X86 O3) across optimisation levels, IU/FPU latencies and IU counts: about 2x on convolution at -O3 (via compiler vectorisation), no gain on factorial or matmul | C |
| [**BigInt Calculator**](https://github.com/Rmuk655/Arbitrary-Precision-Arithmetic-and-Programming-Fundamentals/tree/main/bigint-calculator) | Custom arbitrary-precision integer and decimal arithmetic in Java, with a CLI, runnable JAR and Python wrapper | Java |
| [**Data Structures**](https://github.com/Rmuk655/Data-Structures) | Balanced trees (AVL, red-black, 2-4, B-tree), hashing, graphs and 2-SAT, fuzz-tested against `std::set` | C++ |
| [**Business entity resolution**](https://github.com/Rmuk655/Amazon-ML-Hackathon) | Record-linkage pipeline for the Amazon ML Challenge: blocking, pruning and a two-pass LightGBM matcher | Python |
| [**Compiler Construction**](https://github.com/Rmuk655/Compiler-Construction) | Flex/Bison Tcl-to-C++ transpiler, Kaleidoscope front end emitting LLVM IR, Clang AST-matcher tools and LLVM IR studies | Flex, Bison, LLVM, Clang |
| [**Computer Networks**](https://github.com/Rmuk655/Computer-Networks) | Dual-stack VyOS static-routing lab and a C++ group messaging system with TCP control, UDP multicast and TLS | C++, VyOS |
| [**Tensora**](https://github.com/Rmuk655/TensoraCompiler) | DSL for ML computation graphs with static checking, typed graph IR, optimisation passes and MLIR/LLVM lowering | C++, MLIR |
| [**Tune DSL**](https://github.com/Rmuk655/Tune-DSL) | Music DSL compiled to audio with three cross-checked backends (Python, C++, MLIR) | Python, MLIR |

## Interests

Operating systems · Compilers · Computer architecture · ML systems · Performance engineering

## Profiles

[LinkedIn](https://www.linkedin.com/in/krishnan-r-iith/) · [LeetCode](https://leetcode.com/u/rmuk/) · [Codeforces](https://codeforces.com/profile/muk_r1)
