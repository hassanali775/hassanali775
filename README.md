<p align="center">
  <img src="https://capsule-render.vercel.app/type/slice&color=0d1117&height=180&section=header&text=Hassan%20Ali%20Imran&fontSize=45&fontColor=3ecf8e&fontAlignY=45" alt="Hassan Ali Imran profile header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3500&pause=1000&color=3ECF8E&center=true&vCenter=true&width=550&lines=Developing+Sentinel_OS;Refining+Wiretap+modules;Low-level+systems+%26+eBPF" alt="Typing introduction" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/hassan-ali-imran-"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:hassanaliimran11@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://instagram.com/__hassan__alii"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=flat&logo=Instagram&logoColor=white" alt="Instagram" /></a>
</p>

## About My Work

I am Hassan Ali Imran, a systems developer and security researcher building secure, lightweight operating system environments and high-performance network monitoring modules.

I focus on projects where performance isn't an afterthought. My best work connects bare-metal execution with safe memory management, secure boot verification, kernel tracing, and robust network event captures.

| Systems Architecture | Network Telemetry | Kernel-level Performance |
| :--- | :--- | :--- |
| Microkernel Design | Raw Packet Ingestion | eBPF Event Tracing |
| Secure Boot Chains | Zero-copy Ring Buffers | Memory Barrier Isolation |

| | |
| :--- | :--- |
| **Best at** | Custom OS design, Linux kernel performance tuning, packet sniffing architectures, and systems programming in C/Rust. |
| **Main stack** | C, C++, Rust, Go, eBPF, QEMU, Linux, Python. |
| **Engineering habits** | Manual memory safety, static analysis validation, zero-trust system models, kernel-space isolation, and rigorous integration testing. |
| **Current direction** | Implementing advanced eBPF tracing modules for Wiretap and optimizing scheduler context-switching performance for Sentinel_OS. |

---

## Featured Builds

### Sentinel_OS
A secure, lightweight custom operating system environment engineered for minimal resource footprints.

*Stack: C, Assembly, Custom Bootloaders, Rust, QEMU.*

**Why it matters:** Most modern OS distributions carry significant legacy bloat. Sentinel_OS aims to strip out unnecessary abstraction layers, utilizing a minimal micro-kernel architecture with strictly isolated execution rings and secure-boot trust anchors.

**Interesting parts**
* Custom early-stage bootloader implementing secure boot protocol validation.
* Lightweight virtual memory manager engineered to strictly isolate kernel execution space from user-space privilege escalations.
* *In progress:* Optimizing multi-core CPU scheduling metrics to reduce task context-switching overhead.

### Wiretap
High-performance, zero-overhead network monitoring and packet analysis modules.

*Stack: C++, Go, eBPF, Raw Sockets, libpcap.*

**Why it matters:** Standard user-space packet sniffers induce heavy context-switching and copying overhead under heavy network loads. Wiretap shifts packet classification and telemetry directly into the kernel using eBPF, preserving processing throughput.

**Interesting parts**
* High-speed, zero-copy memory ring architectures optimized for raw frame ingestion.
* Dynamic eBPF kernel maps to safely aggregate network statistics and metrics without leaving kernel space.
* *In progress:* Integrating kernel-level filtering arrays to drop malicious traffic patterns at the driver layer.

---

## Skill Map
Systems Developer & Security Engineer
│
├── Systems & Kernel Route ──────► Custom OS Design • Memory Managers • Bootloaders • Kernel Tuning
│                                  (Demonstrated in: Sentinel_OS microkernel architecture)
│
├── Network Telemetry Route ────► Raw Sockets • Protocol Parsers • eBPF Event Maps • Packet Filters
│                                  (Demonstrated in: Wiretap network monitoring engines)
│
└── Deployment & Security Route ─► Secure Boot Anchors • Static Analysis • QEMU Emulation • CI Automation

**Strongest zone:** custom low-level architectures + strict memory safety + zero-overhead event capture

---

## GitHub Motion

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=hassanali775&theme=dark&hide_border=false&include_all_commits=true&count_private=true" width="48%" alt="GitHub stats" />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=hassanali775&theme=dark&hide_border=false&include_all_commits=true&layout=compact" width="48%" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=hassanali775&theme=dark&hide_border=false" width="97%" alt="GitHub streak" />
</p>

---

## Current Focus

* Deepening expertise in hardware-enforced security boundaries (such as AMD SEV / Intel SGX).
* Collaborating on open-source, low-level cybersecurity tools and kernel-space frameworks.
* Breaking and debugging experimental kernel configurations to understand limits and build back stronger.

<p align="center">
  <img src="https://capsule-render.vercel.app/type/waving&color=0d1117&height=80&section=footer" alt="Footer wave" width="100%" />
</p>
