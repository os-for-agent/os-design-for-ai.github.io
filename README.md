# AgenticOS 2026: Operating Systems Design for AI Agents

(Co-located with ASPLOS 2026)

AI agents are rapidly evolving from experimental prototypes to always-on services that autonomously plan, invoke external tools, collaborate, and continuously interact with their environment. This shift challenges traditional operating system abstractions—processes, threads, files, sockets, and resource controllers—which were never designed for dynamic, semantically rich, adaptive agent workloads. To support AI agents at scale, operating systems themselves must become *agentic*, adapting their abstractions and resource management policies to the semantic behaviors of agents.

The AgenticOS workshop seeks original position papers and experience reports that explore OS-level mechanisms for AI-agent workloads. Our goal is to define the primitives, isolation models, scheduling techniques, and observability mechanisms necessary to build operating systems explicitly tailored to agent-based systems.

## Topics of interest include (but are not limited to):

* New OS abstractions for agent execution (process/container/multikernel enhancements)
* Dynamic sandboxing and lightweight runtimes for securely executing agent-generated code and tasks
* Semantics-aware resource management and scheduling for dynamic, multi-agent workloads
* Long-lived state abstractions for managing agent context, prompts, and episodic memory
* eBPF-driven extensions for real-time observability, adaptation, and constraint enforcement
* Compiler–OS co-design for adaptive and agent-aware JIT execution strategies
* GPU and accelerator virtualization for large-scale deployment of agent workloads
* Security and isolation mechanisms for agent-invoked tools, code, and data flows
* Agents managing systems: kernel tuning, anomaly detection, resource orchestration, failure recovery, and dynamic policy updates

## Submission guidelines

We solicit two types of submissions:

* **Extended abstracts for talks**
  1–2 pages (excluding references). Suitable for early-stage ideas, position statements, ongoing projects, or demos. Accepted abstracts will be presented at the workshop.
* **Short/position papers**
  Up to 6 pages (excluding references). Suitable for more complete concepts, research results, experience reports, or comprehensive position papers. Accepted papers may appear in the ACM Digital Library (authors may opt out).

All submissions must follow the ACM double-column conference format. The review process is single-blind, with each submission receiving at least two reviews. Extended abstracts will appear only on the workshop website unless authors request archival publication.
