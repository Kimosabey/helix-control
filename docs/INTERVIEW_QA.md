# Interview Q&A — HelixControl

### "Tell me about this project."
HelixControl is agentic infrastructure orchestrator and MCP runtime for autonomous DevOps. HelixControl turns operator intent into safe infrastructure actions: a LangGraph agent plans, MCP tools execute against Kubernetes, and guardrails keep autonomous operations within bounds.

### "What was the hardest part?"
Letting an agent act on infrastructure while keeping it provably safe with guardrails and approvals.

### "Why did you choose this stack?"
- **LangGraph** — stateful multi-agent orchestration.
- **MCP** — model context protocol tooling.
- **Kubernetes** — container orchestration.

### "How does it fit the rest of your portfolio?"
It follows my "Antigravity" model — local logic/state/UI, cloud reasoning where it earns its cost — and shares the documentation and deployment conventions used across all my projects (AX-04).
