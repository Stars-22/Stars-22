<div align="center">

# 繁星 · Stars-22

**C++ 服务端 · 高性能系统 · 架构设计 · 工程效能**
**C++ Backend · High-Performance Systems · Architecture · Developer Productivity**

![C++ Backend](https://img.shields.io/badge/C%2B%2B_%E6%9C%8D%E5%8A%A1%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Architect](https://img.shields.io/badge/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E5%B8%88-6A5ACD?style=for-the-badge)
![Dev Productivity](https://img.shields.io/badge/%E7%A0%94%E5%8F%91%E6%95%88%E8%83%BD%E5%B7%A5%E7%A8%8B%E5%B8%88-2E8B57?style=for-the-badge)
![SDK Engineer](https://img.shields.io/badge/SDK_%E5%BC%80%E5%8F%91%E5%B7%A5%E7%A8%8B%E5%B8%88-E8A020?style=for-the-badge)

[简体中文](#zh) · [English](#en)

</div>

---

<a id="zh"></a>

## 简体中文

### 关于我

专注于 **C++ 服务端与高性能系统**，习惯从架构设计、契约定义出发，把复杂系统拆成可设计、可验证、可交接的模块。对底层性能与工程化有执念：零依赖、可裁剪、缓存友好、可测试。

- **服务端 / 系统**：高并发、资源调度、并发模型选型、可靠性与容错
- **底层 / 高性能**：SIMD 向量化、内存池、缓存分块、访存优化
- **架构 / 工程**：分层与边界、契约先行、开闭原则、构建与可观测性

### 技术栈

**语言**

![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)

**高性能 / 底层**

![SIMD](https://img.shields.io/badge/AVX2_%2F_FMA-4B0082?style=flat-square)
![Memory Pool](https://img.shields.io/badge/Memory_Pool-4B0082?style=flat-square)
![Multithreading](https://img.shields.io/badge/Multithreading-4B0082?style=flat-square)
![Cache Aware](https://img.shields.io/badge/Cache_Aware-4B0082?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**服务端 / 工程**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### GitHub 统计

<div align="center">

<img height="165" src="https://github-stats.mintimate.cn/api?username=Stars-22&show_icons=true&theme=dark&hide_border=true&locale=cn" />
<img height="165" src="https://github-stats.mintimate.cn/api/top-langs?username=Stars-22&layout=compact&theme=dark&hide_border=true&locale=cn&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=Stars-22&theme=dark&hide_border=true&locale=zh_Hans" />

</div>

### 精选项目

| 项目 | 简介 | 技术 |
| --- | --- | --- |
| [**NetFountain**](https://github.com/Stars-22/NetFountain) | 两级代理 IP 池系统：一级池多供应商拉取净化去重，二级池按站点做出口连通验证形成租赁池，代理层按站点路由并原样透传，服务间以统一 HTTP API 进程级解耦 | Python · Vue 3 |
| [**PorxyPH**](https://github.com/Stars-22/PorxyPH) | 代理节点编排管理系统：一份订阅拆为独立端口，每节点一容器、幂等生命周期、健康检查与自动故障转移 | Go · Vue 3 · Docker |
| [**FluxMeld**](https://github.com/chenYJ2000/FluxMeld) | 本地多服务商 AI 路由工作台：OpenAI 兼容网关、账户池与健康感知负载均衡、安全工具调用 | TypeScript · Electron |
| [**SysTrace**](https://github.com/Stars-22/SysTrace) | 轻量级 Windows 系统资源历史监控：单文件部署，内置实时 CPU / 内存 / 磁盘热力图与可缩放时间线 | C++ |
| [**MemoryPool**](https://github.com/Stars-22/MemoryPool) | 线程安全的高并发内存池，三层缓存架构，降低多线程下的锁竞争与分配开销 | C++ |
| [**MessageWall**](https://github.com/Stars-22/MessageWall) · [**Inbox**](https://github.com/Stars-22/Inbox) · [**Cpp-Compiler**](https://github.com/Stars-22/Cpp-Compiler) · [**GTNH 核电 OC**](https://github.com/Stars-22/GTNH-PowerfulCoolingNuclearReactor) | 早期实践：校园信息墙服务、套接字通信、词法分析器、游戏内自动化 | C++ · Lua |

### C++ 底层与工程实践

> 以下为内部 / 私有项目，仅作能力说明，不提供链接。

**SLib — 自研神经网络算子库（手写 C++17）**

- **零第三方依赖**：C++17 + CMake 从零实现全部算子内核，不引入任何推理运行时或算子库，最大化可控性与可裁剪性。
- **高性能内核**：手写 AVX2/FMA 微内核 SGEMM（寄存器分块、K 步长模板特化、软件预取、掩码加载）；向量化激活函数并以多项式逼近替换标准库数学函数（sin / exp / tanh / erf）。
- **卷积与流式状态**：im2col + GEMM 通用卷积与因果卷积，设计滚动状态缓存支持流式推理；卷积分块参数按 L2 预算与 SIMD 宽度自动寻优。
- **信号处理**：任意长度 FFT / STFT-ISTFT（2 的幂用迭代 FFT、任意长度用 Bluestein chirp-Z），含周期 Hann 窗、重叠相加与窗平方和归一化。
- **内存与抽象**：对齐内存池 `BufferPool` + `Buffer` 偏移视图，以零拷贝视图在算子链间传递张量；`Module` / `Sequential` 统一算子接口，逐层复用消除反复分配。

**服务端基础设施与高并发**

- **资源调度与高可用**：两级资源池、租约 + TTL、健康检查与自动故障转移。
- **并发治理**：有界队列 + 固定 worker（队满丢最旧，长周期内存有界）、单写者模型、连接池串行 + keep-alive。
- **可靠性**：按批推进 checkpoint、仅整批落盘后推进水位、写锁冲突保留队首重试、中断回滚未完成批。
- **容器编排**：基于 Docker Engine API 的幂等容器生命周期（临时 init 容器写卷、按名清理）与周期健康检查。

**数据工程**

- **架构**：共享核心库 + 薄壳 CLI，依赖单向、核心库零副作用。
- **扩展性**：注册表 + 策略对象落地开闭原则，新增字段 / 规则 / 过滤策略不改既有流程。
- **数据管线**：单写者串行化持久化、批量提交、流式写出与断点续传。

### 联系

[![Email](https://img.shields.io/badge/1187598002%40qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:1187598002@qq.com)
[![Website](https://img.shields.io/badge/stars22.xyz-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white)](https://www.stars22.xyz)
[![GitHub](https://img.shields.io/badge/Stars--22-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Stars-22)

<p align="right"><a href="#en">English →</a></p>

---

<a id="en"></a>

## English

### About

Focused on **C++ backend and high-performance systems**. I start from architecture, contracts, and module boundaries, and turn complex systems into units that are designable, verifiable, and handoff-ready. Strong bias toward zero dependencies, cache-friendly code, and testability.

- **Backend / Systems**: high concurrency, resource scheduling, concurrency-model selection, reliability and fault tolerance
- **Low-level / Performance**: SIMD vectorization, memory pooling, cache blocking, memory-access optimization
- **Architecture / Engineering**: layering and boundaries, contract-first design, open-closed principle, build and observability

### Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)

**High Performance / Low Level**

![SIMD](https://img.shields.io/badge/AVX2_%2F_FMA-4B0082?style=flat-square)
![Memory Pool](https://img.shields.io/badge/Memory_Pool-4B0082?style=flat-square)
![Multithreading](https://img.shields.io/badge/Multithreading-4B0082?style=flat-square)
![Cache Aware](https://img.shields.io/badge/Cache_Aware-4B0082?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

**Backend / Engineering**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### GitHub Stats

<div align="center">

<img height="165" src="https://github-stats.mintimate.cn/api?username=Stars-22&show_icons=true&theme=dark&hide_border=true" />
<img height="165" src="https://github-stats.mintimate.cn/api/top-langs?username=Stars-22&layout=compact&theme=dark&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=Stars-22&theme=dark&hide_border=true" />

</div>

### Featured Projects

| Project | Description | Tech |
| --- | --- | --- |
| [**NetFountain**](https://github.com/Stars-22/NetFountain) | Two-tier proxy IP pool: tier-1 pulls, sanitizes and deduplicates from multiple providers; tier-2 validates site-level connectivity into a leasing pool; a routing layer forwards per site, with services decoupled over a unified HTTP API | Python · Vue 3 |
| [**PorxyPH**](https://github.com/Stars-22/PorxyPH) | Proxy node orchestration: one subscription split into standalone ports, one container per node, idempotent lifecycle, health checks and automatic failover | Go · Vue 3 · Docker |
| [**FluxMeld**](https://github.com/chenYJ2000/FluxMeld) | Local multi-provider AI routing workspace: OpenAI-compatible gateway, account pool with health-aware load balancing, and safe tool calling | TypeScript · Electron |
| [**SysTrace**](https://github.com/Stars-22/SysTrace) | Lightweight Windows system-resource history monitor: single-file deployment with a built-in real-time CPU / memory / disk heatmap and zoomable timeline | C++ |
| [**MemoryPool**](https://github.com/Stars-22/MemoryPool) | A thread-safe high-concurrency memory pool with a three-tier cache architecture to cut lock contention and allocation overhead | C++ |
| [**MessageWall**](https://github.com/Stars-22/MessageWall) · [**Inbox**](https://github.com/Stars-22/Inbox) · [**Cpp-Compiler**](https://github.com/Stars-22/Cpp-Compiler) · [**GTNH Reactor**](https://github.com/Stars-22/GTNH-PowerfulCoolingNuclearReactor) | Early work: campus message wall, socket communication, a lexer, and in-game automation | C++ · Lua |

### Low-Level C++ & Engineering Practice

> Internal / private projects, described only — no links.

**SLib — a hand-written C++17 neural-network operator library**

- **Zero third-party dependencies**: every operator kernel implemented from scratch with C++17 + CMake, no inference runtime or external operator library — maximizing control and trimmability.
- **High-performance kernels**: hand-written AVX2/FMA SGEMM micro-kernel (register blocking, K-step template specialization, software prefetch, masked loads); vectorized activations with polynomial approximations replacing libm math functions (sin / exp / tanh / erf).
- **Convolution & streaming state**: im2col + GEMM general and causal convolution with a rolling state cache for streaming inference; blocking parameters auto-tuned against L2 budget and SIMD width.
- **Signal processing**: arbitrary-length FFT / STFT-ISTFT (iterative FFT for powers of two, Bluestein chirp-Z otherwise) with periodic Hann window, overlap-add and window-sum normalization.
- **Memory & abstraction**: aligned memory pool `BufferPool` plus `Buffer` offset views, passing tensors across the operator chain as zero-copy views; unified `Module` / `Sequential` interfaces reuse buffers layer by layer.

**Backend infrastructure & high concurrency**

- **Resource scheduling & HA**: two-tier resource pools, lease + TTL, health checks and automatic failover.
- **Concurrency governance**: bounded queue + fixed workers (drop-oldest on full, bounded long-run memory), single-writer model, serial connection pool + keep-alive.
- **Reliability**: batch-wise checkpoint advance, commit-then-advance watermark, keep-head retry on write-lock contention, rollback of incomplete batches on interrupt.
- **Container orchestration**: idempotent container lifecycle via the Docker Engine API (ephemeral init container writing volumes, cleanup by name) with periodic health checks.

**Data engineering**

- **Architecture**: shared core library + thin CLI shells, unidirectional dependencies, side-effect-free core.
- **Extensibility**: registry + strategy objects implementing the open-closed principle so new fields, rules and filters require no changes to existing flows.
- **Pipelines**: single-writer serialized persistence, batched commits, streaming output and resumable execution.

### Contact

[![Email](https://img.shields.io/badge/1187598002%40qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:1187598002@qq.com)
[![Website](https://img.shields.io/badge/stars22.xyz-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white)](https://www.stars22.xyz)
[![GitHub](https://img.shields.io/badge/Stars--22-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Stars-22)

<p align="right"><a href="#zh">← 简体中文</a></p>
