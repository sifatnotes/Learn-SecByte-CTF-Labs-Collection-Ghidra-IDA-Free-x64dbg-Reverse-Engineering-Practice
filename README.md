# Learn-SecByte-CTF-Labs-Collection-Ghidra-IDA-Free-x64dbg-Reverse-Engineering-Practice
A curated collection of hands-on reverse engineering CTF labs covering Ghidra, IDA Free, x64dbg, Binary Navigation, Stack Buffer Overflows, Control Flow Forensics, and Call Graph Analysis from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on binary reverse engineering, dynamic debugging, software disassembling, and vulnerability analysis labs designed for cybersecurity students, CTF players, reverse engineers, malware analysts, and exploit developers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Mastering reverse engineering disassemblers, interactive debuggers, and binary execution mechanics is fundamental to analyzing unknown software and discovering security vulnerabilities. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenge labs provides practical exposure to industry-standard tools and low-level execution analysis.

From disassembling binaries using Ghidra and IDA Free to setting dynamic breakpoints in x64dbg, tracing function call graphs, inspecting stack frame corruption (stack smashing), and navigating control flow paths, these exercises build foundational and advanced binary analysis skills.

---

## Lab Collection & Index

Below is the complete, searchable index of all reverse engineering tool and binary analysis challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Stack Trace to Stack Smash** | Vulnerability Analysis | Stack frame mechanics, buffer overflow execution, return address hijacking | [Access Lab](https://learn.secbyte.org/ctf/stack-trace-to-stack-smash) |
| 2 | **Call Graph Forensics: Function Flow Analysis** | Binary Analysis | Cross-reference (XREF) tracing, call tree construction, function reachability | [Access Lab](https://learn.secbyte.org/ctf/call-graph-forensics-function-flow-analysis) |
| 3 | **Control Flow Forensics: Following the Program's Path** | Binary Analysis | Basic block disassembly, jump conditions, control flow graph (CFG) analysis | [Access Lab](https://learn.secbyte.org/ctf/control-flow-forensics-following-the-programs-path) |
| 4 | **Function Analysis: Binary Behavior Under the Microscope** | Binary Analysis | Calling conventions (`cdecl`, `stdcall`, `fastcall`), stack arguments, local variables | [Access Lab](https://learn.secbyte.org/ctf/function-analysis-binary-behavior-under-the-microscope) |
| 5 | **Binary Navigation: From Bits to Bytes to Meaning** | Binary Fundamentals | PE/ELF headers, endianness, data types, opcode mapping, assembly basics | [Access Lab](https://learn.secbyte.org/ctf/binary-navigation-from-bits-to-bytes-to-meaning) |
| 6 | **Advanced x64dbg Debugging Lab** | Dynamic Analysis | Conditional breakpoints, memory breakpoints, hardware registers, unpacking | [Access Lab](https://learn.secbyte.org/ctf/advanced-x64dbg-debugging-lab) |
| 7 | **x64dbg Fundamentals: Reverse Engineering a Suspicious Windows Binary** | Dynamic Analysis | Step-over (`F8`), step-into (`F7`), string references, memory map inspection | [Access Lab](https://learn.secbyte.org/ctf/x64dbg-fundamentals-reverse-engineering-a-suspicious-windows) |
| 8 | **Advanced IDA Analysis: Unpacking a Protected Binary** | Disassembly & IDA | IDA scripts (IDC/IDAPython), plugin usage, manual OEP identification, unpacking | [Access Lab](https://learn.secbyte.org/ctf/advanced-ida-analysis-unpacking-a-protected-binary) |
| 9 | **IDA Free Fundamentals: Static Analysis from Zero to Flags** | Disassembly & IDA | Graph view navigation, function renaming, comment creation, string searching | [Access Lab](https://learn.secbyte.org/ctf/ida-free-fundamentals-static-analysis-from-zero-to-flags) |
| 10 | **Advanced Ghidra Analysis: Orion Firmware Case** | Decompilation & Ghidra | Firmware analysis, memory map configuration, custom processor modules, decompilation | [Access Lab](https://learn.secbyte.org/ctf/advanced-ghidra-analysis-orion-firmware-case) |
| 11 | **Ghidra Fundamentals: Binary Sleuthing in the Safehouse** | Decompilation & Ghidra | Decompiler output analysis, symbol tree, data type manager, function patching | [Access Lab](https://learn.secbyte.org/ctf/ghidra-fundamentals-binary-sleuthing-in-the-safehouse) |
| 12 | **Reverse Engineering Fundamentals: The Lost Updater** | Reversing Foundations | Static binary inspection, keygenning logic, hardcoded flag discovery | [Access Lab](https://learn.secbyte.org/ctf/reverse-engineering-fundamentals-the-lost-updater) |

---

## Categories

### 1. Reversing Tools: Ghidra & IDA Free
Master static binary analysis, disassembling, and decompilation utilizing NSA's Ghidra and Hex-Rays' IDA Free platforms.
- [IDA Free Fundamentals: Static Analysis from Zero to Flags](https://learn.secbyte.org/ctf/ida-free-fundamentals-static-analysis-from-zero-to-flags)
- [Advanced IDA Analysis: Unpacking a Protected Binary](https://learn.secbyte.org/ctf/advanced-ida-analysis-unpacking-a-protected-binary)
- [Ghidra Fundamentals: Binary Sleuthing in the Safehouse](https://learn.secbyte.org/ctf/ghidra-fundamentals-binary-sleuthing-in-the-safehouse)
- [Advanced Ghidra Analysis: Orion Firmware Case](https://learn.secbyte.org/ctf/advanced-ghidra-analysis-orion-firmware-case)

### 2. Dynamic Debugging: x64dbg
Execute dynamic analysis, set memory/hardware breakpoints, and trace binary execution paths in real-time.
- [x64dbg Fundamentals: Reverse Engineering a Suspicious Windows Binary](https://learn.secbyte.org/ctf/x64dbg-fundamentals-reverse-engineering-a-suspicious-windows)
- [Advanced x64dbg Debugging Lab](https://learn.secbyte.org/ctf/advanced-x64dbg-debugging-lab)

### 3. Low-Level Control Flow & Function Forensics
Deconstruct compiled binary structures, map execution paths, and analyze calling conventions across basic blocks.
- [Binary Navigation: From Bits to Bytes to Meaning](https://learn.secbyte.org/ctf/binary-navigation-from-bits-to-bytes-to-meaning)
- [Reverse Engineering Fundamentals: The Lost Updater](https://learn.secbyte.org/ctf/reverse-engineering-fundamentals-the-lost-updater)
- [Function Analysis: Binary Behavior Under the Microscope](https://learn.secbyte.org/ctf/function-analysis-binary-behavior-under-the-microscope)
- [Control Flow Forensics: Following the Program's Path](https://learn.secbyte.org/ctf/control-flow-forensics-following-the-programs-path)
- [Call Graph Forensics: Function Flow Analysis](https://learn.secbyte.org/ctf/call-graph-forensics-function-flow-analysis)

### 4. Vulnerability Mechanics & Stack Inspection
Examine stack memory allocations, trace buffer overflows, and investigate control flow hijacking.
- [Stack Trace to Stack Smash](https://learn.secbyte.org/ctf/stack-trace-to-stack-smash)

---

## Learning Path

Follow this structured progression path to build technical mastery in reverse engineering and dynamic debugging:

1. **Phase 1: Binary & Reversing Foundations** — Learn binary structures, assembly instructions, and basic static reversing:
   - [Binary Navigation: From Bits to Bytes to Meaning](https://learn.secbyte.org/ctf/binary-navigation-from-bits-to-bytes-to-meaning)
   - [Reverse Engineering Fundamentals: The Lost Updater](https://learn.secbyte.org/ctf/reverse-engineering-fundamentals-the-lost-updater)
   - [IDA Free Fundamentals: Static Analysis from Zero to Flags](https://learn.secbyte.org/ctf/ida-free-fundamentals-static-analysis-from-zero-to-flags)
   - [Ghidra Fundamentals: Binary Sleuthing in the Safehouse](https://learn.secbyte.org/ctf/ghidra-fundamentals-binary-sleuthing-in-the-safehouse)

2. **Phase 2: Dynamic Debugging & Control Flow Analysis** — Trace execution using x64dbg and analyze call graphs:
   - [x64dbg Fundamentals: Reverse Engineering a Suspicious Windows Binary](https://learn.secbyte.org/ctf/x64dbg-fundamentals-reverse-engineering-a-suspicious-windows)
   - [Function Analysis: Binary Behavior Under the Microscope](https://learn.secbyte.org/ctf/function-analysis-binary-behavior-under-the-microscope)
   - [Control Flow Forensics: Following the Program's Path](https://learn.secbyte.org/ctf/control-flow-forensics-following-the-programs-path)
   - [Call Graph Forensics: Function Flow Analysis](https://learn.secbyte.org/ctf/call-graph-forensics-function-flow-analysis)

3. **Phase 3: Advanced Analysis & Unpacking** — Handle protected binaries, firmware image reversing, and complex debugging:
   - [Advanced x64dbg Debugging Lab](https://learn.secbyte.org/ctf/advanced-x64dbg-debugging-lab)
   - [Advanced IDA Analysis: Unpacking a Protected Binary](https://learn.secbyte.org/ctf/advanced-ida-analysis-unpacking-a-protected-binary)
   - [Advanced Ghidra Analysis: Orion Firmware Case](https://learn.secbyte.org/ctf/advanced-ghidra-analysis-orion-firmware-case)

4. **Phase 4: Vulnerability & Memory Corruption** — Analyze stack frames and investigate stack smashing exploits:
   - [Stack Trace to Stack Smash](https://learn.secbyte.org/ctf/stack-trace-to-stack-smash)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and download the exercise binaries on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy analysis tools (Ghidra, IDA Free, x64dbg, Cutter, PEStudio) in an isolated security sandbox environment.
4. Set breakpoints, analyze decompiled functions, patch logic constraints, locate vulnerabilities, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, security research, and authorized technical training purposes. Never attempt to reverse engineer, patch, or exploit unauthorized software or production systems.
