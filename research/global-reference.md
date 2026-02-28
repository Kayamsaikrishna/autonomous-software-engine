# Global Reference: Industries, Startups & Research Papers
## AI-Powered Autonomous Software Engineering — End-to-End Cross-Platform Build

> A comprehensive, curated global directory of every major player, institution, and research body
> working on problems directly related to my project. All links are verified and current as of early 2026.

---

## HOW TO USE THIS DOCUMENT

This document is organized into **5 major sections**:

1. **Tier 1 Startups** — Companies building autonomous AI software engineers (closest to my vision)
2. **Tier 2 Startups** — Companies building AI coding assistants and app builders (adjacent space)
3. **Big Tech Initiatives** — What the giants are doing in this space
4. **Global Research Labs & Universities** — Academic institutions actively publishing on this
5. **Key Research Papers** — Essential papers organized by sub-topic

Each entry includes: Country, Website, Focus area, Funding, and relevance to your specific project.

---

# SECTION 1: TIER 1 STARTUPS
### These are building autonomous end-to-end software engineering agents — the closest to what I want to build

---

## 🇺🇸 United States

### 1. Cognition AI (Devin)
- **Website:** https://cognition.ai
- **Founded:** 2023
- **Country:** USA (San Francisco, CA)
- **Focus:** World's first autonomous AI software engineer — Devin can plan, write, test, debug, and deploy code end-to-end in a sandboxed environment with shell, editor, and browser
- **Funding:** $10.2B valuation (Series C, 2025), $400M Series C led by Founders Fund; acquired Windsurf (IDE) in July 2025
- **ARR Growth:** $1M (Sept 2024) → $73M (June 2025) → $150M+ combined post-Windsurf acquisition
- **Key Investors:** Founders Fund, Peter Thiel, Elad Gil, Tony Xu
- **Why Relevant:** The primary reference point for autonomous software engineering. Their architecture — sandboxed environment, long-horizon reasoning, multi-agent (MultiDevin) — is the closest commercial implementation of what I am researching.
- **Benchmark:** 13.86% on SWE-bench (resolved real GitHub issues end-to-end)
- **Blog/Announcements:** https://cognition.ai/blog/introducing-devin
- **Further Reading:** https://cognition.ai/blog/funding-growth-and-the-next-frontier-of-ai-coding-agents

---

### 2. Anysphere (Cursor)
- **Website:** https://cursor.sh
- **Founded:** 2022 (MIT alumni team)
- **Country:** USA (San Francisco, CA)
- **Focus:** AI-first IDE built on VS Code — multi-file editing, natural language commands, codebase-aware AI, agentic coding
- **Funding:** $9.9B valuation (June 2025); $100M Series B at $2.6B (2024); $60M Series A at $400M (Aug 2024)
- **ARR:** $100M+ ARR (April 2025); 40,000+ developers
- **Why Relevant:** The leading AI IDE. My system will need IDE integration as a product layer. Cursor's architecture for multi-file context and repo-wide understanding is directly relevant to my HAB (Hierarchical Architecture Blueprint) problem.
- **Key Insight:** Cursor shows that developers pay for intelligent code context — not just autocomplete

---

### 3. Factory AI
- **Website:** https://factory.ai
- **Founded:** 2023
- **Country:** USA
- **Focus:** "Agent-Native Software Development" — AI droids (agents) that automate coding, testing, and deployment for startups and enterprises; integrates with version control and issue trackers
- **Funding:** $15M Series A led by Sequoia (June 2024); total ~$20M; valued at $120M
- **ARR:** $129M (2025)
- **Why Relevant:** Factory's agents handle the full software delivery lifecycle — picking up tasks from issue trackers, writing code, opening PRs, handling review feedback. Closest to a production-grade agentic pipeline for enterprise software.
- **SWE-bench Score:** ~19% (June 2024) — higher than many baseline models
- **Source:** https://research.contrary.com/company/cognition

---

### 4. Magic.dev
- **Website:** https://magic.dev
- **Founded:** 2022
- **Country:** USA (San Francisco, CA)
- **Focus:** Building long-context code generation models — their LTM-2-mini model can process 10 million lines of code (equivalent to 750 novels). Built for fully automated software development.
- **Funding:** $465M total; $320M round led by Eric Schmidt (former Google CEO) in Aug 2024
- **Key Investors:** Eric Schmidt, Sequoia, Atlassian, Elad Gil, Jane Street, Nat Friedman, Daniel Gross
- **Partnership:** Google Cloud — building "supercomputers" on GCP
- **Why Relevant:** Magic is solving the context window problem — the core architectural challenge in my HAB system. Their approach to processing entire large codebases is directly relevant to my "coherent architecture generation at scale" research problem.
- **Source:** https://techcrunch.com/2024/08/29/generative-ai-coding-startup-magic-lands-320m-investment-from-eric-schmidt-atlassian-and-others/

---

### 5. Poolside AI
- **Website:** https://poolside.ai
- **Founded:** 2023 (by Jason Warner, former CTO of GitHub, and Eiso Kant)
- **Country:** USA & France (Paris/San Francisco)
- **Focus:** Building foundation models specifically for software development; trains models not just on code but on enterprise business data and software engineering processes
- **Funding:** $626M total; $500M Series B led by Bain Capital Ventures (Oct 2024); $3B valuation
- **Key Investors:** Bain Capital, Nvidia, eBay Ventures, DST Global, Citi Ventures, HSBC Ventures, Capital One Ventures
- **ARR:** $50M (2025)
- **Why Relevant:** Poolside's philosophy that "software development should take place outside the editor" and their focus on training models on enterprise business context (not just code) is directly relevant to my Specification Engine design. Their Global 2000 customer focus also validates the enterprise market.
- **Source:** https://techcrunch.com/2024/10/02/ai-coding-startup-poolside-raises-500m-from-ebay-nvidia-and-others/

