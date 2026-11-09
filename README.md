### Ido Horowitz

Revenue operator turned builder. I've built sales, marketing, CS and RevOps functions from zero at several startups, and now I build the agent systems that run them.

**What I'm building now: Exo.** It's an experimental company that runs on AI agents. I designed both the agent platform and the operating model around it:

- **A multi-tenant agent-operations platform.** It is built in TypeScript on the Claude Agent SDK, Postgres and Inngest. Every agent action goes through one policy gateway and is written to an append-only ledger. Every model call is logged with its cost and the version of the skill behind it.
- **Governance before autonomy.** Agents act by default within budgets, undo windows and kill switches, and a few red lines always stay with a human. Releases pass eval gates, a backup and restore test, and an isolation check.
- **An executive council of agents.** CTO, CFO, Board, Trust/CISO, Product and others each have a charter, decision rights and a decision journal. A weekly retro sharpens them using evidence.
- **Built with agents.** Claude Code lanes wrote the code under the same gates: about 1,400 commits, 100+ merged PRs and 7 gated production releases in the first 30 days.

**Why most of my work isn't here.** It lives in private repositories, my company's own and my clients'. I'm happy to walk through the architecture, the governance model and a live demo.

**Background:** Director of Sales & BD at Commbox (ARR $7M → $12M), VP Sales at RedFalcon.AI, VP BD at Olistics, founder and CEO of Multiverse (ad-tech).

[exo.partners](https://exo.partners) · Tel Aviv
