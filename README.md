<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1400&color=00C6FF&center=true&vCenter=true&width=680&lines=Cybersecurity+%7C+Networking+%7C+LLMs;AI+harnesses+%7C+Jailbreak+research;Local+LLM+inference+%7C+AMD+GPU+optimization;Open-source+tools+%7C+French+%26+English" alt="Typing animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-111827?style=flat-square&logo=kalilinux&logoColor=white" alt="Cybersecurity" />
  <img src="https://img.shields.io/badge/Networks-0B7285?style=flat-square&logo=cisco&logoColor=white" alt="Networks" />
  <img src="https://img.shields.io/badge/LLMs%20%2F%20AI-7F00FF?style=flat-square&logo=openai&logoColor=white" alt="LLMs and AI" />
  <img src="https://img.shields.io/badge/French%20%2B%20English-00C6FF?style=flat-square&logo=googletranslate&logoColor=white" alt="French and English" />
</p>

## 👋 About me

I am a man passionate about **cybersecurity**, **networking**, and **LLMs / artificial intelligence**.

I research AI systems, with a particular focus on **AI harnesses**, model robustness, and **jailbreaks**. I also contribute to open-source agent infrastructure and **local LLM inference**, including **AMD GPU optimization with HIP**.

## 🔬 Research interests

- AI harnesses, agent infrastructure, and tool-use workflows
- Jailbreak research, red teaming, and model robustness
- Cybersecurity, network analysis, and defensive engineering
- Local LLM inference, GPU kernels, and reproducible performance benchmarks
- Developer tooling, automation, and regression testing

## 🚀 Contributions & projects

### PolyStrata — AMD GPU inference

Two contributions merged upstream on **October 27, 2026**:

- **[HIP optimization — PR #85](https://github.com/VecSzn/PolyStrata/pull/85):** implemented an opt-in split value reduction for Qwen3.6 MoE-compatible attention on AMD GPUs, reusing existing scratch memory without another VRAM allocation.
- **[Reproducible benchmarks — PR #86](https://github.com/VecSzn/PolyStrata/pull/86):** on an **RX 9070 XT**, measured **+7.8% decode throughput at 32K context** and **+22.2% at 98K** (36.5 → 44.6 tokens/s), with the same sampled peak VRAM of **14.50 GiB**.
- Added HIP GPU tests covering **414 numerical checks**, plus raw benchmark outputs, hashes, and reproduction commands.

Measured with **Cyber-Tiel-Coder-35B-A3B UD-Q4_K_XL**, Q8_0 KV cache, graphs disabled, and three restarted runs per setting. Results apply to this tested configuration; the optimization is disabled by default.

### Hermes Agent

- Identified and reproduced a Desktop/TUI bug where <code>prefill_messages_file</code> was ignored.
- Traced the execution path to <code>tui_gateway.server._make_agent</code> and submitted the tested [PR #105945](https://github.com/NousResearch/hermes-agent/pull/105945).
- Credited as a co-author of the merged Desktop/TUI prefill fix ([commit 4503c24](https://github.com/NousResearch/hermes-agent/commit/4503c24), [PR #122251](https://github.com/NousResearch/hermes-agent/pull/122251)), following my diagnosis and original PR #105945.

### KeepClaw

An Android host for PicoClaw, with an agent core and local web console running in a foreground service. [View project →](https://github.com/leakedd/KeepClaw)

### Other projects

- [Hermes Agent fork](https://github.com/leakedd/hermes-agent) — exploring and testing the agent codebase.
- [RR02](https://github.com/leakedd/RR02) — C++ project.

## 🧰 Tools & languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,java,git,github,android,linux&theme=dark" alt="Technologies" />
</p>

<p align="center">
  <sub>French and English · Français et anglais</sub>
</p>