---

### 6. Augment Code
- **Website:** https://augmentcode.com
- **Founded:** 2024
- **Country:** USA
- **Focus:** AI tools for large enterprise codebases — multiple developers collaborating on complex code with IP protection and enterprise security standards
- **Funding:** $252M total; $227M Series B (April 2024); $977M valuation
- **Key Investors:** Sutter Hill Ventures, Index Ventures, Innovation Endeavors, Lightspeed, Meritech Capital, Eric Schmidt
- **Why Relevant:** Augment specifically targets large, complex codebases — the exact problem space my HAB and multi-file coherence research addresses. Their IP protection approach is relevant to my distribution layer design.

---

### 7. Windsurf (formerly Codeium)
- **Website:** https://windsurf.com
- **Founded:** 2021 (rebranded Dec 2024)
- **Country:** USA (Mountain View, CA)
- **Focus:** AI coding assistant (IDE + agent); Gartner named them Leader in AI Coding Assistants 2025
- **Funding:** $150M Series C led by General Catalyst (Aug 2024); $1.25B valuation
- **Key Event:** Acquired by Cognition AI in July 2025 for ~$82M ARR
- **Why Relevant:** Windsurf's transition from coding assistant to agentic IDE demonstrates the product evolution path. Their acquisition by Cognition shows how the market is consolidating around full-stack autonomous engineering.

---

### 8. Graphite
- **Website:** https://graphite.dev
- **Founded:** 2020
- **Country:** USA (New York, NY)
- **Focus:** AI-powered code review — automates feedback, summarizes pull requests, suggests improvements, self-heals CI failures
- **Funding:** $81M total; $52M Series B (March 2025)
- **Users:** Tens of thousands of engineers at Shopify, Snowflake, Figma
- **ARR Growth:** Revenue grew 20x in 2024
- **Why Relevant:** Graphite focuses specifically on the verification and review layer of the software pipeline — directly relevant to my verification engine design, particularly the feedback signal problem.

---

### 9. Replit
- **Website:** https://replit.com
- **Founded:** 2016
- **Country:** USA (San Francisco, CA)
- **Focus:** Cloud-based collaborative coding with AI Agent (Agent 3) that builds full applications from natural language descriptions, sets up databases, integrates APIs
- **Funding:** Well-funded; ARR grew from $10M to $100M in 9 months after Agent launch
- **Notable:** Agent 3 includes self-testing — the AI interacts with the app like a user, clicks around, finds bugs, and fixes them automatically
- **Why Relevant:** Replit's self-testing feature is a prototype of my verification layer. Their multi-language, 50+ language support and full deployment pipeline is relevant to my multi-platform distribution layer.
- **Source:** https://prismic.io/blog/ai-code-generators

---

### 10. Lovable (formerly GPT Engineer)
- **Website:** https://lovable.dev
- **Founded:** 2023
- **Country:** Sweden 🇸🇪 (Stockholm) — notable as a non-US leader
- **Focus:** Natural language to full-stack web app — React/Tailwind frontend + Supabase backend, targeted at non-technical users
- **Funding:** Significant VC; $100M ARR in 8 months (potentially fastest-growing startup in history by this metric)
- **ARR:** $200M (2025)
- **Why Relevant:** Lovable proves massive market demand for natural language → working software. Their architecture (conversation → spec → code → deploy in one pipeline) is a simplified version of my full vision. Study their failure modes (security issues, code quality degradation after 50+ prompts) — these are exactly the problems my verification layer must solve.

---

## 🇫🇷 France

### 11. Poolside AI (European Operations)
- Already listed above — notable as having French roots and European HQ alongside San Francisco presence

---

## 🇸🇪 Sweden

### 12. Lovable
- Already listed above — Swedish-founded, globally operating

---

# SECTION 2: TIER 2 STARTUPS
### AI app builders, coding assistants, and platform tools — adjacent market that informs my product design

---

