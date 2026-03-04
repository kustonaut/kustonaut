# Hey, I'm Akshay 👋

**Senior Product Manager at Microsoft · Excel Product Group**
Build → prototype → eval → production · Hands-on with RAG, agents, triage pipelines
**Outcome:** 350 PB/day data platforms · 6,000+ issues triaged · 22 Copilot skills in daily production

I build AI agents, triage pipelines, and analytics engines for real workflows — then open-source them.

**🌐 [kustonaut.github.io/portfolio](https://kustonaut.github.io/portfolio)** — live demos, architecture deep-dives, and everything I ship.

```
Build   → AI agents, eval systems, PM tooling
Think   → Rules-first → LLM-fallback → eval → iterate
Ship    → 3 production tools, 22 Copilot skills, 50+ automations
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dixitakshay-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/dixitakshay)
[![Twitter](https://img.shields.io/badge/Twitter-kustonaut-1DA1F2?style=flat&logo=x)](https://twitter.com/kustonaut)
[![Portfolio](https://img.shields.io/badge/Portfolio-kustonaut.github.io-06060b?style=flat&logo=github)](https://kustonaut.github.io)

---

### ⭐ Star Repos

I own the **Add-ins & Copilot extensibility platform** in Excel — the surface where third-party developers and ISVs plug into Office. On the side, I build open-source PM tooling that I use every day in production:

| Project | What it does | Why this approach | What I'd improve |
|---------|-------------|-------------------|-------------------|
| [**brain-os**](https://github.com/kustonaut/brain-os) | AI-powered daily OS for PMs — 22 Copilot skills, daily intelligence pipeline, Command Center dashboard | Local-first, config-driven. Every PM tool should be a VS Code skill, not a SaaS subscription. | Multi-model routing (GPT-4o for classification, Claude for synthesis), cross-PM onboarding wizard |
| [**issue-sentinel**](https://github.com/kustonaut/issue-sentinel) | AI issue triage — classify, prioritize, route. Zero manual effort. | Rules-first catches 60% at zero cost. LLM handles the remaining 35%. Eval suite tracks accuracy over time. | Fine-tuned classifier to push rules-first coverage to 80%, A/B eval framework for prompt variants |
| [**github-issue-analytics**](https://github.com/kustonaut/github-issue-analytics) | 13-metric scorecard from thousands of issues — fix rate, DSAT proxy, SHS, area heatmaps | Because at scale, you need data — not opinions. ETL → classify → score → dashboard. | Streaming ingestion for real-time alerts, anomaly detection on metric trends |

> Each repo follows the same pattern: **Problem → Architecture → Why this approach → Tradeoffs → Demo → What I'd improve.**

---

### 🔧 What I Work On

- Retrieval-augmented triage pipelines (rule-based + LLM hybrid classification)
- Agent orchestration with MCP servers and GitHub Actions
- Prompt optimization — temperature routing, CoT/Step-Back, few-shot tuning
- Eval frameworks — golden test suites, decision logging, accuracy tracking
- PM signal aggregation — email, Teams, ADO, GitHub → daily intelligence brief
- Developer platform strategy — Add-in lifecycle, Copilot extensibility, DLP integrations

---

### 🧠 How I Think About AI Systems

```
Issue arrives
    │
    ├─ Rules-first pass (keyword matching, YAML config)
    │   └─ 60% classified → zero latency, zero cost
    │
    ├─ LLM pass (few-shot, low temperature)
    │   └─ 35% classified → handles ambiguity
    │
    ├─ Urgency scoring (regression signals, escalation patterns)
    │
    ├─ Sentiment analysis (frustrated → neutral → positive)
    │
    └─ Decision logged → JSONL audit trail → tune rules over time
```

**Rules first. LLM second. Eval always.**

---

### 📸 Visual Proof

<table>
  <tr>
    <td align="center">
      <a href="https://kustonaut.github.io/brain-os">
        <img src="https://raw.githubusercontent.com/kustonaut/brain-os/main/docs/readme-hero.svg" width="400" alt="Brain OS — AI-powered PM operating system" />
      </a>
      <br /><strong>Brain OS</strong> — Daily intelligence pipeline
    </td>
    <td align="center">
      <a href="https://kustonaut.github.io/brain-os">
        <img src="https://raw.githubusercontent.com/kustonaut/brain-os/main/docs/readme-pipeline.svg" width="400" alt="Brain OS Pipeline — 9 automated steps" />
      </a>
      <br /><strong>Pipeline</strong> — 9 automated steps, zero manual effort
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://kustonaut.github.io/brain-os">
        <img src="https://raw.githubusercontent.com/kustonaut/brain-os/main/docs/readme-skills.svg" width="400" alt="22 Copilot Skills" />
      </a>
      <br /><strong>22 Skills</strong> — Morning OS, career coach, incident investigator
    </td>
    <td align="center">
      <a href="https://kustonaut.github.io/brain-os">
        <img src="https://raw.githubusercontent.com/kustonaut/brain-os/main/docs/arch-system-overview.svg" width="400" alt="System Architecture" />
      </a>
      <br /><strong>Architecture</strong> — Rules-first → LLM → eval loop
    </td>
  </tr>
</table>

> 🎮 **Live demos:** [Brain OS](https://kustonaut.github.io/brain-os) · [Issue Sentinel](https://kustonaut.github.io/issue-sentinel) · [GitHub Issue Analytics](https://kustonaut.github.io/github-issue-analytics)

---

### 📊 By the Numbers

| | |
|---|---|
| 🏢 **Microsoft** | 11+ years — Consulting → Azure Data Explorer → Excel Product Group |
| 📊 **Data scale** | 350 PB/day (1P connectors), 20x OSS growth (40 PB/day) |
| 🎯 **Issues triaged** | 6,000+ across 5 charter areas |
| 🤖 **Copilot skills** | 22 production-grade PM skills |
| ⚙️ **Automations** | 50+ daily pipeline scripts |
| ⭐ **365daysofADX** | 37 stars — 365-day public KQL challenge |
| 🧪 **Test coverage** | 23/23 tests passing across all repos |

