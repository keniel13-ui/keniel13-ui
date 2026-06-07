 # Keniel Maldonado

  Building **Self-Correcting Systems**: tools and research for AI agent memory reliability,
  authority auditing, freshness checks, and action-safe automation.

  Current focus:

  > Relevance is not authority.

  AI systems can retrieve context that is semantically relevant but not allowed to govern
  an action. My work explores how agent memory should track authority, freshness, scope,
  corrections, and verification requirements before tool use.

  ## Current Proof Points

  - 27 public research claims on AI memory reliability and authority boundaries.
  - A live Memory Authority Auditor built with six specialized agent services.
  - A public research harness with claim ledger, preregistrations, evaluators, ablations,
  and validity notes.
  - Recent work on signed-and-fresh grants, paired authority/action logs, and scope-
  soundness boundaries.

  ## Live Work

  ### AI Memory Authority Auditor

  A deployed multi-agent web app that audits `AGENTS.md`, `CLAUDE.md`, Cursor rules, SOPs,
  and project memory files for stale instructions, authority conflicts, and verification
  gates.

  - Live app: https://memory-authority-auditor-web-992750435781.us-central1.run.app
  - DEV submission:
  https://dev.to/zep1997/i-built-a-multi-agent-authority-auditor-for-ai-memory-files-1hb0
  - Architecture: one Cloud Run web service plus six specialized agent services.

  Agent roles:

  - Memory Extractor
  - Authority Classifier
  - Conflict Detector
  - Verification Gate Agent
  - Authority Mapper
  - Report Writer

  ### AI Memory Judgment Demo

  A public research harness for testing whether memory retrieval systems select the memory
  that is authorized to govern an action, not only the memory that is most relevant.

  - Repo: https://github.com/keniel13-ui/ai-memory-judgment-demo
  - Includes lexical retrieval tests, embedding comparison, role-filter experiments, scope
  metadata tests, action-type arbitration, freshness gates, paired action logs, claim
  ledger, validity threats, and audit materials.

  ## Public Writing

  I write in public on DEV about AI memory, correction memory, uncertainty, authority
  arbitration, and production agent reliability.

  - DEV profile: https://dev.to/zep1997
  - Start here: https://dev.to/zep1997/start-here-my-ai-memory-research-so-far-4m4k

  ## Working Thesis

  Production agent memory needs more than recall. Once agents can remember, use tools, and
  act across time, they need a trust layer around memory itself.

  It needs:

  - authority labels
  - status and freshness
  - scope boundaries
  - source-of-truth pointers
  - verification gates
  - audit traces
  - human review for sensitive actions

  Memory is input.

  Authority is the action boundary.