| Company | Country | Website | Focus | Funding | Relevance |
|---|---|---|---|---|---|
| **Bolt.new (StackBlitz)** | 🇺🇸 USA | https://bolt.new | Browser-based full-stack app builder using Claude; fastest prototype-to-URL | Well-funded | Fastest time-to-prototype benchmark; understand their WebContainer tech |
| **v0 by Vercel** | 🇺🇸 USA | https://v0.dev | React component and Next.js app generation; highest code quality in category | Vercel-backed | Frontend generation quality benchmark |
| **GitHub Copilot** | 🇺🇸 USA | https://github.com/features/copilot | Pioneered AI coding assistance; 1.3M+ paid subscribers; 40% revenue growth | Microsoft | The market validation that proved developer willingness to pay |
| **Tabnine** | 🇮🇱 Israel | https://tabnine.com | AI code completion with privacy focus; enterprise; runs locally | $47M+ | Enterprise AI coding with on-premise deployment model |
| **Sourcegraph (Cody)** | 🇺🇸 USA | https://sourcegraph.com | Codebase search + AI assistant; strong on large, legacy codebases | $225M | Large codebase navigation — relevant to my context retrieval problem |
| **Aider** | 🇺🇸 USA | https://aider.chat | Open-source AI pair programming in the terminal; multi-file editing | Open source | Most hackable agent framework; good for understanding agentic loops |
| **Continue.dev** | 🇺🇸 USA | https://continue.dev | Open-source AI coding assistant for VS Code and JetBrains | Open source | Useful reference for IDE integration design |
| **Sweep AI** | 🇺🇸 USA | https://sweep.dev | AI that converts GitHub issues to pull requests autonomously | $2.5M seed | Direct ancestor of my verification-to-correction loop |
| **Kodiak (formerly Robinhood)** | 🇺🇸 USA | - | Automated PR merging with CI/CD intelligence | Internal | Automated merge pipeline reference |
| **DevRev** | 🇺🇸 USA | https://devrev.ai | AI-native business OS (AgentOS) unifying support, product, and engineering | $186M; $1.15B valuation | Founded by Dheeraj Pandey (Nutanix founder); AI-native dev workflow |
| **Bubble** | 🇺🇸 USA | https://bubble.io | No-code visual builder with AI app generator | $100M+ | Non-technical user base; understanding user mental models |
| **Base44** | 🇮🇱 Israel | https://base44.com | Enterprise-focused app builder; strong governance and security | Series A | Enterprise cross-platform with compliance |
| **Tempo Labs** | 🇺🇸 USA | https://tempolabs.ai | React-specialized AI app builder | Seed | React generation quality reference |

---

# SECTION 3: BIG TECH INITIATIVES
### Understanding what the giants are building tells me where the competitive moat must be

---

### Microsoft / GitHub
- **GitHub Copilot:** https://github.com/features/copilot — the market pioneer; 1.3M paid subscribers as of 2024
- **Copilot Workspace:** https://githubnext.com/projects/copilot-workspace — end-to-end agentic development environment; takes GitHub issues and builds features autonomously
- **GitHub Spark:** https://githubnext.com/projects/github-spark — natural language micro-app builder
- **Why Watch:** Microsoft's distribution advantage (GitHub = 100M+ developers) and deep Azure integration mean any cross-platform tool must have a GitHub-native workflow

### Google / DeepMind
- **AlphaCode 2:** https://deepmind.google/discover/blog/alphacode-2-competitive-programming/ — competition-level code generation at 85th percentile of human programmers
- **Gemini Code Assist:** https://cloud.google.com/products/gemini/code-assist — enterprise AI coding for Google Cloud
- **Firebase Studio (Project IDX):** https://idx.dev — browser-based AI development environment for full-stack and multiplatform apps; specifically targets Flutter and cross-platform mobile
- **Antigravity:** Google's dedicated IDE for autonomous agents (announced 2025)
- **Why Watch:** Firebase Studio's explicit cross-platform and Flutter focus is the closest big-tech equivalent to my vision

### Amazon / AWS
- **Amazon Q Developer:** https://aws.amazon.com/q/developer/ — AI coding assistant integrated into AWS; includes Amazon Transform for large-scale legacy code migration
- **CodeWhisperer:** Now part of Amazon Q
- **Why Watch:** Amazon Transform's automated migration capability is the enterprise-scale version of my system's code modernization use case

### Meta / FAIR
- **Code Llama:** https://ai.meta.com/blog/code-llama-large-language-model-for-coding/ — open-source code generation models; 7B to 70B parameters; state of the art open-source as of 2024
- **SWE-bench collaboration:** Meta (UCSB collaboration) produced PatchPilot with 64.6% SWE-bench Verified score (May 2025)
- **Why Watch:** Code Llama is the open-source foundation I may train my own models on top of

### Apple
- **Xcode Intelligence:** Apple's integrated AI for Xcode — Swift code completion, documentation generation
- **Why Watch:** Any iOS/macOS generation tool must understand Apple's toolchain constraints and approval processes; Apple's restrictions affect my distribution layer significantly

### JetBrains
- **AI Assistant:** https://www.jetbrains.com/ai/ — IDE-integrated AI across all JetBrains IDEs (IntelliJ, PyCharm, etc.)
- **DPAI Arena:** Developer Productivity AI Arena — launched Oct 2025, benchmarks coding agents across multiple languages and frameworks
- **Why Watch:** JetBrains' DPAI Arena is a new benchmark standard that may replace SWE-bench for enterprise metrics

### ByteDance
- **TRAE:** ByteDance's coding agent achieved 75.2% on SWE-bench Verified (2025) — among the highest recorded scores
- **Why Watch:** Chinese tech giants are making rapid advances; TRAE is a direct competitor at the frontier

---

# SECTION 4: GLOBAL RESEARCH LABS & UNIVERSITIES
### Academic institutions publishing cutting-edge research directly relevant to your project

---

## 🇺🇸 United States

### Princeton University — NLP Group
- **Website:** https://nlp.cs.princeton.edu
- **Key Lab:** Princeton NLP
- **Key Researchers:** Karthik Narasimhan, Carlos E. Jimenez, John Yang, Ofir Press
- **What They Built:** SWE-bench (the primary benchmark for autonomous software engineering) and SWE-agent (open-source autonomous coding agent, NeurIPS 2024)
- **GitHub:** https://github.com/SWE-bench/SWE-bench, https://github.com/SWE-agent/SWE-agent
- **Why Critical:** SWE-bench is the standard I will use to evaluate my system. Understanding its design is essential.

