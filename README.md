# Robert Floyd Dugger

**Automation Engineer, Contact Center Systems** · West Palm Beach, FL

I automate the manual work inside contact centers: DNC compliance across dialer
platforms, real-time dialer automation, and Chrome extensions agents use every
shift. Most of that code is internal to the contact center I work in; the case
studies explain what it does and how it was built.

**Site:** [rfditservices.com](https://rfditservices.com/) ·
**Work:** [case studies and tools](https://rfditservices.com/projects/) ·
**Writing:** [blog.rfditservices.com](https://blog.rfditservices.com/) ·
**Contact:** [rfditservices.com/contact](https://rfditservices.com/contact/)

## Contact-center automation

| Project | What it is |
|---|---|
| DNC Compliance Automation *(private)* | One Slack command scrubs call lists across every dialer platform, with an audit trail. 3,078 tests. [Case study](https://rfditservices.com/projects/dnc-compliance-tool/) |
| Telesero Admin Suite *(private)* | Watches live dialer metrics and makes the balancing changes a person used to make by hand. 619 passing tests. [Case study](https://rfditservices.com/projects/telesero-admin-suite/) |
| Zoom Wallboard Inside the Dialer *(private)* | Real-time Zoom Contact Center availability inside the dialer, for warm transfers without switching tabs. [Case study](https://rfditservices.com/projects/cb-zoom-wallboard/) |
| Convoso New Lead Load *(Chrome Web Store)* | Chrome extension that creates the follow-up lead after a call is dispositioned in Convoso. [Details](https://rfditservices.com/projects/convoso-auto-create-lead/) |

More Chrome Web Store tools are on the [Work page](https://rfditservices.com/projects/#contact-center-automation).

## Agent systems

| Project | What it is |
|---|---|
| AgentFlow *(private, retired)* | A harness that ran Claude Code and Devin from one shared directive queue across five installs, with humans holding the only keys to Done and merge. About 900 merged PRs and 10,000 tests in six weeks. Retired when it started improving itself instead of the product; the parts that worked are being carried into smaller projects. |
| [rfd_method](https://github.com/rfd62794/rfd_method) | The proof standard behind it: stop and verify, write a directive, implement, certify the test floor, advance. |
| [RFDRepoMan](https://github.com/rfd62794/RFDRepoMan) | 37 typed git and GitHub actions for agents, with risky ones behind an explicit confirmation gate. |
| [ClineMCP](https://github.com/rfd62794/ClineMCP) | Long-lived, observable coding-agent sessions as an MCP service. |

## Engineering tools

| Project | What it is |
|---|---|
| [RFD_Blog_Engine](https://github.com/rfd62794/RFD_Blog_Engine) | WordPress and dev.to publishing pipeline with honest reconciliation. [Write-up](https://rfditservices.com/projects/rfd-blog-engine/) |
| [RFD_Logging](https://github.com/rfd62794/RFD_Logging) | Structured JSON logging for Python services, zero dependencies. [Write-up](https://rfditservices.com/projects/rfd-logging/) |
| [OpenAgent](https://github.com/rfd62794/OpenAgent) | Session context for AI coding tools, so every session doesn't start from zero. [Write-up](https://rfditservices.com/projects/openagent/) |
| RFD_YT_Engine *(private)* | YouTube channel pipeline split into eight domains and exposed as MCP tools. [Write-up](https://rfditservices.com/projects/rfd-yt-engine/) |

## Games (side projects)

| Project | What it is |
|---|---|
| [RFDGameStudio](https://github.com/rfd62794/RFDGameStudio) | A game definition format and runtime contract: every game is data, UI intent and pure Lua logic that runs identically in Python, TypeScript and Rust. [Studio](https://rfditservices.com/studio/) |
| [VoidDrift](https://github.com/rfd62794/VoidDrift) | Mobile arcade mining game in Rust and Bevy for Android. [Live on itch.io](https://rdug627.itch.io/voidrift) |
| [OperatorGame](https://github.com/rfd62794/OperatorGame) | Dispatch simulator in Rust: command a slime crew, deploy on missions, see what survives. |

## Retired and archived

Kept public on purpose: each one still shows how it was built, and why it stopped.

| Project | Status | What it shows |
|---|---|---|
| [rpgCore](https://github.com/rfd62794/rpgCore) | Retired → RFDGameStudio | One Python engine driving games in four genres; 3,628 commits. [Retrospective](https://rfditservices.com/archives/rpgcore/) |
| PhantomArbiter *(private)* | Semi-retired | Solana arbitrage system across Python, Rust (PyO3) and TypeScript. [Post-mortem](https://rfditservices.com/archives/phantom-arbiter/) |
| [ContentPipeline](https://github.com/rfd62794/ContentPipeline) | Retired → RFD_YT_Engine | YAML beat sheet to finished YouTube Short, with OBS and YouTube API automation. [Retrospective](https://rfditservices.com/archives/contentpipeline/) |
| [RFD_IT_Publishing](https://github.com/rfd62794/RFD_IT_Publishing) | Merged → RFDGameStudio | itch.io publishing CLI designed so it could be absorbed without a rewrite. [Retrospective](https://rfditservices.com/archives/rfd-it-publishing/) |

Smaller games and experiments, sorted honestly by how finished they are, are on
the [Legacy Projects](https://rfditservices.com/legacy/) page.
