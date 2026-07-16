<!-- ========================================================= -->
<!-- Hero Section -->
<!-- ========================================================= -->

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0B0F19,50:13293D,100:3ECF8E&text=Hassan%20Ali%20Imran&fontSize=42&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=21&duration=3500&pause=1000&color=3ECF8E&center=true&vCenter=true&width=780&lines=Systems+Developer;Security+Researcher;Building+SentinelOS+Local;Developing+Wiretap;Kernel+Engineering+%7C+Rust+%7C+C%2B%2B+%7C+Linux;Performance+First+%E2%80%A2+Memory+Aware+%E2%80%A2+Low-Level"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/hassan-ali-imran-">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
  </a>

  <a href="mailto:hassanaliimran11@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" />
  </a>

  <a href="https://instagram.com/__hassan__alii">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" />
  </a>

  <img src="https://komarev.com/ghpvc/?username=hassanali775&style=flat&color=3ECF8E" />
</p>

---

# About

I am **Hassan Ali Imran**, a systems developer and Infrastructure Engineer focused on building high-performance infrastructure, execution runtimes, and low-level software.

My work sits at the intersection of operating systems, distributed infrastructure, networking, and security, with an emphasis on deterministic performance, explicit memory management, and efficient concurrency.

I enjoy designing software that stays close to the hardware while maintaining clean architecture, observability, and long-term maintainability.

<br>

| Engineering Snapshot | |
| :--- | :--- |
| Primary Focus | Systems Programming · Infrastructure Engineering · Security Research |
| Core Languages | C · C++ · Rust · Go · Python · Assembly |
| Platform | Linux |
| Research Areas | Operating Systems · eBPF · Kernel Internals · Distributed Systems |
| Engineering Style | Performance-first · Memory-aware · Concurrency-focused |
| Current Interests | Kernel Telemetry · Execution Runtimes · Hardware Isolation · Operating Systems |

---

# Engineering Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,rust,go,python,linux,git,postgres,mysql,mongodb,docker,gcp&perline=6"/>
</p>

<br>

| Systems | Infrastructure | Security |
| :--- | :--- | :--- |
| Linux | PostgreSQL | eBPF |
| Rust | RocksDB | Kernel Tracing |
| C / C++ | Zero-Copy Pipelines | Static Analysis |
| Assembly | Distributed Systems | Memory Isolation |
| POSIX Threads | Networking | Performance Profiling |

---

# Selected Engineering Projects

---

## Cognitive Data Nexus

A distributed, high-throughput memory grid and data infrastructure designed to explore sub-millisecond indexing, deterministic data movement, and zero-copy communication.

**Stack**

`Rust` • `C++` • `Go` • `RocksDB`

### Problem

Traditional storage engines often incur unnecessary overhead through serialization, runtime memory movement, and networking abstractions. Cognitive Data Nexus explores a memory-first architecture focused on reducing latency while sustaining high ingestion throughput.

### Highlights

- Lock-free multithreaded ring-buffer scheduler designed to minimize contention between worker threads.
- Zero-copy ingestion pipeline that moves raw bytes directly from network buffers into storage.
- Memory-mapped indexing strategy for efficient access patterns.
- Storage layer tuned around RocksDB to maximize read and write performance.
- Modular architecture intended for future distributed scaling.

---

## Aether Engine

A lightweight execution runtime focused on coordinating large numbers of micro-tasks while minimizing scheduler and context-switching overhead.

**Stack**

`C++` • `Assembly` • `POSIX Threads`

### Problem

Traditional operating system scheduling is optimized for general-purpose workloads rather than millions of extremely lightweight tasks. Aether Engine investigates runtime-level scheduling strategies that maximize CPU utilization while reducing synchronization costs.

### Highlights

- Lightweight task scheduling architecture.
- Assembly-assisted context-switching experiments focused on minimizing register save overhead.
- Lock-free work-stealing scheduler for dynamic load balancing.
- Runtime telemetry for cache misses, scheduling latency, and execution behavior.
- Designed around modular execution components for future scalability.

---

## Neuros

A hardware-oriented profiling and memory analysis engine built to study cache behavior, instruction execution, and memory-access patterns.

**Stack**

`C` • `Go` • `Linux`

### Problem

General-purpose profilers provide useful performance metrics but often abstract away low-level hardware behavior. Neuros explores cache activity and memory access characteristics to better understand execution bottlenecks.

### Highlights

- Integrates with Linux performance monitoring infrastructure.
- Studies cache hierarchy behavior and memory-access patterns.
- Collects low-level execution telemetry for analysis.
- Converts performance traces into visual representations of memory activity.
- Designed as an educational and experimental performance analysis platform.

---
# Research & Development

---

## Sentinel_OS

**Status:** `In Development`

An experimental operating system focused on lightweight execution, memory isolation, and kernel architecture.

**Stack**

`C` • `Rust` • `Assembly` • `QEMU`

### Current Work

- Custom scheduler design and task management.
- Virtual memory subsystem experimentation.
- Bootloader refinement and early initialization.
- Kernel-space isolation mechanisms.
- Performance instrumentation for scheduler evaluation.

---

## Wiretap

**Status:** `In Development`

An experimental network telemetry framework exploring high-performance packet processing using kernel-space instrumentation.

**Stack**

`C++` • `Go` • `eBPF` • `libpcap`

### Current Work

- Zero-copy packet ingestion.
- eBPF-based telemetry collection.
- High-performance ring-buffer communication.
- Kernel-space packet filtering.
- Runtime network analysis tooling.

---
# Engineering Principles

- Performance is a feature, not an afterthought.
- Measure before optimizing.
- Prefer explicit ownership over hidden runtime behavior.
- Keep abstractions honest and purposeful.
- Build observable systems before making them distributed.
- Simplicity scales better than unnecessary complexity.

---
# Engineering Map

                          Hassan Ali Imran
                                 │
        ┌────────────────────────┼────────────────────────┐
        │                        │                        │
    Systems                 Infrastructure            Security
        │                        │                        │
  C / C++ / Rust          Distributed Systems         eBPF
  Operating Systems       Zero-Copy Pipelines         Kernel Tracing
  Memory Management       Execution Runtimes          Hardware Isolation

  # GitHub Activity

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.shion.dev/api?username=hassanali775&theme=dark&hide_border=true&include_all_commits=true&count_private=true" width="100%" />
    </td>

    <td width="50%" align="center">
      <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=hassanali775&theme=dark&hide_border=true&layout=compact" width="100%" />
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=hassanali775&theme=dark&hide_border=true" width="97%" />
</p>

---
# Current Focus

- Building high-performance systems software with predictable runtime behavior.
- Deepening expertise in operating systems, execution runtimes, and kernel development.
- Exploring hardware-assisted security technologies such as AMD SEV and Intel SGX.
- Contributing to low-level open-source infrastructure and systems tooling.

---
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:0B0F19,50:13293D,100:3ECF8E"/>
</p>