### MIT — CSAIL (Computer Science and Artificial Intelligence Laboratory)
- **Website:** https://www.csail.mit.edu
- **Key Researchers:** Armando Solar-Lezama (program synthesis), Alex Gu
- **Recent Paper:** "Challenges and Paths Towards AI for Software Engineering" (ICML 2025) — maps all current bottlenecks in autonomous software engineering
- **MIT News Article:** https://news.mit.edu/2025/can-ai-really-code-study-maps-roadblocks-to-autonomous-software-engineering-0716
- **Why Critical:** Solar-Lezama is one of the world's foremost experts on program synthesis — the academic foundation of your project. His lab's roadmap paper is essential reading.

### Stanford University
- **SAIL (Stanford AI Lab):** https://ai.stanford.edu
- **HAI (Human-Centered AI):** https://hai.stanford.edu
- **Software Engineering Productivity Research Group:** https://softwareengineeringproductivity.stanford.edu/ai-impact
- **Key Researchers:** Diyi Yang (collaborated on SWE-bench and MIT paper), Kevin Ellis (program synthesis, Cornell)
- **Stanford AI Coding Course:** "The Modern Software Developer" — first university AI coding course
- **Why Critical:** Stanford's direct pipeline into Silicon Valley means research here becomes products within 12–24 months

### Carnegie Mellon University (CMU)
- **SEI (Software Engineering Institute):** https://www.sei.cmu.edu/ai-augmented-software-engineering/
- **Focus:** AI-augmented software engineering for defense and enterprise; formal methods; code translation workflows
- **Notable Work:** Ada to C++ automated translation; automated refactoring for large-scale legacy modernization
- **Why Critical:** CMU SEI is the gold standard for production-grade software engineering research. Their work on formal verification and AI augmentation is directly relevant to my verification layer.

### UC Berkeley — BAIR (Berkeley AI Research)
- **Website:** https://bair.berkeley.edu
- **Key Researchers:** Koushik Sen (collaborated on MIT/SWE paper), Naman Jain, Manish Shetty
- **Focus:** Reinforcement learning, program analysis, fuzzing (relevant to your property-based verification)
- **Why Critical:** Berkeley's fuzzing research directly informs my verification layer design

### University of Illinois Urbana-Champaign (UIUC)
- **Focus:** Programming languages, compilers, static analysis
- **Notable:** Strong track record in formal verification and automated program repair

---

## 🇬🇧 United Kingdom

### University of Cambridge — Machine Learning Group
- **Website:** https://mlg.eng.cam.ac.uk
- **Focus:** Statistical machine learning; probabilistic programming
- **Why Relevant:** Program synthesis with probabilistic models

### University College London (UCL)
- **Key Researcher:** Mark Harman (Meta/UCL) — search-based software engineering, automated test generation
- **Focus:** SBSE (Search-Based Software Engineering) — using evolutionary algorithms for software automation
- **Why Relevant:** Harman's work on automated test generation is the academic foundation for my test synthesis layer

### University of Edinburgh
- **Focus:** Functional programming, type systems, formal verification
- **Why Relevant:** Type-directed program synthesis research

---

## 🇩🇪 Germany / 🇦🇹 Austria / 🇨🇭 Switzerland

### ETH Zurich
- **AI Center:** https://ai.ethz.ch
- **Key Researchers:** Thomas Hofmann (ML, code), Andreas Krause (learning algorithms)
- **Focus:** AI for software, safety verification, formal methods
- **Why Relevant:** ETH Zurich's formal methods and safety verification research directly informs my cross-platform correctness verification problem

### GENIUS Project (European Consortium)
- **Paper:** "The Future of Generative AI in Software Engineering" (2025)
- **Link:** https://arxiv.org/html/2511.01348v2
- **Countries:** Germany (BMFTR-funded), Austria (FFG-funded)
- **Focus:** GenAI across the entire software development lifecycle; long-term industry metrics
- **Why Relevant:** Multi-year, multi-country study of GenAI's real impact on software delivery — rare longitudinal data

---

## 🇫🇷 France

### INRIA
- **Website:** https://www.inria.fr
- **Focus:** Formal verification, programming languages, distributed systems
- **Why Relevant:** INRIA has decades of work on formal specification and program correctness that pre-dates LLMs — useful foundation

---

## 🇨🇳 China

### Tsinghua University
- **Focus:** Code intelligence, LLMs for SE, CodeBERT successors
- **Notable Work:** CodeBERT, GraphCodeBERT — influential code understanding models
- **Why Relevant:** Chinese universities are producing state-of-the-art code LLMs at scale

### Peking University (PKU)
- **Focus:** Software engineering automation, LLM applications

### Fudan University
- **Key Lab:** FudanSELab
- **GitHub Repository:** https://github.com/FudanSELab/Agent4SE-Paper-List — maintains comprehensive list of agent-based software engineering papers
- **Why Critical:** The best curated bibliography of LLM-for-software-engineering research. Bookmark this.

### DeepSeek (Research Lab + Company)
- **Website:** https://deepseek.com
- **Focus:** Open-source code LLMs; DeepSeek Coder achieves near-state-of-the-art on code benchmarks
- **Why Relevant:** DeepSeek Coder V2 is a leading open-source option for my code generation backbone

### ByteDance Research
- **TRAE Agent:** 75.2% SWE-bench Verified score (2025 leader)
- **Focus:** Reinforcement learning for code agents; long-horizon software tasks

---

## 🇯🇵 Japan

### RIKEN Center for Advanced Intelligence Project (AIP)
- **Website:** https://aip.riken.jp
- **Focus:** Machine learning, natural language processing for software
- **Why Relevant:** Growing Japanese research output in code intelligence

### NTT Research / NTT Data
- **Focus:** Enterprise software automation; Japanese enterprise software market

