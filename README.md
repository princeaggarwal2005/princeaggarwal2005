# Prince Aggarwal

**Mathematics & Computing @ Delhi Technological University · 2028**

I build software around AI systems: the infrastructure that routes model requests, the tools that orchestrate agents, and the security boundaries that keep those systems trustworthy.

Currently spending most of my time on **agent security, LLM infrastructure, and backend systems**.

## What I'm building

### [AgentATK]

An agentic-application security project, currently being rebuilt around a more rigorous, code-aware analysis engine.

The current v0 focuses on mapping the attack surface of **Python LangChain and LangGraph applications**:

- Trace untrusted inputs through agents, models, tools, and graph state.
- Map what those paths can reach, grouping actions by capability and impact.
- Locate guardrails where they actually apply, and distinguish weak controls.
- Associate relevant OWASP security test categories with graph structures.
- Attach file-and-line evidence to findings, while keeping unknowns visible.

**Current scope: mapping, not execution.** The hackathon demo is an earlier prototype; the proper version is under development. Automated security testing is planned for a later milestone.

### [Stratum](https://github.com/princeaggarwal2005/stratum-llm-router)

An OpenAI-compatible LLM gateway written in Go, using local semantic classification to route requests between a primary model and a cheaper side model.

Explores cost-aware model routing with embedding-based classification, response verification, and fallback to the primary model. In an offline RouterBench evaluation, it reported **36.8% lower estimated API cost** than always using the primary model.

## Areas I work in

- **AI engineering:** LLM applications, agent workflows, tool use, MCP, evaluation, reliability and security.
- **Backend & infrastructure:** Go, Python, TypeScript, APIs, service architecture and Docker.
- **Computer science:** Data structures, algorithms, system design and competitive programming.

## Tech stack

| Area | Technologies |
|---|---|
| Languages | Go · Python · TypeScript · C++ · JavaScript |
| Backend | Go · Node.js · FastAPI · Express · REST APIs |
| AI systems | LLM APIs · Agentic workflows · MCP · Embeddings · Evals |
| Frontend | React · Next.js · HTML · CSS · Tailwind |
| Infrastructure | Docker · Git · Linux · Redis |

## Competitive programming

**500+ problems solved** across LeetCode, Codeforces and other platforms.

I enjoy the problem-solving side of CS, especially algorithms, data structures and the occasional contest-induced existential crisis.

## Connect

[LinkedIn](https://www.linkedin.com/in/prince-aggarwal-b00864321/) · [X](https://x.com/agr_prince2005) · [LeetCode](https://leetcode.com/u/agr_prince2005/) · [Codeforces](https://codeforces.com/profile/agr.prince2005) · [Email](mailto:agr.prince2005@gmail.com)

---

*Build systems. Understand their failure modes. Make them better.*
