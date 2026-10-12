# Hi, I'm Krishnan 👋

Computer Science undergraduate at **IIT Hyderabad** (B.Tech CSE, 2024-2028). I like systems, compilers, computer architecture and ML inference: building things close to the machine and measuring whether they actually work.

## Currently

- Fixing an **X86 backend crash in LLVM** on vector `atomicrmw` ([issue #226002](https://github.com/llvm/llvm-project/issues/226002), [PR #230788](https://github.com/llvm/llvm-project/pull/230788), open)
- Compiler construction: DSL front ends and lowering to LLVM/MLIR
- Research on speculative decoding and draft-model distillation

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [**LLVM contribution**](https://github.com/llvm/llvm-project/pull/230788) | Root-caused and fixed an X86 ISel crash: vector `atomicrmw` operands are now expanded to a `cmpxchg` loop, with regression tests with and without `+cx16` | C++, LLVM |
| [**RISC-V Toolchain & Web Simulator**](https://github.com/Rmuk655/RISC-V-Toolchain-Web-Simulator) | Assembler, disassembler, debugger, cache simulator and pipeline hazard detector; compiles to WebAssembly for a browser front end | C++17, WASM |
| [**xv6 Kernel Extensions**](https://github.com/Rmuk655/xv6-Kernel-Extensions) | Syscall-aware MLFQ scheduler, clock page replacement with swap, FCFS/SSTF disk scheduling, RAID 0/1/5-backed swap | C, RISC-V |
| [**DistillSpec research**](https://github.com/Rmuk655/Distill-Spec-Research) | Distillation objectives for speculative-decoding draft models on Qwen3 pairs; a careful negative result against a strong JSD baseline | Python, PyTorch |
| [**OCaml compiler extension**](https://github.com/Rmuk655/miniml-compiler-extension) | Exception handling across lexer, parser, AST, typechecker and runtime | OCaml |
| [**Gem5 FPU optimization**](https://github.com/Rmuk655/Gem5-FPU-Pipeline-Optimization) | Splitting integer work across integer and FP units; measured speed-ups and where they disappear | C |
| [**Data Structures**](https://github.com/Rmuk655/Data-Structures) | Balanced trees (AVL, red-black, 2-4, B-tree), hashing, graphs and 2-SAT, fuzz-tested against `std::set` | C++ |
| [**Business entity resolution**](https://github.com/Rmuk655/Amazon-ML-Hackathon) | Record-linkage pipeline for the Amazon ML Challenge: blocking, pruning and a two-pass LightGBM matcher | Python |
| [**Tune DSL**](https://github.com/Rmuk655/Tune-DSL) | Music DSL compiled to audio with three cross-checked backends (Python, C++, MLIR) | Python, MLIR |

## Interests

Operating systems · Compilers · Computer architecture · ML systems · Performance engineering

## A note on AI use

I use AI assistants for explanation, review and, in some projects, implementation. Where a project's implementation was written with an AI assistant under my direction (for example Tune DSL), its README says so.

## Profiles

[LinkedIn](https://www.linkedin.com/in/krishnan-r-iith/) · [LeetCode](https://leetcode.com/u/rmuk/) · [Codeforces](https://codeforces.com/profile/muk_r1)