---

## 🇰🇷 South Korea

### KAIST (Korea Advanced Institute of Science and Technology)
- **Focus:** Programming languages, formal verification, AI for SE

### Samsung Research
- **Focus:** On-device AI coding; mobile development automation (directly relevant to Android/cross-platform work)

---

## 🇸🇬 Singapore

### National University of Singapore (NUS)
- **Focus:** Efficient AI systems, large-scale deployment
- **Why Relevant:** Strong applied AI research with industry partnerships

### Nanyang Technological University (NTU)
- **Focus:** AI for software, smart systems

---

## 🇮🇳 India

### IIT Bombay / IIT Delhi / IIT Madras
- **Focus:** Program analysis, formal methods, software testing automation
- **Why Relevant:** Growing research output; India is emerging as a significant research contributor to this space

---

# SECTION 5: KEY RESEARCH PAPERS
### Organized by sub-topic — each with exact link for access

---

## 5.1 — Benchmarks (Know How My System Will Be Evaluated)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **SWE-bench: Can Language Models Resolve Real-world GitHub Issues?** | Jimenez, Yang, et al. (Princeton) | 2024 | ICLR 2024 (Oral) | https://arxiv.org/abs/2310.06770 | **The primary benchmark.** Read this first. |
| **SWE-bench Verified** | Princeton NLP + OpenAI | 2024 | OpenAI Blog | https://openai.com/index/introducing-swe-bench-verified/ | More reliable subset — verified by human engineers |
| **SWE-bench Multimodal** | Yang, Jimenez et al. | 2025 | ICLR 2025 | https://openreview.net/forum?id=riTiq3i21b | Extends benchmark to visual/UI domains |
| **SWE-bench Pro: Can AI Agents Solve Long-Horizon Tasks?** | Deng et al. | 2025 | arXiv | https://arxiv.org/abs/2509.16941 | Enterprise-grade benchmark — 1,865 problems from 41 repos |
| **HumanEval: Evaluating Large Language Models Trained on Code** | Chen et al. (OpenAI) | 2021 | arXiv | https://arxiv.org/abs/2107.03374 | The original code generation benchmark — still widely used |
| **MBPP: Program Synthesis with Large Language Models** | Austin et al. (Google) | 2021 | arXiv | https://arxiv.org/abs/2108.07732 | Beginner Python problems benchmark |

---

## 5.2 — Autonomous Software Engineering Agents (Core Research)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering** | Yang, Jimenez et al. (Princeton/Stanford) | 2024 | NeurIPS 2024 | https://arxiv.org/abs/2405.15793 | Open-source autonomous software agent — the academic counterpart to Devin |
| **Agentless: Demystifying LLM-based Software Engineering Agents** | Xia et al. | 2024 | arXiv | https://arxiv.org/abs/2407.01489 | Shows that simple, agent-free approaches can match complex agent systems — key insight for your verification layer |
| **Challenges and Paths Towards AI for Software Engineering** | Gu, Solar-Lezama et al. (MIT/Berkeley/Stanford) | 2025 | ICML 2025 | https://news.mit.edu/2025/can-ai-really-code-study-maps-roadblocks-to-autonomous-software-engineering-0716 | **Essential.** Maps every roadblock in autonomous SE. My research framing should cite this. |
| **ChatDev: Communicative Agents for Software Development** | Qian et al. | 2023 | ACL 2024 | https://arxiv.org/abs/2307.07924 | Multi-agent "software company" simulation — CEO, CTO, programmer agents |
| **MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework** | Hong et al. | 2023 | ICLR 2024 | https://arxiv.org/abs/2308.00352 | Agents take on human software team roles; generates structured artifacts |
| **CodeAct: Executable Code Actions Elicit Better LLM Agents** | Wang et al. | 2024 | ICML 2024 | https://arxiv.org/abs/2402.01030 | All agent actions represented as executable code — simplifies agent architecture |
| **Reflexion: Language Agents with Verbal Reinforcement Learning** | Shinn et al. | 2023 | NeurIPS 2023 | https://arxiv.org/abs/2303.11366 | Agents learn from failure through verbal self-reflection — directly relevant to my correction loop |
| **ReAct: Synergizing Reasoning and Acting in Language Models** | Yao et al. | 2022 | ICLR 2023 | https://arxiv.org/abs/2210.03629 | Foundation of modern agentic systems — reasoning + action interleaved |
| **A Survey on Code Generation with LLM-based Agents** | (Multi-institution) | 2025 | arXiv | https://arxiv.org/abs/2508.00083 | Comprehensive survey of 100+ papers on LLM-based code generation agents |
| **AI Agentic Programming: A Survey of Techniques, Challenges, and Opportunities** | (Multi-institution) | 2025 | arXiv | https://arxiv.org/abs/2508.11126 | 152 papers reviewed; maps the complete design space of agentic programming |

---

