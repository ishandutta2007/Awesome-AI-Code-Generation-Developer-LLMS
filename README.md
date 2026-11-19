# Awesome-AI-Code-Generation-Developer-LLMS

## Top AI Code Generation & Developer LLMs Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Open-Weight Coding Foundation Models, Agentic Coding Harnesses, Local Code Inference, IDE Copilots & Fill-in-the-Middle (FIM) Engines*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Code Generation & Developer LLMs**. These platforms, foundation models, and developer harnesses generate multi-file software architectures, synthesize unit tests, power sub-second Fill-in-the-Middle (FIM) code completion, and run sovereign coding LLMs locally or on private clusters.



**Examples** include GitHub Copilot, Cursor, Windsurf (Codeium), Tabnine, Amazon Q Developer, Sourcegraph Cody, Replit Ghostwriter / Agent, Supermaven, JetBrains AI, and QwenLM/qwen-code (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-weight coding LLMs (`Qwen3-Coder`, `Qwen2.5-Coder`, `DeepSeek-Coder-V2`, `Codestral`, `StarCoder2`, `Devstral`, `GLM-4-Code`), agentic CLI/IDE harnesses (`Qwen Code`, `Continue`, `Cline`, `Aider`, `OpenHands`), and high-throughput local inference servers — ideal for software engineers, ML researchers, and organizations building private, self-hosted code generation pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[GitHub Copilot](https://github.com)**  

  Industry-standard AI code generation platform and autonomous coding agent offering multi-model inline autocomplete, Copilot Edits, automated PR workflows, and enterprise IP indemnity.



- **[Cursor](https://cursor.com)**  

  AI-native code editor forked from VS Code featuring custom predictive Tab models, repository-wide semantic indexing, Composer multi-file agents, and background cloud execution.



- **[Windsurf (formerly Codeium)](https://windsurf.com)**  

  Agentic AI IDE and extension suite powered by Cascade flows, deep codebase awareness, real-time terminal synchronization, and low-latency Supercomplete models.



- **[Supermaven](https://supermaven.com)**  

  Ultra-low-latency AI code completion platform built around a 1-million-token context window (Babble) for near-instantaneous inline predictions across large repositories.



- **[Tabnine](https://tabnine.com)**  

  Enterprise AI code generation platform emphasizing zero-data-retention privacy, air-gapped/VPC deployments, custom repository fine-tuning, and compliance-safe code models.



- **[Amazon Q Developer](https://amazon.com)**  

  Cloud AI software engineering assistant providing IDE code generation, automated runtime upgrades, security vulnerability scanning, and AWS infrastructure troubleshooting.



- **[Sourcegraph Cody](https://sourcegraph.com)**  

  Enterprise AI coding assistant leveraging Sourcegraph's code graph and multi-repository search for context-aware code generation, inline edits, and unit test synthesis.



- **[JetBrains AI Assistant & Junie](https://jetbrains.com)**  

  Natively integrated AI code generation and autonomous agentic workflow suite built directly into IntelliJ IDEA, PyCharm, WebStorm, GoLand, and Rider.



- **[Replit Ghostwriter & Replit Agent](https://replit.com)**  

  Cloud-based collaborative IDE and autonomous software generation platform capable of architecting, coding, debugging, and deploying full-stack apps from natural language.



- **[Anthropic Claude Code / OpenAI Codex](https://anthropic.com)**  

  Frontier cloud-powered reasoning models and terminal coding harnesses specialized in complex multi-file refactoring, SWE-bench issue resolution, and repository-scale code synthesis.





## Open-Source GitHub Projects



- **[Qwen Code (`QwenLM/qwen-code`)](https://github.com)**  

  Official open-source (`Apache-2.0`) agentic command-line coding workflow and developer harness from Alibaba Qwen, optimized for `Qwen3-Coder` with repository-scale understanding, automated refactoring, and MCP tool integration.



- **[Qwen2.5-Coder & Qwen3-Coder (`QwenLM/Qwen2.5-Coder`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) code-specific LLM family ranging from 0.5B to 32B+ parameters, delivering state-of-the-art code generation, bug fixing, and 128K-context repository reasoning.



- **[DeepSeek-Coder-V2 (`deepseek-ai/DeepSeek-Coder-V2`)](https://github.com)**  

  Open-source Mixture-of-Experts (`MoE`) coding language model matching frontier proprietary models in code generation, mathematical reasoning, and support for 338 programming languages.



- **[StarCoder2 (`bigcode-project/starcoder2`)](https://github.com)**  

  Transparent open-source (`OpenRAIL-M`) code LLM family (3B, 7B, 15B) trained by the BigCode community on permissively licensed The Stack v2 repositories across 600+ languages.



- **[Code Llama (`meta-llama/codellama`)](https://github.com)**  

  Foundational open-weight coding LLM family from Meta featuring specialized Python and Instruct variants alongside native Fill-in-the-Middle (FIM) code completion support.



- **[Mistral Codestral & Devstral (`mistralai/mistral-inference`)](https://github.com)**  

  High-efficiency open-weight coding and software-engineering agent models from Mistral AI engineered for low-latency FIM completion and multi-file repository navigation.



- **[OpenCoder (`OpenCoder-llm/OpenCoder-llm`)](https://github.com)**  

  Fully reproducible open-source (`Apache-2.0`) code LLM releasing not only model weights (1.5B & 8B) but also the complete reproducible data-cleaning pipeline, synthetic code corpora, and training checkpoints.



- **[Seed-Coder (`ByteDance-Seed/Seed-Coder`)](https://github.com)**  

  Open-source (`MIT`) 8B-parameter code foundation model family (`Base`, `Instruct`, `Reasoning`) utilizing model-centric data curation for competitive code synthesis and reasoning.



- **[Continue (`continuedev/continue`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) AI code assistant extension for VS Code and JetBrains enabling custom autocomplete, chat, and agent workflows backed by any local (`Ollama`/`vLLM`) or cloud LLM.



- **[Cline (`cline/cline`) & Roo Code (`RooCodeInc/Roo-Code`)](https://github.com)**  

  Popular open-source (`Apache-2.0`) autonomous VS Code coding agents capable of multi-file edits, terminal execution, browser inspection, and MCP tool integration with human-in-the-loop approval.



- **[Aider (`Aider-AI/aider`)](https://github.com)**  

  Pioneering open-source (`Apache-2.0`) terminal AI pair-programming assistant that maps Git repositories, coordinates edits across multiple files, runs tests, and auto-commits changes.



- **[Tabby (`TabbyML/tabby`)](https://github.com)**  

  Self-hosted open-source (`Apache-2.0`) AI coding assistant written in Rust offering repository-level RAG, real-time FIM autocomplete, and extensions for VS Code, Vim/Neovim, and IntelliJ.



- **[OpenHands (`All-Hands-AI/OpenHands`)](https://github.com)**  

  Open-source (`MIT`) platform for autonomous software-engineering agents operating inside sandboxed Docker runtimes with full bash, code editor, and web browser capabilities.



- **[Void (`voideditor/void`)](https://github.com)**  

  Open-source (`Apache-2.0`) Cursor alternative built on VS Code providing inline diff generation, local codebase indexing, and direct integration with self-hosted or commercial LLMs.



- **[Ollama (`ollama/ollama`)](https://github.com)**  

  Developer-favorite open-source (`MIT`) local LLM runner making it effortless to pull, quantize, and serve open-weight coding models (`Qwen3-Coder`, `DeepSeek`, `Codestral`) offline via an OpenAI-compatible API.



- **[vLLM (`vllm-project/vllm`)](https://github.com)**  

  High-throughput, memory-efficient open-source (`Apache-2.0`) LLM inference and serving engine featuring PagedAttention, speculative decoding, and prefix caching for team-scale code generation.



- **[llama.cpp (`ggml-org/llama.cpp`)](https://github.com)**  

  Portable open-source (`MIT`) C/C++ LLM inference engine enabling quantized GGUF coding models to run across CPU, NVIDIA CUDA, Apple Metal, AMD ROCm, and Vulkan hardware.



### Additional Strong Open-Source Options



- **[EvalPlus (`evalplus/evalplus`)](https://github.com)**, **[LiveCodeBench (`LiveCodeBench/LiveCodeBench`)](https://github.com)**, and **[BigCode Evaluation Harness (`bigcode-project/bigcode-evaluation-harness`)](https://github.com)** for rigorous, contamination-free benchmarking of code generation LLMs (`HumanEval+`, `MBPP+`, `SWE-bench`).

- **[The Stack v2 (`bigcode-project/the-stack-v2`)](https://huggingface.co)** and **[OpenCodeInstruct (`nvidia/OpenCodeInstruct`)](https://huggingface.co)** for open permissively licensed code pretraining and instruction-tuning datasets.

- **[Unsloth (`unslothai/unsloth`)](https://github.com)** and **[LLaMA-Factory (`hiyouga/LLaMA-Factory`)](https://github.com)** for fast LoRA/QLoRA fine-tuning of open coding models on private enterprise codebases.
