<picture>
  <img src="https://raw.githubusercontent.com/wify777/wify777/main/profile-banner.svg?v=2" alt="ashodiev — Python and AI agent security" width="100%" />
</picture>

I build Python tools to study how AI agents handle untrusted messages and
privileged actions. My current project is **AgentTrust**, an experimental
sandbox for agent-to-agent prompt injection.

## Selected work

### [AgentTrust](https://github.com/wify777/AI-vs-AI-Social-Engineering)

What happens when a low-privilege agent forwards a request to an agent with
administrative tools? AgentTrust makes that path inspectable, from the attack
payload to the recorded stub-tool call.

- **Data:** 60 attack payloads and 2,475 archived records, including provider failures.
- **Tooling:** offline dataset verification, network-disabled tests, and package builds.
- **Scope:** a research prototype with local stub tools, not a production security product.

[Code & setup](https://github.com/wify777/AI-vs-AI-Social-Engineering#start-here-no-api-key-required) ·
[Data audit & limitations](https://github.com/wify777/AI-vs-AI-Social-Engineering/blob/main/docs/reproducibility-audit.md) ·
[CI checks](https://github.com/wify777/AI-vs-AI-Social-Engineering/actions/workflows/ci.yml)

## Working stack

- **Code:** Python, HTTP APIs, JSONL
- **Analysis:** NumPy, Matplotlib
- **Checks & delivery:** pytest, Ruff, GitHub Actions, Docker

---

Questions about the project or an experiment to suggest?
[Open an issue](https://github.com/wify777/AI-vs-AI-Social-Engineering/issues).
