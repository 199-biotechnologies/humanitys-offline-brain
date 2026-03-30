<div align="center">

# Humanity's Offline Brain

### The internet will fail. Your knowledge doesn't have to.

[![Star this repo](https://img.shields.io/github/stars/199-biotechnologies/humanitys-offline-brain?style=for-the-badge&logo=github&label=%E2%AD%90%20Star%20this%20repo&color=yellow)](https://github.com/199-biotechnologies/humanitys-offline-brain/stargazers)
[![Follow @longevityboris](https://img.shields.io/badge/Follow_%40longevityboris-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/longevityboris)

[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)
[![Open Source](https://img.shields.io/badge/Open_Source-blue?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://github.com/199-biotechnologies/humanitys-offline-brain)

**A self-contained system for preserving human knowledge and AI reasoning capability when connectivity fails.** Local LLM + curated knowledge archive. No internet required. Runs on hardware you can buy today. Powered by solar, generator, or wall outlet. One machine. All of human knowledge. Yours to keep.

[Why This Exists](#why-this-exists) | [Quick Start](#quick-start) | [How It Works](#how-it-works) | [Features](#features) | [What's Inside](#whats-inside) | [Contributing](#contributing) | [License](#license)

</div>

---

## Why This Exists

Civilisations have always been more fragile than they appeared to those living in them. The residents of Rome in 400 AD could not have imagined that within their grandchildren's lifetimes, the city's population would fall from over a million to fewer than fifty thousand, its aqueducts shattered, its libraries burned. They confused the temporary with the eternal.

We are not so different.

Our knowledge lives on distant servers, accessible through infrastructure we do not control and cannot repair. The scientific papers representing centuries of accumulated understanding exist as entries in corporate databases that may not outlast the decade. The books containing the wisdom of every generation before us are increasingly available only through connections that war, disaster, or simple neglect could sever.

We have built the greatest library in human history and made it dependent on the most fragile delivery mechanism ever devised.

**This project is a hedge against that fragility.**

Humanity's Offline Brain pairs two things that are useless without each other: a comprehensive archive of books and scientific literature, and a local language model capable of retrieving, synthesising, and applying that knowledge. Storage without intelligence is a graveyard of information. Intelligence without knowledge is an empty vessel. Together, they form something that could matter when nothing else works.

## Quick Start

> This project is currently a **guide and architecture specification**. Implementation is underway. Star and watch the repo to follow progress.

```bash
# Clone the guide
git clone https://github.com/199-biotechnologies/humanitys-offline-brain.git
cd humanitys-offline-brain
```

**What you will need:**

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| GPU | RTX 3090 (24 GB VRAM) | RTX 4090 / dual GPU |
| RAM | 64 GB | 128 GB |
| Storage | 20 TB HDD | 40+ TB NVMe + HDD array |
| Power | 500W PSU | Solar panel + battery bank |
| OS | Linux (Ubuntu 22.04+) | Any Linux distro |

Technical expertise is not required. The instructions in this guide can be executed by AI agents with terminal access. A non-technical person need only point an agent at this guide and grant it permission to act.

## How It Works

```
┌─────────────────────────────────────────────────────────┐
│                 HUMANITY'S OFFLINE BRAIN                 │
│                                                         │
│  ┌──────────────┐    ┌──────────────┐    ┌───────────┐  │
│  │   Knowledge  │    │  Local LLM   │    │  Search   │  │
│  │   Archive    │───▶│  (Reasoning) │◀──▶│  & RAG    │  │
│  │              │    │              │    │  Engine   │  │
│  │  Books       │    │  Llama /     │    │           │  │
│  │  Papers      │    │  Mistral /   │    │  Vector   │  │
│  │  Manuals     │    │  Qwen        │    │  Index    │  │
│  │  Guides      │    │              │    │           │  │
│  └──────────────┘    └──────────────┘    └───────────┘  │
│                                                         │
│  ┌──────────────────────────────────────────────────┐   │
│  │              Power: Solar / Generator / Grid      │   │
│  └──────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────┘
```

1. **Knowledge Archive** -- Curated corpus of essential human knowledge: medical texts, engineering references, agricultural guides, scientific papers, and foundational literature. Stored locally on commodity hard drives.

2. **Local LLM** -- Open-source language model (Llama, Mistral, Qwen, or equivalent) running on consumer GPU hardware. No cloud. No API. No internet. Just inference.

3. **RAG Engine** -- Retrieval-augmented generation layer that indexes the archive, searches it semantically, and feeds relevant context to the LLM. Ask a question, get an answer grounded in real sources.

The entire stack runs on a single workstation. Powered by solar, generator, or wall outlet. Indefinitely.

## Features

- **Fully offline** -- Zero internet dependency after initial setup. No API calls, no cloud, no phone-home telemetry.
- **Local reasoning** -- Language models don't just retrieve information. They reason with it. A GP with this system has the diagnostic support of an oncologist, cardiologist, and neurologist working alongside them.
- **Expertise democratisation** -- When specialists are unavailable, generalists equipped with this system perform like specialists. The knowledge of a thousand experts, made portable and local.
- **Modular by design** -- Not everyone needs everything. Individuals can maintain focused subsets (medicine, agriculture, engineering) requiring less hardware and less power.
- **Community-scale distribution** -- Communities can distribute domains across households, each preserving what none could hold alone. This is how libraries have always worked.
- **Agent-installable** -- The guide is designed so AI agents with terminal access can execute the full build. Point an agent at this repo and let it work.
- **Commodity hardware** -- Runs on hardware you can buy today. A curated corpus of essential knowledge fits on hard drives that cost less than a used car.

## What's Inside

| Category | Contents | Why It Matters |
|----------|----------|----------------|
| **Medical** | Clinical references, drug databases, diagnostic guides, surgical manuals | Medicine when hospitals are unreachable |
| **Engineering** | Electrical, mechanical, civil, structural references | Build and repair critical infrastructure |
| **Agriculture** | Crop science, soil management, animal husbandry, food preservation | Feed communities without supply chains |
| **Science** | Physics, chemistry, biology fundamentals, key research papers | Maintain and advance understanding |
| **Technology** | Programming references, networking, radio, power systems | Keep systems running and build new ones |
| **Trades** | Plumbing, welding, carpentry, masonry, machining | Practical skills for rebuilding |
| **General Knowledge** | History, law, governance, education, mathematics | The foundations of functional society |

## Contributing

We welcome contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Priority areas:
- Curated knowledge corpus lists and sourcing strategies
- LLM benchmarking for offline reasoning quality
- RAG pipeline optimisation for large local archives
- Hardware build guides and power system designs
- Domain-specific knowledge packages (medical, engineering, agriculture)
- Documentation and translation

## License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**This is not survivalism. It is prudence.**

A community with preserved scientific knowledge and the means to reason with it can continue where civilisation left off, rather than starting again from first principles. This project exists so that purposeful action remains possible -- even when the screens go dark.

Built by [Boris Djordjevic](https://github.com/longevityboris) at [199 Biotechnologies](https://github.com/199-biotechnologies) | [Paperfoot AI](https://paperfoot.ai)

[![Star this repo](https://img.shields.io/github/stars/199-biotechnologies/humanitys-offline-brain?style=for-the-badge&logo=github&label=%E2%AD%90%20Star%20this%20repo&color=yellow)](https://github.com/199-biotechnologies/humanitys-offline-brain/stargazers)
[![Follow @longevityboris](https://img.shields.io/badge/Follow_%40longevityboris-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/longevityboris)

</div>
