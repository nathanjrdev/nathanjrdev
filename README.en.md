<div align="center">

[🇧🇷 Português](./README.md) &nbsp;|&nbsp; 🇺🇸 English

<br>

<img src="./assets/banner.svg" alt="Nathan Jr. · AI Engineer in training · LLMs · Agents · MCP" width="100%">

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathan-jr-588b1638b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nathanjrdev)
![Open to opportunities](https://img.shields.io/badge/Open_to_opportunities-Remote_·_Hybrid-3DDC97?style=for-the-badge)

</div>

<br>

## 👋 About me

I'm a **Computer Engineering** student at **UNASP** (Brazil) and an intern in **CI&T's Next Gen AI** program, where I build software with AI every day.

I like taking generative AI into real products: semantic search, tool-calling agents and **MCP** integrations. Before code, I worked in **IT support** at UNASP's administration and I teach computer basics to kids at **Projeto Alphabit (ADRA)**. That taught me to start with the people who will use the system.

```python
from dataclasses import dataclass, field

@dataclass
class NathanJr:
    degree: str = "Computer Engineering @ UNASP (2024 → 2029)"
    now: str    = "Next Gen AI Intern @ CI&T"
    focus: list = field(default_factory=lambda: [
        "LLMs and tool-calling agents",
        "RAG, embeddings and semantic search",
        "MCP and Agent Skills",
        "AI evaluation with real metrics",
    ])
    certifications: int = 10         # 7 from the Claude track (Anthropic)

    def philosophy(self) -> str:
        return "AI is software: it needs tests, metrics and clear limits."
```

<br>

## 🤖 Featured project: Léia

> **🚧 In progress · v1 due Nov 14, 2026**

**Léia** is an AI assistant for book rentals. Readers chat in plain Portuguese ("a short thriller for the weekend") and she searches the catalog, checks stock at each branch, prices the rental and books it, always asking for confirmation first.

The point isn't the chat: it's **proving with numbers that the agent gets it right**.

```mermaid
flowchart LR
    U([👤 Reader]) -->|message| L[🤖 Léia<br/>LLM + tool calling]
    L -->|buscar_livros| B[(Postgres + pgvector<br/>catalog and embeddings)]
    L -->|ver_disponibilidade<br/>cotar_locacao| R[⚙️ Rules in code<br/>price · dates · stock]
    L -->|criar_reserva<br/>only after a “yes”| R
    L -->|transferir_para_humano| H([🧑‍💼 Human agent])
    L -.->|every turn| O[📊 Logs<br/>latency · tokens · cost]
```

| Principle | How Léia applies it |
|:--|:--|
| The model never makes up numbers | Price and stock always come from tools |
| Nothing is written without confirmation | Bookings and cancellations only after the reader says "yes" |
| Evaluation as software testing | Search Recall@5, tool accuracy and cost per conversation in the README |

<br>

## 🧪 AI Lab

| Project | What it does | Status |
|:--|:--|:--|
| **Léia** | Book-rental agent with 7 tools, hybrid search and automated evaluation | 🚧 In progress |
| **[Semantic Embeddings](https://github.com/nathanjrdev/Embeddings-semanticos-dashboard)** | Full embeddings pipeline: chunking, VoyageAI, L2 normalization, PCA and cosine-similarity search | ✅ Done |
| **[pixel-dev-office](https://github.com/nathanjrdev/pixel-dev-office)** | Pixel-art office for watching Claude Code agents at work | ✅ Done |
| **PT-BR embeddings model** | Fine-tuned multilingual model for Portuguese requests, published on Hugging Face | 📋 Planned |

<br>

## 🚀 Other projects

<div align="center">

| | Project | Highlight |
|:--:|:--|:--|
| 🃏 | **[Flashlingo](https://github.com/nathanjrdev/Flashlingo)** | English-learning app with spaced repetition (SM-2) and native pronunciation |
| 🌱 | **[Smart Garden](https://github.com/nathanjrdev/PROJETO-HORTA-INTELIGENTE)** | IoT: soil moisture, temperature and water sensors trigger irrigation on their own |
| 🩺 | **[MedicPlan](https://github.com/nathanjrdev/SAAS-medicplan)** | Medical planning SaaS in Next.js and TypeScript |

</div>

<br>

## 🛠️ Stack

**Languages**

<img src="https://skillicons.dev/icons?i=py,java,ts,js,cs,c,cpp" alt="Python, Java, TypeScript, JavaScript, C#, C, C++" />

**Frameworks & back-end**

<img src="https://skillicons.dev/icons?i=spring,nodejs,nextjs,react" alt="Spring Boot, Node.js, Next.js, React" />

<sub>REST APIs · Microservices · JWT · Automated testing</sub>

**Tools**

<img src="https://skillicons.dev/icons?i=docker,git,github,bitbucket,postman,vscode" alt="Docker, Git, GitHub, Bitbucket, Postman, VS Code" />

**AI & LLMs**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![VoyageAI](https://img.shields.io/badge/VoyageAI_Embeddings-5B4BDB?style=for-the-badge)

<sub>Tool calling · Agent Skills · RAG · Embeddings · Semantic search · PCA · LLM evaluation</sub>

<br>

## 🎓 Certifications

<div align="center">

![Anthropic](https://img.shields.io/badge/Anthropic-7_certificates-D97757?style=flat-square&logo=anthropic&logoColor=white)
![CI&T](https://img.shields.io/badge/CI%26T-Bootcamp_Next--Gen_2026-1A1A2E?style=flat-square)
![Rocketseat](https://img.shields.io/badge/Rocketseat-Java_·_Docker-8257E5?style=flat-square&logo=rocket&logoColor=white)

</div>

<details>
<summary><b>See the Claude track (Anthropic)</b></summary>

<br>

| Course | Issued |
|:--|:--|
| Model Context Protocol: Advanced Topics | Jul/2026 |
| Introduction to Model Context Protocol | Jul/2026 |
| Introduction to Agent Skills | Jul/2026 |
| Building with the Claude API | Jul/2026 |
| Claude Code in Action | Jul/2026 |
| Claude 101 | Jun/2026 |
| AI Fluency: Framework & Foundations | Aug/2026 |

</details>

<br>

## 🟡 Contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man eating the contribution graph" src="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph.svg">
</picture>

<sub>generated with <a href="https://github.com/abozanona/pacman-contribution-graph">abozanona/pacman-contribution-graph</a></sub>

</div>