## 5.3 — Code Generation Models (Foundation Models)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **Competition-Level Code Generation with AlphaCode** | Li et al. (DeepMind) | 2022 | Science | https://www.science.org/doi/10.1126/science.abq1158 | First system to reach average human performance in competitive programming |
| **AlphaCode 2** | DeepMind | 2023 | DeepMind Blog | https://deepmind.google/discover/blog/alphacode-2-competitive-programming/ | 85th percentile performance — human expert level |
| **StarCoder: May the Source Be With You** | Li et al. (BigCode) | 2023 | arXiv | https://arxiv.org/abs/2305.06161 | Open-source code model trained on The Stack; widely used as baseline |
| **Code Llama: Open Foundation Models for Code** | Rozière et al. (Meta) | 2023 | arXiv | https://arxiv.org/abs/2308.12950 | Meta's open-source code LLM; fine-tuned on code from Llama 2 |
| **DeepSeek-Coder: When the LLM Meets Programming** | Guo et al. (DeepSeek) | 2024 | arXiv | https://arxiv.org/abs/2401.14196 | Near SOTA open-source code model; practical backbone for your system |
| **CodeT5+: Open Code Large Language Models** | Wang et al. | 2023 | EMNLP 2023 | https://arxiv.org/abs/2305.07922 | Encoder-decoder model; strong for code understanding + generation |

---

## 5.4 — Multi-Agent Systems for Software (Team-Based Approaches)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **AgentCoder: Multi-Agent Code Generation with Iterative Testing** | Huang et al. | 2023 | arXiv | https://arxiv.org/abs/2312.13010 | Multi-agent system with programmer + tester + executor agents; 77.4% on HumanEval-ET |
| **MapCoder: Multi-Agent Code Generation for Competitive Problem Solving** | Islam et al. (BUET) | 2024 | ACL 2024 | https://aclanthology.org/2024.acl-long.269 | Retrieval + planning + coding + debugging agents; competitive problem solving |
| **AgileCoder: Dynamic Collaborative Agents Based on Agile Methodology** | Nguyen et al. | 2024 | arXiv | https://arxiv.org/abs/2406.11912 | Applies Agile software methodology to multi-agent code generation |
| **Multi-Agent Software Development through Cross-Team Collaboration** | Du et al. | 2024 | arXiv | https://arxiv.org/abs/2406.08979 | Multiple agent teams collaborating — relevant to my multi-agent architecture |
| **CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems** | Zhang et al. | 2024 | ACL 2024 | https://arxiv.org/abs/2401.07339 | Adds file system, web search, code execution as agent tools for repo-level coding |

---

## 5.5 — Specification and Requirements Engineering (My Spec Engine)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **SpecGen: Automated Generation of Formal Program Specifications via LLMs** | Ma et al. | 2024 | arXiv | https://arxiv.org/abs/2401.08807 | Directly relevant — AI generating formal specs from natural language |
| **Large Language Models Based Automatic Synthesis of Software Specifications** | (Multi) | 2023 | arXiv | https://arxiv.org/abs/2304.01997 | Foundational work on LLMs for spec synthesis |
| **Impact of LLMs on Generating Software Specifications** | (Multi) | 2023 | arXiv | https://arxiv.org/abs/2306.03324 | Empirical study of LLM quality for spec generation |
| **Advancing Requirements Engineering through Generative AI** | Arora et al. | 2023 | arXiv | https://arxiv.org/abs/2310.13976 | Survey of GenAI's role in requirements engineering |
| **Natural Language Processing-based Requirements Modeling** | (Multi) | 2023 | APSEC 2023 | — | NLP for requirements to formal models |
| **ClarifyGPT: Empowering LLM Code Generation with Intention Clarification** | Mu et al. | 2023 | arXiv | https://arxiv.org/abs/2310.10996 | System that asks clarifying questions to reduce ambiguity — directly relevant to my Spec Engine design |

---

## 5.6 — Automated Program Repair (My Correction Loop)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **A Survey of LLM-based Automated Program Repair** | (Multi) | 2025 | arXiv | https://arxiv.org/abs/2506.23749 | Comprehensive survey covering fine-tuning, prompting, procedural pipelines, and agentic frameworks for APR |
| **AlphaRepair: Automated Program Repair in the Wild** | Xia & Zhang | 2023 | ISSTA 2023 | https://arxiv.org/abs/2301.04072 | Fill-in-middle approach to automated repair |
| **CYCLE: Self-Refining Code Generation** | (Multi) | 2023 | arXiv | — | Self-refinement through execution feedback — 63.5% improvement over baselines |
| **Agentless: Demystifying Software Engineering Agents** | Xia et al. | 2024 | arXiv | https://arxiv.org/abs/2407.01489 | Counter-argument: simple localize-then-repair can match complex agents |

---

## 5.7 — Repository-Level Code Generation (Large Codebase Problem)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **Retrieval-Augmented Code Generation: A Survey** | (Multi) | 2025 | arXiv | https://arxiv.org/abs/2510.04905 | Survey of RAG for repository-scale code generation — my platform knowledge RAG system |
| **CrossCodeEval: Cross-File Code Completion Benchmark** | Ding et al. | 2023 | NeurIPS 2023 | https://arxiv.org/abs/2310.11248 | Benchmark for cross-file code understanding — relevant to my multi-file coherence problem |
| **RepoBench: Repository-Level Code Auto-Completion** | Liu et al. | 2023 | ICLR 2024 | https://arxiv.org/abs/2306.03091 | Benchmark for repo-level code completion |
| **CodePlan: Repository-level Coding using LLMs** | Bairi et al. | 2023 | arXiv | https://arxiv.org/abs/2309.12499 | Planning approach to multi-file, repository-level changes |

---

