<div align="center">

🇧🇷 Português &nbsp;|&nbsp; [🇺🇸 English](./README.en.md)

<br>

<img src="./assets/banner.svg" alt="Nathan Jr. · AI Engineer em formação · LLMs · Agentes · MCP" width="100%">

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathan-jr-588b1638b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nathanjrdev)
![Aberto a oportunidades](https://img.shields.io/badge/Aberto_a_oportunidades-Remoto_·_Híbrido-3DDC97?style=for-the-badge)

</div>

<br>

## 👋 Sobre mim

Sou estudante de **Engenharia da Computação no UNASP** e estagiário no programa **Next Gen AI da CI&T**, onde desenvolvo software com IA no dia a dia.

Gosto de levar IA generativa para produtos reais: buscas semânticas, agentes que chamam ferramentas e integrações via **MCP**. Antes do código, passei pelo **suporte técnico da Reitoria do UNASP** e dou aulas de informática para crianças no **Projeto Alphabit (ADRA)**. Isso me ensinou a olhar primeiro para quem vai usar o sistema.

```python
from dataclasses import dataclass, field

@dataclass
class NathanJr:
    curso: str  = "Engenharia da Computação @ UNASP (2024 → 2029)"
    agora: str  = "Estagiário Next Gen AI @ CI&T"
    foco: list  = field(default_factory=lambda: [
        "LLMs e agentes com tool calling",
        "RAG, embeddings e busca semântica",
        "MCP e Agent Skills",
        "avaliação de IA com métricas reais",
    ])
    certificacoes: int = 10          # 7 delas na trilha Claude (Anthropic)

    def filosofia(self) -> str:
        return "IA é software: precisa de teste, métrica e limites claros."
```

<br>

## 🤖 Projeto em destaque: Léia

> **🚧 Em construção · v1 prevista para 14/11/2026**

A **Léia** é uma assistente de IA para locação de livros. O leitor conversa em linguagem natural ("um suspense curto para o fim de semana"), e ela busca no catálogo, confere o estoque de cada unidade, calcula o valor e fecha a reserva, sempre pedindo confirmação antes.

O diferencial não é o chat: é **provar com números que o agente acerta**.

```mermaid
flowchart LR
    U([👤 Leitor]) -->|mensagem| L[🤖 Léia<br/>LLM + tool calling]
    L -->|buscar_livros| B[(Postgres + pgvector<br/>catálogo e embeddings)]
    L -->|ver_disponibilidade<br/>cotar_locacao| R[⚙️ Regras em código<br/>preço · datas · estoque]
    L -->|criar_reserva<br/>só após o “sim”| R
    L -->|transferir_para_humano| H([🧑‍💼 Atendente])
    L -.->|cada turno| O[📊 Logs<br/>latência · tokens · custo]
```

| Princípio | Como a Léia aplica |
|:--|:--|
| O modelo não inventa números | Preço e estoque vêm sempre das ferramentas |
| Nada é gravado sem confirmação | Reserva e cancelamento só depois do "sim" do leitor |
| Avaliação como teste de software | Recall@5 da busca, acerto de ferramenta e custo por conversa no README |

<br>

## 🧪 Laboratório de IA

| Projeto | O que faz | Status |
|:--|:--|:--|
| **Léia** | Agente de locação de livros com 7 ferramentas, busca híbrida e avaliação automatizada | 🚧 Em construção |
| **[Embeddings Semânticos](https://github.com/nathanjrdev/Embeddings-semanticos-dashboard)** | Pipeline completo de embeddings: chunking, VoyageAI, normalização L2, PCA e busca por similaridade de cosseno | ✅ Pronto |
| **[pixel-dev-office](https://github.com/nathanjrdev/pixel-dev-office)** | Escritório em pixel-art para monitorar agentes do Claude Code trabalhando | ✅ Pronto |
| **Modelo de embeddings PT-BR** | Ajuste fino de um modelo multilíngue para pedidos em português, publicado no Hugging Face | 📋 Planejado |

<br>

## 🚀 Outros projetos

<div align="center">

| | Projeto | Destaque |
|:--:|:--|:--|
| 🃏 | **[Flashlingo](https://github.com/nathanjrdev/Flashlingo)** | App de inglês com repetição espaçada (algoritmo SM-2) e pronúncia nativa |
| 🌱 | **[Horta Inteligente](https://github.com/nathanjrdev/PROJETO-HORTA-INTELIGENTE)** | IoT: sensores de umidade, temperatura e água acionam a irrigação sozinhos |
| 🩺 | **[MedicPlan](https://github.com/nathanjrdev/SAAS-medicplan)** | SaaS de planejamento médico em Next.js e TypeScript |

</div>

<br>

## 🛠️ Stack

**Linguagens**

<img src="https://skillicons.dev/icons?i=py,java,ts,js,cs,c,cpp" alt="Python, Java, TypeScript, JavaScript, C#, C, C++" />

**Frameworks e back-end**

<img src="https://skillicons.dev/icons?i=spring,nodejs,nextjs,react" alt="Spring Boot, Node.js, Next.js, React" />

<sub>APIs REST · Microsserviços · JWT · Testes automatizados</sub>

**Ferramentas**

<img src="https://skillicons.dev/icons?i=docker,git,github,bitbucket,postman,vscode" alt="Docker, Git, GitHub, Bitbucket, Postman, VS Code" />

**IA e LLMs**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![VoyageAI](https://img.shields.io/badge/VoyageAI_Embeddings-5B4BDB?style=for-the-badge)

<sub>Tool calling · Agent Skills · RAG · Embeddings · Busca semântica · PCA · Avaliação de LLMs</sub>

<br>

## 🎓 Certificações

<div align="center">

![Anthropic](https://img.shields.io/badge/Anthropic-7_certificações-D97757?style=flat-square&logo=anthropic&logoColor=white)
![CI&T](https://img.shields.io/badge/CI%26T-Bootcamp_Next--Gen_2026-1A1A2E?style=flat-square)
![Rocketseat](https://img.shields.io/badge/Rocketseat-Java_·_Docker-8257E5?style=flat-square&logo=rocket&logoColor=white)

</div>

<details>
<summary><b>Ver a trilha Claude (Anthropic)</b></summary>

<br>

| Curso | Emissão |
|:--|:--|
| Model Context Protocol: Advanced Topics | Jul/2026 |
| Introduction to Model Context Protocol | Jul/2026 |
| Introduction to Agent Skills | Jul/2026 |
| Building with the Claude API | Jul/2026 |
| Claude Code in Action | Jul/2026 |
| Claude 101 | Jun/2026 |
| AI Fluency: Framework & Foundations | Ago/2026 |

</details>

<br>

## 🟡 Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/nathanjrdev/nathanjrdev/output/pacman-contribution-graph.svg">
</picture>

<sub>gerado com <a href="https://github.com/abozanona/pacman-contribution-graph">abozanona/pacman-contribution-graph</a></sub>

</div>