## 5.8 — Testing and Verification (My Verification Layer)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **QuickCheck: A Lightweight Tool for Random Testing of Haskell Programs** | Claessen & Hughes | 2000 | ICFP 2000 | https://dl.acm.org/doi/10.1145/351240.351266 | Foundational property-based testing paper — theory behind my test generation |
| **DeepSmith: Compiler Fuzzing through Deep Learning** | Cummins et al. | 2018 | ISSTA 2018 | https://arxiv.org/abs/1806.07736 | Using ML to generate adversarial inputs for compilers — relevant to cross-platform testing |
| **CodeT: Code Generation with Generated Tests** | Chen et al. | 2022 | arXiv | https://arxiv.org/abs/2207.10397 | Generate code AND tests simultaneously, use tests to select best code — directly relevant |
| **INTERVENOR: Interactive Chain of Repair** | Wang et al. | 2023 | ACL 2024 | https://arxiv.org/abs/2311.09868 | Interactive code repair through execution feedback loop |
| **LLM4TDD: Test Driven Development Using LLMs** | Piya et al. | 2023 | arXiv | https://arxiv.org/abs/2312.04687 | LLMs for test-driven development — write tests first, then implementation |

---

## 5.9 — Program Synthesis (Deep Theory)

| Paper | Authors | Year | Venue | Link | Why It Matters |
|---|---|---|---|---|---|
| **Program Synthesis** | Solar-Lezama | 2008+ | MIT Survey | https://people.csail.mit.edu/asolar/ | The foundational academic survey on program synthesis |
| **Alloy: A Lightweight Object Modelling Notation** | Jackson | 2002 | ACM TOSEM | https://dl.acm.org/doi/10.1145/505145.505149 | Foundational formal specification language — informs my spec DSL design |
| **Neural Program Synthesis from Diverse Demonstration Sets** | Parisotto et al. | 2016 | arXiv | https://arxiv.org/abs/1611.01855 | Early neural program synthesis |
| **FlashMeta: A Framework for Inductive Program Synthesis** | Polozov & Gulwani | 2015 | OOPSLA 2015 | https://dl.acm.org/doi/10.1145/2814270.2814310 | Microsoft's FlashFill/FlashExtract foundation — synthesis from examples |

---

## 5.10 — Comprehensive Surveys (Read These for Orientation)

| Paper | Authors | Year | Venue | Link | Pages |
|---|---|---|---|---|---|
| **Large Language Models for Software Engineering: A Systematic Literature Review** | Hou et al. | 2024 | ACM TOSEM | https://arxiv.org/abs/2308.10620 | 273+ papers reviewed |
| **A Survey on Large Language Models for Code Generation** | (Multi) | 2025 | arXiv | https://arxiv.org/abs/2503.01245 | Comprehensive; covers challenges, techniques, evaluation, applications |
| **A Survey on Code Generation with LLM-based Agents** | (Multi) | 2025 | arXiv | https://arxiv.org/abs/2508.00083 | 100+ papers; covers planning, tool use, environment interaction |
| **LLM-Based Agents for Software Engineering: A Survey** | (FudanSELab) | 2024 | SCIS 2025 | https://github.com/FudanSELab/Agent4SE-Paper-List | The most comprehensive living bibliography |
| **The Future of Generative AI in Software Engineering (GENIUS Project)** | European Consortium | 2025 | arXiv | https://arxiv.org/abs/2511.01348 | Industry + academia; longitudinal data on GenAI impact |
| **AI-Driven Innovations in Software Engineering** | (Multi) | 2025 | MDPI Applied Sciences | https://www.mdpi.com/2076-3417/15/3/1344 | Practical review for practitioners; covers full SDLC |

---

# SECTION 6: BENCHMARKS & EVALUATION INFRASTRUCTURE
### Tools to measure whether my system is actually working

| Benchmark | Link | What It Measures | Why Use It |
|---|---|---|---|
| **SWE-bench** | https://www.swebench.com | Resolving real GitHub issues end-to-end | Primary benchmark for autonomous SE |
| **SWE-bench Lite** | https://github.com/SWE-bench/SWE-bench | 300 verified tasks subset | Faster iteration during development |
| **SWE-bench Verified** | https://openai.com/index/introducing-swe-bench-verified/ | 500 human-verified solvable tasks | Most reliable SWE-bench variant |
| **SWE-bench Pro** | https://arxiv.org/abs/2509.16941 | Enterprise-level, long-horizon tasks | Tests my system against real enterprise complexity |
| **HumanEval** | https://github.com/openai/human-eval | Function-level Python code generation | Baseline code generation quality |
| **MBPP** | https://github.com/google-research/google-research/tree/master/mbpp | Beginner-level Python programming | Code generation across difficulty levels |
| **LiveCodeBench** | https://livecodebench.github.io | Continuously updated programming challenges | Avoids benchmark contamination |
| **DPAI Arena (JetBrains)** | https://dpai.jetbrains.com | Multi-language, multi-workflow developer productivity | Enterprise-focused comprehensive evaluation |
| **Terminal-Bench** | (Stanford/Laude Institute, May 2025) | Command-line environment agent tasks | Multi-step CLI workflows |
| **SWE-PolyBench (Amazon)** | AWS Research | Polyglot (multi-language) codebases | Cross-language capability — directly relevant to cross-platform |

---

# SECTION 7: OPEN SOURCE PROJECTS TO STUDY
### Hackable, well-documented agentic systems you should run locally and study

| Project | Link | What to Learn From It |
|---|---|---|
| **SWE-agent** | https://github.com/SWE-agent/SWE-agent | Agent-computer interface design; how agents interact with shells |
| **mini-SWE-agent** | https://github.com/SWE-agent/mini-swe-agent | Minimal agent (100 lines Python) achieving 74%+ on SWE-bench — understand core principles |
| **Aider** | https://github.com/paul-gauthier/aider | Multi-file editing; git integration; excellent UX for command-line agents |
| **OpenHands (formerly OpenDevin)** | https://github.com/All-Hands-AI/OpenHands | Open-source Devin alternative; full agent loop with sandbox |
| **MetaGPT** | https://github.com/geekan/MetaGPT | Multi-agent software company simulation |
| **ChatDev** | https://github.com/OpenBMB/ChatDev | Communicative agents for software development |
| **AutoGen (Microsoft)** | https://github.com/microsoft/autogen | Multi-agent conversation framework |
| **CrewAI** | https://github.com/crewAIInc/crewAI | Role-based multi-agent orchestration |
| **LangChain** | https://github.com/langchain-ai/langchain | Agent framework and tool integration |
| **LlamaIndex** | https://github.com/run-llama/llama_index | RAG pipeline framework |
| **Codex CLI** | https://github.com/openai/openai-codex | OpenAI's terminal-based coding agent |
| **Awesome-Code-LLM** | https://github.com/codefuse-ai/Awesome-Code-LLM | Curated list of code LLM research |
| **AwesomeLLM4SE** | https://github.com/iSEngLab/AwesomeLLM4SE | Survey list of LLMs for software engineering |
| **Agent4SE-Paper-List** | https://github.com/FudanSELab/Agent4SE-Paper-List | Fudan's comprehensive agent-SE paper list |

---

# SECTION 8: KEY COMMUNITIES AND CONFERENCES TO FOLLOW

## Conferences (Where the Research Gets Published)
| Conference | Full Name | Link | Cadence |
|---|---|---|---|
| **ICSE** | International Conference on Software Engineering | https://www.icse-conferences.org | Annual |
| **ASE** | Automated Software Engineering | https://conf.researchr.org/series/ase | Annual |
| **FSE / ESEC** | Foundations of Software Engineering | https://2025.esec-fse.org | Annual |
| **ISSTA** | International Symposium on Software Testing and Analysis | https://conf.researchr.org/series/issta | Annual |
| **NeurIPS** | Neural Information Processing Systems | https://neurips.cc | Annual |
| **ICML** | International Conference on Machine Learning | https://icml.cc | Annual |
| **ICLR** | International Conference on Learning Representations | https://iclr.cc | Annual |
| **ACL** | Association for Computational Linguistics | https://aclanthology.org | Annual |

## Online Communities
| Community | Link | What You'll Find |
|---|---|---|
| **Papers With Code** | https://paperswithcode.com | ML papers linked to code implementations |
| **Connected Papers** | https://connectedpapers.com | Citation network visualization |
| **SWE-bench Leaderboard** | https://www.swebench.com | Live rankings of autonomous SE agents |
| **AI Engineer World's Fair** | https://www.ai.engineer | Annual conference for AI engineering practitioners |
| **Latent Space Podcast** | https://www.latent.space | Best podcast on AI engineering; covers agent architectures |
| **The Pragmatic Engineer Newsletter** | https://newsletter.pragmaticengineer.com | Industry trends in software engineering + AI |

---

# SECTION 9: INVESTOR LANDSCAPE
### Understanding who funds this space helps me understand where it's going

| Investor | Notable Investments | Signal |
|---|---|---|
| **Founders Fund (Peter Thiel)** | Cognition/Devin | Betting on AGI-level software engineering |
| **Sequoia Capital** | Factory, Magic, many others | Sequoia sees autonomous SE as a multi-trillion opportunity |
| **Bain Capital Ventures** | Poolside | Enterprise software automation as core thesis |
| **Index Ventures** | Augment, others | European+US cross-portfolio view |
| **General Catalyst** | Codeium/Windsurf | Horizontal AI infrastructure + applications |
| **Sutter Hill Ventures** | Augment | Deep technical bets on infrastructure-level tools |
| **a16z (Andreessen Horowitz)** | Various | Active AI developer tools thesis |
| **Y Combinator** | Many AI coding startups | Batch after batch of AI developer tool startups; check ycombinator.com/companies |

---

# READING ORDER RECOMMENDATION

If I only have time for 10 things from this entire document, read in this order:

1. **SWE-bench paper** — https://arxiv.org/abs/2310.06770 (understand the benchmark I'll be evaluated on)
2. **SWE-agent paper** — https://arxiv.org/abs/2405.15793 (the open-source agent I'll build on top of)
3. **MIT "Challenges and Paths" paper** — https://news.mit.edu/2025/can-ai-really-code-study-maps-roadblocks-to-autonomous-software-engineering-0716 (the roadmap of every problem I'll face)
4. **Cognition AI blog** — https://cognition.ai/blog/introducing-devin (my closest commercial predecessor)
5. **Agentless paper** — https://arxiv.org/abs/2407.01489 (the counter-argument to complex agent systems)
6. **FudanSELab paper list** — https://github.com/FudanSELab/Agent4SE-Paper-List (my ongoing bibliography)
7. **Mini-SWE-agent** — https://github.com/SWE-agent/mini-swe-agent (run this locally and understand it line by line)
8. **MetaGPT paper** — https://arxiv.org/abs/2308.00352 (multi-agent architecture reference)
9. **Reflexion paper** — https://arxiv.org/abs/2303.11366 (how agents learn from failure)
10. **Code LLM survey** — https://arxiv.org/abs/2503.01245 (comprehensive orientation to the field)

---

*Last Updated: February 2026. This field moves fast — recheck funding and benchmark scores quarterly.*
*Primary sources: arXiv, Crunchbase, TechCrunch, Contrary Research, CB Insights, SWE-bench Leaderboard*
