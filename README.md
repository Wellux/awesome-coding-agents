<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/header-dunkel.svg">
  <img alt="Awesome Coding Agents: Claude Code, Codex, OpenCode, Pi and Herdr with setups, parallel sessions, loops, code context, usage and guides." src=".github/assets/header-hell.svg" width="100%">
</picture>

<p align="center"><a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge-flat2.svg"></a> <img alt="459 repos" src="https://img.shields.io/badge/repos-459-1B8DBE?style=flat-square"> <img alt="9 categories" src="https://img.shields.io/badge/categories-9-1B8DBE?style=flat-square"> <img alt="5.4M stars combined" src="https://img.shields.io/badge/stars_combined-5.4M-1B8DBE?style=flat-square"> <img alt="updated 2026-10-29" src="https://img.shields.io/badge/updated-2026--10--29-95969A?style=flat-square"> <img alt="license CC0" src="https://img.shields.io/badge/license-CC0-95969A?style=flat-square"></p>

<h3 align="center">Coding agents, and everything that keeps them on track.</h3>

Terminal and editor coding agents plus the setups, parallel runners, spec workflows, code context, usage trackers and review tools around them. Each repo sits where it does its job, not by star count.

<!-- onboarding:start -->
### In 3 Minuten startklar

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/onboarding-dunkel.svg">
  <img alt="In 3 Minuten startklar: 1. Start here: 4 Picks, einer pro Rolle; 2. Rubrik: nach Aufgabe sortiert, nicht Hype; 3. Ausprobieren: README des Picks, Install-Zeile; 4. Dranbleiben: Stern setzen, Updates im Feed" src=".github/assets/onboarding-hell.svg" width="100%">
</picture>

1. **Start here.** Oben unter [Start here](#start-here) stehen 4 Picks, einer je Rolle. Fang mit dem an, der zu deiner Lücke passt.
2. **Rubrik.** Unter [Contents](#contents) die Rubrik wählen: jedes Repo steht genau einmal da, nach der Aufgabe, die es erledigt.
3. **Ausprobieren.** Den Pick öffnen und seine Install-Zeile ausführen; die Sterne zeigen, wie viele ihn schon nutzen.
4. **Dranbleiben.** Dieser Liste einen Stern geben: neue Picks erscheinen in deinem GitHub-Feed.

**Was du davon hast**

- Die Repos rund um Coding Agents an einem Ort, nach Aufgabe sortiert, statt tagelang selbst zu suchen.
- Jeder Pick sagt in einem Satz, wofür er gut ist.
- Aufgenommen wird nur, was öffentlich ist, eine Lizenz hat und heute läuft.

**Nächster Schritt:** Fehlt ein Repo? Über [CONTRIBUTING.md](CONTRIBUTING.md) vorschlagen, ein Satz zur Aufgabe genügt; mehr Listen auf [github.com/Wellux](https://github.com/Wellux).
<!-- onboarding:end -->

## Start here

No time for 459 repos? Start with these 4, one per role. Add the rest when you feel the gap.

| Role | Pick | Why |
|:--|:--|:--|
| **Agent** | [opencode](https://github.com/anomalyco/opencode) `★ 222.8k` | Open-source terminal coding agent with build and plan agents and a desktop app |
| **Spec** | [spec-kit](https://github.com/github/spec-kit) `★ 143.7k` | Write the spec and task plan first so the agent builds the right thing |
| **Parallel** | [vibe-kanban](https://github.com/BloopAI/vibe-kanban) `★ 28.5k` | Run several coding agents side by side from one kanban board |
| **Review** | [pr-agent](https://github.com/The-PR-Agent/pr-agent) `★ 13.7k` | Reviews each pull request the agents open before you merge it |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/map-dunkel.svg">
  <img alt="Map of the 9 categories" src=".github/assets/map-hell.svg" width="100%">
</picture>

## Contents

- [Coding agents](#coding-agents) · 64<br><sub>[Terminal agents](#terminal-agents) · [Editor and IDE agents](#editor-and-ide-agents) · [Autonomous software engineers](#autonomous-software-engineers) · [Prompt-to-app builders](#prompt-to-app-builders) · [Rebuilt and dissected agents](#rebuilt-and-dissected-agents)</sub>
- [Pi and Herdr](#pi-and-herdr) · 47<br><sub>[Pi ecosystem](#pi-ecosystem) · [Herdr ecosystem](#herdr-ecosystem)</sub>
- [Setups and mods](#setups-and-mods) · 57<br><sub>[Claude Code setups and frameworks](#claude-code-setups-and-frameworks) · [Claude Code hooks, status lines and mods](#claude-code-hooks-status-lines-and-mods) · [Codex and OpenCode add-ons](#codex-and-opencode-add-ons) · [Copilot, Cursor, Gemini and Antigravity add-ons](#copilot-cursor-gemini-and-antigravity-add-ons)</sub>
- [Accounts and usage](#accounts-and-usage) · 24<br><sub>[Account and provider switchers](#account-and-provider-switchers) · [Usage, quota and cost monitors](#usage-quota-and-cost-monitors)</sub>
- [Parallel agents](#parallel-agents) · 70<br><sub>[Parallel worktrees and boards](#parallel-worktrees-and-boards) · [Desktop and web workbenches](#desktop-and-web-workbenches) · [Mobile and web access](#mobile-and-web-access) · [Background and cloud runners](#background-and-cloud-runners) · [Councils and second opinions](#councils-and-second-opinions)</sub>
- [Specs, loops and factories](#specs-loops-and-factories) · 62<br><sub>[Specs and task plans](#specs-and-task-plans) · [Plans and task trackers for agents](#plans-and-task-trackers-for-agents) · [Agent loops](#agent-loops) · [Software factories](#software-factories)</sub>
- [Review, tests and provenance](#review-tests-and-provenance) · 39<br><sub>[AI code review](#ai-code-review) · [Testing and QA agents](#testing-and-qa-agents) · [Sessions and provenance](#sessions-and-provenance)</sub>
- [Code context](#code-context) · 62<br><sub>[Code graphs and intelligence](#code-graphs-and-intelligence) · [Semantic code search](#semantic-code-search) · [Repo packers and live docs](#repo-packers-and-live-docs) · [Token savers](#token-savers)</sub>
- [Guides and lists](#guides-and-lists) · 34<br><sub>[Claude Code guides](#claude-code-guides) · [Codex and Copilot guides](#codex-and-copilot-guides) · [Harness and context engineering](#harness-and-context-engineering) · [Vibe coding](#vibe-coding)</sub>

## Coding agents

The agents that read, write and ship code with you.

### Terminal agents

- **[opencode](https://github.com/anomalyco/opencode)** `★ 222.8k` · **Top pick.** Open-source coding agent for the terminal, any model.
- **[claude-code](https://github.com/anthropics/claude-code)** `★ 153.8k` · **Top pick.** Anthropic's agentic coding tool in the terminal.
- **[codex](https://github.com/openai/codex)** `★ 131.4k` · **Top pick.** OpenAI's lightweight coding agent that runs in your terminal.
- **[gemini-cli](https://github.com/google-gemini/gemini-cli)** `★ 108.6k` · Open-source AI agent that brings Gemini into your terminal.
- **[openinterpreter](https://github.com/openinterpreter/openinterpreter)** `★ 68.7k` · Coding agent for open models such as Kimi K3 and GLM 5.3.
- **[goose](https://github.com/aaif-goose/goose)** `★ 55.9k` · Open-source, extensible AI agent that installs, executes, edits and tests code with any LLM.
- **[aider](https://github.com/Aider-AI/aider)** `★ 49.8k` · AI pair programming in the terminal with Claude, GPT, Gemini, Llama and other models.
- **[qwen-code](https://github.com/QwenLM/qwen-code)** `★ 28.8k` · Open-source AI coding agent that lives in your terminal.
- **[grok-build](https://github.com/xai-org/grok-build)** `★ 27.6k` · SpaceXAI's coding agent harness with a fullscreen, mouse-interactive, extensible terminal UI.
- **[prime-agent](https://github.com/PrimeIntellect-ai/prime-agent)** `★ 22.4k` · Self-improving RLM agent for coding workflows and long-running autonomous tasks.
- **[MiMo-Code](https://github.com/XiaomiMiMo/MiMo-Code)** `★ 13.7k` · Coding agent CLI from the Xiaomi MiMo team where models and agents co-evolve.
- **[copilot-cli](https://github.com/github/copilot-cli)** `★ 11.3k` · Brings the Copilot coding agent to the terminal.
- **[claude-engineer](https://github.com/Doriandarko/claude-engineer)** `★ 11.2k` · Interactive command-line interface that uses Anthropic's Claude 3.5 Sonnet as a coding assistant.
- **[claurst](https://github.com/Kuberwastaken/claurst)** `★ 10.3k` · Multi-provider terminal coding agent in Rust, begun as a clean-room rebuild of Claude Code.
- **[ZCode](https://github.com/zai-org/ZCode)** `★ 8.3k` · Z.ai's extensible coding agent harness.
- **[Kode-CLI](https://github.com/shareAI-lab/Kode-CLI)** `★ 5.2k` · Terminal AI coding assistant that edits files, runs commands and switches models mid-session.
- **[mistral-vibe](https://github.com/mistralai/mistral-vibe)** `★ 5.2k` · Minimal command-line coding agent from Mistral.
- **[iflow-cli](https://github.com/iflow-ai/iflow-cli)** `★ 5.1k` · Terminal agent that analyzes your repositories and works on code from the command line.
- **[letta-code](https://github.com/letta-ai/letta-code)** `★ 3.7k` · Stateful coding agent from Letta with memory and identity that learns and adapts over time.
- **[grok-cli](https://github.com/superagent-ai/grok-cli)** `★ 3.5k` · Open-source terminal coding agent for the Grok API.
- **[Fuxi](https://github.com/fuxicodex/Fuxi)** `★ 3.2k` · Terminal coding agent that edits code, runs commands and routes between providers by cost.
- **[o1-engineer](https://github.com/Doriandarko/o1-engineer)** `★ 2.8k` · CLI on the OpenAI API for code generation, file editing and project planning.
- **[antigravity-cli](https://github.com/google-antigravity/antigravity-cli)** `★ 2.7k` · Brings the Antigravity agent harness to the terminal as a CLI.
- **[deepseek-engineer](https://github.com/Doriandarko/deepseek-engineer)** `★ 2.2k` · CLI coding assistant on the DeepSeek API that reads, creates and diff-edits local files.
- **[loushang](https://github.com/zhnt/loushang)** `★ 1.9k` · Python coding harness and terminal workbench with model routing, sessions and tool governance.
- **[ntegrals/10x](https://github.com/ntegrals/10x)** `★ 1.4k` · Self-hosted open-source coding agent with multi-step Superpowers, model routing and BYOK.
- **[omni-engineer](https://github.com/Doriandarko/omni-engineer)** `★ 866` · Console-based AI developer assistant, successor to Claude Engineer, with multi-file editing.
- **[klaatcode](https://github.com/KlaatAI/klaatcode)** `★ 353` · Open-source terminal coding agent that picks a model per task across Claude, GPT and DeepSeek.
- **[workos/cli](https://github.com/workos/cli)** `★ 71` · AI-powered CLI wizard that integrates WorkOS AuthKit into your app automatically.
- **[coven-code](https://github.com/OpenCoven/coven-code)** `★ 10` · Open-source, multi-provider AI coding-agent TUI written in Rust.

### Editor and IDE agents

- **[cline](https://github.com/cline/cline)** `★ 71k` · Autonomous coding agent available as an SDK, IDE extension or CLI assistant.
- **[continue](https://github.com/continuedev/continue)** `★ 36.4k` · Open-source coding agent for editors and IDEs.
- **[cursor](https://github.com/cursor/cursor)** `★ 33.3k` · AI-first code editor from Cursor.
- **[OpenCursor](https://github.com/PawanOsman/OpenCursor)** `★ 6k` · Open-source Cursor-like coding agent for VS Code with agentic chat and multi-provider LLMs.
- **[localpilot](https://github.com/danielgross/localpilot)** `★ 3.3k` · Local Copilot-style code completion running on your own machine.
- **[sidex](https://github.com/Sidenai/sidex)** `★ 3.1k` · VS Code workbench rebuilt on Tauri with a built-in AI coding agent.
- **[athas](https://github.com/athasdev/athas)** `★ 3.1k` · Cross-platform Tauri code editor with Git support, AI agents and vim keybindings.
- **[ProxyAI](https://github.com/carlrobertoh/ProxyAI)** `★ 1.9k` · Open-source AI coding assistant for JetBrains IDEs that connects to any model.
- **[coffee](https://github.com/Coframe/coffee)** `★ 1.5k` · AI tool that builds and iterates on frontend UI from inside your own IDE.
- **[vibeyard](https://github.com/elirantutia/vibeyard)** `★ 1.4k` · IDE built for working with AI coding agents.

### Autonomous software engineers

- **[OpenHands](https://github.com/OpenHands/OpenHands)** `★ 92.1k` · Platform for AI-driven software development with autonomous coding agents.
- **[gpt-pilot](https://github.com/Pythagora-io/gpt-pilot)** `★ 33.6k` · AI developer agent that writes code for whole apps.
- **[SWE-agent](https://github.com/SWE-agent/SWE-agent)** `★ 20.7k` · Takes a GitHub issue and tries to fix it on its own with the language model of your choice.
- **[DeepCode](https://github.com/HKUDS/DeepCode)** `★ 16.8k` · Open agentic coding with agent harness, loop engineering and multi-agent orchestration.
- **[developer](https://github.com/smol-ai/developer)** `★ 12.2k` · Library for embedding a developer agent in your own app.
- **[trae-agent](https://github.com/bytedance/trae-agent)** `★ 12.2k` · LLM-based agent for general software engineering tasks.
- **[open-swe](https://github.com/langchain-ai/open-swe)** `★ 11.1k` · Open-source asynchronous coding agent.
- **[gpt-migrate](https://github.com/joshpxyne/gpt-migrate)** `★ 7k` · GPT-based tool that migrates a codebase from one framework or language to another.
- **[DevOpsGPT](https://github.com/kuafuai/DevOpsGPT)** `★ 6k` · Multi-agent system that combines LLMs with DevOps tools to turn requirements into software.
- **[dev-gpt](https://github.com/jina-ai/dev-gpt)** `★ 1.9k` · GPT-based virtual development team.
- **[100xengineer](https://github.com/code100x/100xengineer)** `★ 32` · Experiment that gives an agent access to compute and coding resources.
- **[ai-harness](https://github.com/Yash990-bit/ai-harness)** `★ 1` · Hackathon submission for an autonomous software engineering platform with headless evaluation.

### Prompt-to-app builders

- **[ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template)** `★ 37.8k` · Clones a website with one command using AI coding agents.
- **[open-lovable](https://github.com/firecrawl/open-lovable)** `★ 28.8k` · Clones any website and recreates it as a modern React app.
- **[llamacoder](https://github.com/Nutlope/llamacoder)** `★ 7.1k` · Open-source Claude Artifacts clone built on Llama 3.1 405B.
- **[fragments](https://github.com/e2b-dev/fragments)** `★ 6.4k` · Open-source Next.js template for building apps fully generated by AI.
- **[vibesdk](https://github.com/cloudflare/vibesdk)** `★ 5.4k` · Open-source vibe coding platform for building your own vibe-coding platform on Cloudflare.
- **[chatgpt-artifacts](https://github.com/ozgrozer/chatgpt-artifacts)** `★ 511` · Brings Claude's Artifacts feature to ChatGPT.
- **[wp-autoplugin](https://github.com/WP-Autoplugin/wp-autoplugin)** `★ 399` · WordPress plugin that generates working plugins from plain descriptions using AI models.
- **[Gumroad-Landing-Page-Generator](https://github.com/peterw/Gumroad-Landing-Page-Generator)** `★ 379` · Python script that turns a Gumroad site into a GPT-4 landing page and deploys it to Vercel.
- **[10x-app-builder/10x](https://github.com/10x-app-builder/10x)** `★ 291` · AI app builder for macOS that generates SwiftUI code, an Xcode project and a simulator preview.
- **[open-artifacts](https://github.com/mayfer/open-artifacts)** `★ 212` · Claude Artifacts-style app in one static HTML page that works with any language model.
- **[rilable](https://github.com/rbrown101010/rilable)** `★ 170` · iPhone app that builds web and iOS apps from a prompt.

### Rebuilt and dissected agents

- **[claw-code](https://github.com/ultraworkers/claw-code)** `★ 195k` · Public Rust implementation of the claw CLI agent harness, now kept as an agent-maintained exhibit.

<sub><a href="#contents">back to contents</a></sub>

## Pi and Herdr

Pi, a hackable coding agent, and Herdr, a terminal workspace for agents, each with its own plugins.

### Pi ecosystem

- **[pi](https://github.com/earendil-works/pi)** `★ 118.5k` · **Top pick.** Agent toolkit with a unified LLM API, agent loop, TUI and the pi coding agent CLI.
- **[nicobailon/pi-subagents](https://github.com/nicobailon/pi-subagents)** `★ 4.1k` · **Top pick.** Pi extension for async subagent delegation with truncation, artifacts and session sharing.
- **[oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** `★ 70.4k` · Agent CLI on senpi, a Pi fork, with an ultrawork keyword that plans, builds and checks each task.
- **[oh-my-pi](https://github.com/can1357/oh-my-pi)** `★ 37k` · Fork of the Pi coding agent with the IDE wired in, built by Stencil Labs.
- **[pi-autoresearch](https://github.com/davebcn87/pi-autoresearch)** `★ 8.2k` · Autonomous experiment loop extension for Pi.
- **[PI-Desktop](https://github.com/vastsa/PI-Desktop)** `★ 7.4k` · Local-first AI coding agent desktop on Electron, a Rust core and the pi harness.
- **[thinkrail](https://github.com/JetBrains/thinkrail)** `★ 5.1k` · Lightweight IDE for vibe coding with pi that adapts to the way you work.
- **[SoL-Pi](https://github.com/NVlabs/SoL-Pi)** `★ 3.6k` · Pi extension with four efficiency mechanisms that cut repeated model turns and context replay.
- **[pi-skills](https://github.com/badlogic/pi-skills)** `★ 2.6k` · Skills for the Pi coding agent, compatible with Claude Code and Codex CLI.
- **[pi-computer-use](https://github.com/injaneity/pi-computer-use)** `★ 2.1k` · Lets Pi control your apps on macOS and Windows.
- **[pi-vs-claude-code](https://github.com/disler/pi-vs-claude-code)** `★ 1.7k` · Comparison of the open-source Pi agent and the closed-source Claude Code agent.
- **[gentle-shell](https://github.com/Gentleman-Programming/gentle-shell)** `★ 1.5k` · Pi-native workspace with parallel coding agents, live tasks, Git diffs and permission controls.
- **[pi-config](https://github.com/amosblomqvist/pi-config)** `★ 1.2k` · Personal configuration for the Pi coding agent.
- **[pi-agent-desktop](https://github.com/abcwyc/pi-agent-desktop)** `★ 863` · Cross-platform desktop app that brings a Claude Code-style experience to the Pi coding agent.
- **[working-activity](https://github.com/ccch1mneyyy/working-activity)** `★ 666` · Animated working-status line extension for the pi CLI and DeepSeek Harness.
- **[pi-llm-wiki](https://github.com/zosmaai/pi-llm-wiki)** `★ 616` · Self-maintaining, Obsidian-compatible wiki for pi that turns raw sources into linked notes.
- **[fusion-harness](https://github.com/disler/fusion-harness)** `★ 600` · Pi extension that fuses two to five frontier models into one architect and several builders.
- **[PiDurableKit](https://github.com/finnvoor/PiDurableKit)** `★ 290` · Durable AI agents for Apple platforms, running pi-durable on JavaScriptCore with a Swift API.
- **[RSI-Harness](https://github.com/CosmosMind-ai/RSI-Harness)** `★ 271` · Versionable, shareable agent harness built on the Pi coding agent with a Genome config layer.
- **[pi2dsh](https://github.com/weijiafu14/pi2dsh)** `★ 214` · Compatibility layer that runs unmodified Pi extensions as native DeepSeek Harness plugins.
- **[pi-herdsman](https://github.com/boadij/pi-herdsman)** `★ 213` · Asynchronous Pi subagents and fleet orchestration with nested delegation for parallel coding agents.
- **[edxeth/pi-subagents](https://github.com/edxeth/pi-subagents)** `★ 133` · Multi-agent framework for Pi with background and foreground agents and forked context.
- **[pi-typesafe](https://github.com/DevMortimer/pi-typesafe)** `★ 48` · TypeSafe decisions for Pi with a batched evaluation tool, terminal playground and typed API.
- **[pi-cua](https://github.com/injaneity/pi-cua)** `★ 35` · Brings Pi coding sessions to Cua Spaces while workspace tools run on your own computers.
- **[bunny-agent](https://github.com/buda-ai/bunny-agent)** `★ 29` · Coding agent built on Pi with a daily CLI, one-command remote sandboxes and an agent product kit.
- **[eimg/helix](https://github.com/eimg/helix)** `★ 27` · Experimental agent orchestration loop built on Pi.
- **[Bunny-AI-Agent](https://github.com/abdu6666/Bunny-AI-Agent)** `★ 19` · Coding agent built on Pi with a CLI, remote sandboxes and a kit for building agent products.
- **[jev-harness](https://github.com/PromtEngineer/jev-harness)** `★ 10` · Pi agent harness built around TypeSafe's Jev with a router, context picker, gate and verifier.
- **[pi-plugins](https://github.com/doodledood/pi-plugins)** `★ 5` · Installable Pi extensions, a theme and setup profile templates.

### Herdr ecosystem

- **[herdr](https://github.com/herdrdev/herdr)** `★ 46.4k` · **Top pick.** Rust terminal multiplexer and workspace manager built as the runtime for coding agents.
- **[collie](https://github.com/AltanS/collie)** `★ 1.5k` · Mobile client for Herdr: a self-hosted PWA to drive Claude Code, Pi, Codex and OpenCode.
- **[herdr-reviewr](https://github.com/persiyanov/herdr-reviewr)** `★ 955` · Herdr plugin that shows your agent's diff in a terminal pane and sends comments back to the agent.
- **[herdrm](https://github.com/missuo/herdrm)** `★ 772` · Native macOS console for Herdr showing all coding agents and their live terminals.
- **[herdr-annotate](https://github.com/plannotator/herdr-annotate)** `★ 710` · Herdr plugin to annotate terminal text, documents and agent replies and send feedback to the agent.
- **[herdr-file-viewer](https://github.com/smarzban/herdr-file-viewer)** `★ 689` · Git-aware, read-only file viewer for Herdr with a tree, content pane and diffs.
- **[herdr-sidebar](https://github.com/alexarthurs/herdr-sidebar)** `★ 518` · VS Code-style sidebar for herdr with a file explorer and git source control.
- **[herdr-remote](https://github.com/dcolinmorgan/herdr-remote)** `★ 436` · Monitors and drives herdr agents from the menu bar, a phone or Telegram.
- **[herdr-plus](https://github.com/cloudmanic/herdr-plus)** `★ 367` · Herdr plugin that adds Projects and Quick Actions.
- **[herdr-browser](https://github.com/ogulcancelik/herdr-browser)** `★ 360` · Herdr plugin that renders a real Chromium view inside a pane and drives it over CDP.
- **[herdr-auto-title](https://github.com/kryptamine/herdr-auto-title)** `★ 277` · Herdr plugin that names tabs and panes from current work, Git branch and Claude Code sessions.
- **[herdr-board](https://github.com/nelsonPires5/herdr-board)** `★ 185` · Kanban board for herdr where cards are prompts dispatched to AI agents in visible panes.
- **[herdr-hud](https://github.com/finna/herdr-hud)** `★ 110` · Floating desktop HUD for macOS and Windows to manage Herdr agents while gaming.
- **[herdr-telegram-agents](https://github.com/permgps/herdr-telegram-agents)** `★ 85` · Herdr plugin that drives coding agents from Telegram with one topic per agent and live status.
- **[omarchy-herdr](https://github.com/jankeesvw/omarchy-herdr)** `★ 58` · Shows herdr servers and their agents in the Omarchy bar, with a click to jump to one.
- **[OmarchyRemote](https://github.com/gigq/OmarchyRemote)** `★ 11` · Touch shell for an Omarchy desktop with terminal, files, browser tabs and Herdr agents.
- **[omarchy-herdr-hud](https://github.com/finna/omarchy-herdr-hud)** `★ 7` · Draggable Omarchy overlay to monitor and prompt Herdr agents without leaving a game.
- **[herdx](https://github.com/dizzyd/herdx)** `★ 3` · macOS interface for herdr.

<sub><a href="#contents">back to contents</a></sub>

## Setups and mods

Configs, hooks and ports that make a harness yours.

### Claude Code setups and frameworks

- **[ECC](https://github.com/affaan-m/ECC)** `★ 291.8k` · **Top pick.** Agent harness optimization system with skills, instincts, memory and research-first development.
- **[gstack](https://github.com/garrytan/gstack)** `★ 138.1k` · **Top pick.** Garry Tan's Claude Code setup of 23 opinionated tools acting as CEO, designer, eng manager and QA.
- **[oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)** `★ 40.4k` · Teams-first multi-agent orchestration for Claude Code.
- **[claude-code-templates](https://github.com/davila7/claude-code-templates)** `★ 33k` · CLI for configuring and monitoring Claude Code with ready-made templates.
- **[SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework)** `★ 23.9k` · Configuration framework that adds specialized commands and cognitive personas to Claude Code.
- **[claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase)** `★ 10k` · Example Claude Code infrastructure with skill auto-activation, hooks and agents.
- **[claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase)** `★ 6.1k` · Example Claude Code project setup with hooks, skills, agents, commands and GitHub Actions.
- **[WorldFlowAI/everything-claude-code](https://github.com/WorldFlowAI/everything-claude-code)** `★ 5.5k` · Claude Code toolkit of agents, commands, skills, rules and hooks.
- **[claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows)** `★ 3.9k` · Workflows and configurations for Claude Code built from heavy daily use.
- **[claude-code-harness](https://github.com/Chachamaru127/claude-code-harness)** `★ 3.2k` · Autonomous plan, work and review cycle for Claude Code, packaged as a development harness.
- **[my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup)** `★ 2.7k` · Starter template configuration and CLAUDE.md memory bank system for Claude Code.
- **[trailofbits/claude-code-config](https://github.com/trailofbits/claude-code-config)** `★ 2.1k` · Opinionated Claude Code defaults, documentation and workflows used at Trail of Bits.
- **[vibe-coding-toolkit](https://github.com/soumatheusgomes/vibe-coding-toolkit)** `★ 2.1k` · Curated AI-coding toolkit with Claude Code plugins, subagent orchestration and quality gates.
- **[everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh)** `★ 2k` · Chinese translation of everything-claude-code with agents, skills, hooks, commands and rules.
- **[claude-code-settings](https://github.com/feiskyer/claude-code-settings)** `★ 1.7k` · Curated skills, sub-agents and config templates for Claude Code.
- **[claude-workflow-v2](https://github.com/CloudAI-X/claude-workflow-v2)** `★ 1.4k` · Workflow plugin for Claude Code that bundles agents, skills, hooks and commands.
- **[claude-codex-settings](https://github.com/fcakyon/claude-codex-settings)** `★ 1.2k` · Configs, plugins, hooks and agents for Claude Code, Codex and Cursor, with Kimi, MiniMax and GLM.
- **[jarrodwatts/claude-code-config](https://github.com/jarrodwatts/claude-code-config)** `★ 1.1k` · Personal Claude Code setup with rules, hooks, agents, skills and commands.
- **[claude-config](https://github.com/solatis/claude-config)** `★ 914` · Personal Claude Code customizations and configuration.
- **[claude-forge](https://github.com/sangrokjung/claude-forge)** `★ 866` · Claude Code setup with 16 agents, 35 commands, 32 skills and 21 safety hooks in one install.
- **[claude-modular](https://github.com/oxygen-fragment/claude-modular)** `★ 285` · Modular Claude Code framework with 30+ commands, token optimization and MCP integration.
- **[meridian](https://github.com/markmdev/meridian)** `★ 188` · Zero-config Claude Code setup with task scaffolding, structured memory and persistent context.
- **[tpavanipradeep/everything-claude-code](https://github.com/tpavanipradeep/everything-claude-code)** `★ 164` · Copy of the everything-claude-code setup for Claude Code.
- **[rootstock-os](https://github.com/Mazhron/rootstock-os)** `★ 46` · Project operating system for Claude with lossless sessions, leaner tokens and a company of agents.
- **[dotfiles](https://github.com/atxtechbro/dotfiles)** `★ 28` · AI-orchestration dotfiles for parallel agents, enforced principles and self-healing setups.
- **[agentic-ai-starter-kit](https://github.com/robonuggets/agentic-ai-starter-kit)** `★ 22` · Beginner setup for Claude Code with a personalized CLAUDE.md, safety rails and two starter skills.

### Claude Code hooks, status lines and mods

- **[claude-hud](https://github.com/jarrodwatts/claude-hud)** `★ 29k` · **Top pick.** Plugin for Claude Code that shows context usage, active tools, running agents and todo progress.
- **[claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery)** `★ 4k` · Guide and examples for mastering Claude Code hooks.
- **[claude-code-prompt-improver](https://github.com/severity1/claude-code-prompt-improver)** `★ 2k` · Claude Code hook that turns vague prompts into precise ones.
- **[claude-dashboard](https://github.com/uppinote20/claude-dashboard)** `★ 583` · Status line plugin for Claude Code showing context use, API rate limits and cost.
- **[claude-auto-retry](https://github.com/cheapestinference/claude-auto-retry)** `★ 389` · Retries Claude Code automatically after subscription rate limits and API overload errors.
- **[effortless](https://github.com/HeyCubit/effortless)** `★ 284` · Mods for Claude Code that pick the reasoning effort per prompt and show the cache countdown.
- **[heard](https://github.com/heardlabs/heard)** `★ 215` · Local voice layer for Claude Code and Codex on macOS that reads your coding agent's progress aloud.
- **[claude-code-mods](https://github.com/ray-amjad/claude-code-mods)** `★ 98` · Mods for Claude Code: panes, bands, prompt guards, secret handling and memory tools.
- **[backtalk](https://github.com/jaredrhod/backtalk)** `★ 89` · Lets you talk to Claude Code out loud and hear its answers in a real voice.
- **[doctor-plus](https://github.com/robonuggets/doctor-plus)** `★ 86` · Claude Code health check that runs /doctor, then audits the workspace against Anthropic guidance.
- **[compaction-advisor](https://github.com/vignesh07/compaction-advisor)** `★ 17` · Monitors Claude Code context use so compaction does not interrupt tasks mid-way.
- **[jev-opus](https://github.com/WXK-AI/jev-opus)** `★ 16` · Claude Code plugin that re-decides Opus effort every step with Jev, keeping the prompt cache.
- **[hyperagents-plugin](https://github.com/Zpankz/hyperagents-plugin)** `★ 4` · Claude Code plugin for self-referential, self-improving agents inspired by Meta's HyperAgents paper.

### Codex and OpenCode add-ons

- **[codex-plugin-cc](https://github.com/openai/codex-plugin-cc)** `★ 34.7k` · Plugin that lets Claude Code use Codex to review code or delegate tasks.
- **[oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)** `★ 33.7k` · Codex extension that adds hooks, agent teams, HUDs and more.
- **[awesome-opencode](https://github.com/awesome-opencode/awesome-opencode)** `★ 10.8k` · Curated list of plugins, themes, agents, projects and resources for OpenCode.
- **[codex-desktop-linux](https://github.com/ilysenko/codex-desktop-linux)** `★ 3.9k` · Unofficial repackaging of OpenAI's Linux ChatGPT desktop app as deb, RPM, pacman, AppImage and Nix.
- **[lazycodex](https://github.com/code-yeongyu/lazycodex)** `★ 3.8k` · Codex agent harness for complex codebases with project memory, planning and verified completion.
- **[codex-host](https://github.com/BytePioneer-AI/codex-host)** `★ 3k` · Runs Pi and Claude Code directly inside Codex Desktop.
- **[codex-universal](https://github.com/openai/codex-universal)** `★ 1.1k` · Base Docker image used in Codex environments.
- **[opencode-lmstudio](https://github.com/agustif/opencode-lmstudio)** `★ 156` · OpenCode plugin that detects LM Studio and discovers its models dynamically.

### Copilot, Cursor, Gemini and Antigravity add-ons

- **[awesome-copilot](https://github.com/github/awesome-copilot)** `★ 40.5k` · Community instructions, agents, skills and configurations for GitHub Copilot.
- **[plugins](https://github.com/cursor/plugins)** `★ 14.5k` · Cursor plugin specification and official plugins.
- **[copilot-sdk](https://github.com/github/copilot-sdk)** `★ 10.6k` · Multi-platform SDK for embedding the GitHub Copilot agent in apps and services.
- **[ag-kit](https://github.com/vudovn/ag-kit)** `★ 8.2k` · Antigravity-first kit with rules, skills, specialist agents, workflows, memory and a safety hook.
- **[vibe-tools](https://github.com/eastlondoner/vibe-tools)** `★ 4.8k` · Gives Cursor Agent an AI team and advanced skills.
- **[deepseek-v4-for-copilot](https://github.com/Vizards/deepseek-v4-for-copilot)** `★ 1.5k` · Adds DeepSeek V4 to the Copilot Chat model picker.
- **[copilot-plugins](https://github.com/github/copilot-plugins)** `★ 379` · Official Copilot plugin collection with MCP servers, skills and hooks.
- **[gemini-kit](https://github.com/nth5693/gemini-kit)** `★ 370` · 19 agents and 44 commands for Gemini CLI covering planning, testing and review.
- **[oh-my-githubcopilot](https://github.com/jmstar85/oh-my-githubcopilot)** `★ 162` · Harness for GitHub Copilot in VS Code with 28+ agents, 30+ skills and hooks.
- **[everything-antigravity](https://github.com/krishnakanthb13/everything-antigravity)** `★ 97` · Collection of agents, task skills and coding rules for Google Antigravity.

<sub><a href="#contents">back to contents</a></sub>

## Accounts and usage

Switch accounts and watch the bill.

### Account and provider switchers

- **[cc-switch](https://github.com/farion1231/cc-switch)** `★ 149.7k` · **Top pick.** Cross-platform desktop app that switches providers and configs for Claude Code, Codex and OpenCode.
- **[cc-switch-cli](https://github.com/SaladDay/cc-switch-cli)** `★ 5.4k` · CLI that switches providers and configs across Claude Code, Codex and Gemini CLI.
- **[codex-provider-sync](https://github.com/Dailin521/codex-provider-sync)** `★ 3.6k` · Syncs Codex session provider metadata across rollout files and SQLite state.
- **[cc-mirror](https://github.com/numman-ali/cc-mirror)** `★ 2.3k` · Creates isolated Claude Code variants with custom providers such as Z.ai, MiniMax and OpenRouter.
- **[codex-switcher](https://github.com/Lampese/codex-switcher)** `★ 908` · Desktop app for managing multiple OpenAI Codex CLI accounts.
- **[agentic-flow](https://github.com/ruvnet/agentic-flow)** `★ 831` · Lets Claude Code and the Agent SDK switch between alternative low-cost AI models.
- **[claude-code-switch](https://github.com/foreveryh/claude-code-switch)** `★ 667` · One-command model switcher for Claude Code on the Anthropic API.
- **[opencode-multi-auth-codex](https://github.com/floze-the-genius/opencode-multi-auth-codex)** `★ 188` · OpenCode account routing, session controls, dashboard and reliability tooling for Codex OAuth.

### Usage, quota and cost monitors

- **[CodexBar](https://github.com/steipete/CodexBar)** `★ 22.9k` · **Top pick.** Shows usage stats for OpenAI Codex and Claude Code without having to log in.
- **[Claude-Code-Usage-Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor)** `★ 8.8k` · **Top pick.** Real-time Claude Code usage monitor with predictions and warnings.
- **[cost-xray](https://github.com/tigerless-labs/cost-xray)** `★ 5.9k` · Shows what Claude Code and Codex send to the API and what each part costs.
- **[robinebers/openusage](https://github.com/robinebers/openusage)** `★ 4.5k` · Open-source monitor for subscription usage across Claude, Codex, Copilot and Cursor.
- **[AI-Engineering-Coach](https://github.com/microsoft/AI-Engineering-Coach)** `★ 4.4k` · Microsoft dashboard that reads local AI coding session logs and scores habits and anti-patterns.
- **[EchoBird](https://github.com/edison7009/EchoBird)** `★ 3.5k` · Manages ChatGPT, Codex CLI and Claude Code accounts and tracks quota in one place.
- **[AntigravityQuotaWatcher](https://github.com/wusimpl/AntigravityQuotaWatcher)** `★ 2.3k` · Plugin that watches your Google Antigravity AI model quota.
- **[sniffly](https://github.com/chiphuyen/sniffly)** `★ 1.3k` · Claude Code dashboard with usage statistics, error analysis and a shareable view.
- **[onWatch](https://github.com/onllm-dev/onWatch)** `★ 764` · Tracks AI API quotas for Claude Code, Codex, Copilot, Antigravity, Z.ai and Synthetic in real time.
- **[token-dashboard](https://github.com/nateherkai/token-dashboard)** `★ 748` · Turns Claude Code JSONL transcripts into local token cost analytics and hotspot views.
- **[ai-usagebar](https://github.com/akitaonrails/ai-usagebar)** `★ 728` · Rust waybar widget that shows plan and credit status for Claude, GPT, GLM and OpenRouter.
- **[usage](https://github.com/aqua5230/usage)** `★ 343` · Menu bar app showing quota, burn rate and cost for Claude Code, Codex, Antigravity and Grok CLI.
- **[tokens](https://github.com/missuo/tokens)** `★ 282` · CLI and web leaderboard to track and compare AI coding-assistant token usage.
- **[janekbaraniewski/openusage](https://github.com/janekbaraniewski/openusage)** `★ 236` · Dashboard that tracks spend and usage across Claude, Cursor, OpenRouter, Copilot and more.
- **[Clawdmeter](https://github.com/weltern/Clawdmeter)** `★ 32` · Cross-platform desktop dashboard for Claude Code usage with live session and weekly limits.
- **[tokens-on-track](https://github.com/gnibu/tokens-on-track)** `★ 19` · Menu bar app that tracks Claude Code and Codex quota usage and pace.

<sub><a href="#contents">back to contents</a></sub>

## Parallel agents

Run many coding agents at once without losing track.

### Parallel worktrees and boards

- **[orca](https://github.com/stablyai/orca)** `★ 109.1k` · **Top pick.** Workspace for a fleet of coding and personal agents on desktop, mobile and remote runtimes.
- **[vibe-kanban](https://github.com/BloopAI/vibe-kanban)** `★ 28.5k` · **Top pick.** Kanban task manager for running Claude Code, Codex or other coding agents.
- **[multica](https://github.com/multica-ai/multica)** `★ 54.1k` · Self-hostable, source-available workspace where AI coding agents pick up issues like teammates.
- **[Paradev](https://github.com/ParadevAI/Paradev)** `★ 15.7k` · Agentic IDE, formerly Superset, that runs 100+ coding agents in parallel.
- **[agent-orchestrator](https://github.com/OrchestratorInc/agent-orchestrator)** `★ 13.8k` · Plans, runs and supervises fleets of agents from task to merged PR.
- **[worktrunk](https://github.com/max-sixty/worktrunk)** `★ 9.5k` · Git worktree CLI for running parallel AI coding agents.
- **[claude-squad](https://github.com/smtg-ai/claude-squad)** `★ 8.7k` · Manages multiple AI terminal agents such as Claude Code, Codex, OpenCode and Amp.
- **[firstmate](https://github.com/kunchenguid/firstmate)** `★ 8.4k` · Lead agent that spawns and supervises a crew of coding agents, each in a clean git worktree.
- **[ccmanager](https://github.com/kbwo/ccmanager)** `★ 1.3k` · Session manager for coding agents such as Claude Code, Gemini CLI, Codex CLI and Cursor Agent.
- **[parallel-code](https://github.com/johannesjo/parallel-code)** `★ 1.1k` · Runs Claude Code, Codex and Gemini side by side, each in its own git worktree.
- **[EnsoAI](https://github.com/J3n5en/EnsoAI)** `★ 998` · Desktop app that runs Claude, Gemini and Codex side by side, each branch in its own git worktree.
- **[luvus](https://github.com/RizRiyz/luvus)** `★ 986` · Rust terminal workspace that runs, watches and coordinates AI coding agents in panes and worktrees.
- **[shep](https://github.com/shep-ai/shep)** `★ 269` · CLI that runs parallel coding agents in git worktrees, with built-in memory and an SDD flow.
- **[operator-oss](https://github.com/iishyfishyy/operator-oss)** `★ 208` · Runs many Claude Code or Codex sessions in parallel across projects from one screen.
- **[learning-cmux-with-agents](https://github.com/disler/learning-cmux-with-agents)** `★ 117` · 31 prompts showing one primary agent can stand up, drive and tear down a fleet of coding agents.
- **[100x-orchestrator](https://github.com/aj47/100x-orchestrator)** `★ 98` · Orchestrates AI coding agents that use Aider to handle the coding work.
- **[proletariat](https://github.com/chrismcdermut/proletariat)** `★ 36` · Agent orchestration CLI that runs coding agents in isolated git branches and Docker containers.
- **[yardsort](https://github.com/joaoh82/yardsort)** `★ 13` · Desktop app that runs coding agents in parallel worktrees and hands work between them.

### Desktop and web workbenches

- **[t3code](https://github.com/pingdotgg/t3code)** `★ 31.2k` · Control surface for Claude Code, Codex, Cursor and other coding agents on desktop, web and mobile.
- **[opcode](https://github.com/winfunc/opcode)** `★ 22.4k` · GUI app and toolkit for Claude Code to create custom agents and manage sessions.
- **[paseo](https://github.com/getpaseo/paseo)** `★ 22.3k` · Orchestrates multiple coding agents from desktop and mobile apps.
- **[humanlayer](https://github.com/humanlayer/humanlayer)** `★ 12.7k` · Human-in-the-loop tooling that helps AI coding agents solve hard problems in complex codebases.
- **[openchamber](https://github.com/openchamber/openchamber)** `★ 12.3k` · Agentic development environment built on the OpenCode agent.
- **[openrig](https://github.com/mvschwarz/openrig)** `★ 8.3k` · Defines teams of Claude Code, Codex and Pi agents in YAML and runs them as one persistent rig.
- **[CodePilot](https://github.com/op7418/CodePilot)** `★ 6.5k` · Multi-model AI agent desktop client with MCP and skills, controllable from your phone.
- **[tuios](https://github.com/Gaurav-Gosain/tuios)** `★ 6.2k` · Terminal window manager that tracks what coding agents are doing, with one agent inbox.
- **[desktop-cc-gui](https://github.com/zhukunpenglinyutong/desktop-cc-gui)** `★ 4.5k` · Tauri desktop client that runs Claude Code, Codex, Gemini, OpenCode and DeepSeek Harness in one GUI.
- **[codeg](https://github.com/spacering-net/codeg)** `★ 4.2k` · Multi-agent coding workspace that aggregates sessions from Claude Code, Codex, OpenCode and Pi.
- **[HolyClaude](https://github.com/CoderLuii/HolyClaude)** `★ 2.6k` · AI coding workstation with Claude Code, a web UI, 8 AI CLIs, a headless browser and 50+ tools.
- **[nodeterm](https://github.com/eneskirca/nodeterm)** `★ 2.1k` · Node-based terminal manager that runs parallel AI coding agent sessions as draggable nodes.
- **[happier](https://github.com/happier-dev/happier)** `★ 2.1k` · Web, desktop and mobile client and orchestrator for Codex, Claude Code, OpenCode, Pi and more.
- **[opensessions](https://github.com/Ataraxy-Labs/opensessions)** `★ 1.2k` · Sidebar for tmux showing live session status for Amp, Claude Code, Codex and OpenCode.
- **[Pivo](https://github.com/AgentsMesh/Pivo)** `★ 1.1k` · Task-focused development environment with a Kanban board, a terminal and AI assistance.
- **[voicetree](https://github.com/voicetreelab/voicetree)** `★ 936` · Spatial IDE for recursive multi-agent orchestration, built like a graph view you work inside.
- **[Codeman](https://github.com/Ark0N/Codeman)** `★ 823` · Self-hosted mission control for running Claude Code, OpenCode, Pi, Codex and Gemini CLI.
- **[hive](https://github.com/tt-a1i/hive)** `★ 580` · Browser-based workspace where Claude Code, Codex, Gemini and OpenCode collaborate as PTY processes.
- **[VibeAround](https://github.com/jazzenchen/VibeAround)** `★ 530` · Launches Claude Code, Codex CLI, Gemini CLI, Pi Agent and more from one place.
- **[wmux](https://github.com/openwong2kim/wmux)** `★ 437` · Agent development environment that multiplexes terminals, git worktrees and browsers for agents.
- **[keel](https://github.com/codejunkie99/keel)** `★ 337` · Local-first macOS coding workspace using local Laya and optional Jev for decision selection.
- **[bettercode](https://github.com/kerim0x1/bettercode)** `★ 261` · Desktop workspace that runs Claude Code, Codex, Cursor Agent and Grok side by side.
- **[canopy](https://github.com/Miosa-osa/canopy)** `★ 233` · Desktop workspace that keeps terminal sessions, agent runtimes and git worktrees across restarts.
- **[realm](https://github.com/31Carlton7/realm)** `★ 118` · Local-first macOS workspace and control plane for running all your coding agents in one place.
- **[campfire](https://github.com/stretchcloud/campfire)** `★ 100` · Collaborative web platform for AI coding agents, with collective intelligence layers.
- **[gastown-gui](https://github.com/web3dev1337/gastown-gui)** `★ 95` · Web GUI for the Gas Town multi-agent orchestrator.
- **[flow](https://github.com/samyakkkk/flow)** `★ 74` · Workspace for coding agents that captures each session into a searchable project brain.
- **[coven](https://github.com/OpenCoven/coven)** `★ 73` · Local runtime that runs Codex, Claude Code and Copilot CLI sessions inside project boundaries.
- **[openfde](https://github.com/memovai/openfde)** `★ 58` · AI workspace for forward-deployed engineers that runs Claude Code or Codex in task worktrees.
- **[autoharness](https://github.com/codejunkie99/autoharness)** `★ 37` · macOS coding-agent control center that routes one objective to a loop, a swarm or a task graph.
- **[coven-cave](https://github.com/OpenCoven/coven-cave)** `★ 31` · Native workspace for familiars, agent sessions, memory, tools and workflows.

### Mobile and web access

- **[claudecodeui](https://github.com/siteboon/claudecodeui)** `★ 14.3k` · **Top pick.** Open-source web UI to run and manage Claude Code, Codex, Cursor CLI and OpenCode remotely.
- **[hapi](https://github.com/tiann/hapi)** `★ 5.3k` · App to run and watch Codex, Claude Code, OpenCode and other coding agents from anywhere.
- **[vibetunnel](https://github.com/amantus-ai/vibetunnel)** `★ 4.7k` · Turns any browser into a terminal so you can command your agents on the go.
- **[chums](https://github.com/lcoutodemos/chums)** `★ 275` · Apple Watch and iPhone app to talk to Claude Code and Codex agents, each shown as a character.
- **[tlive](https://github.com/y49/tlive)** `★ 215` · Self-hosted remote approvals and live monitoring for Claude Code and Codex via Telegram or web.

### Background and cloud runners

- **[gastown](https://github.com/gastownhall/gastown)** `★ 18.6k` · Multi-agent workspace manager for running many coding agents together.
- **[background-agents](https://github.com/ColeMurray/background-agents)** `★ 3.4k` · Open-source system for running coding agents in the background in the cloud.
- **[cloudroom](https://github.com/davidondrej/cloudroom)** `★ 1.1k` · Self-hostable Rust runtime that runs Claude Code, Codex and Pi in the cloud.
- **[helixml/helix](https://github.com/helixml/helix)** `★ 824` · Private agent fleet with spec coding where each agent gets its own GPU-accelerated desktop.
- **[gastown-remote](https://github.com/numman-ali/gastown-remote)** `★ 38` · Deploys Gas Town to a VPS for always-on agent orchestration, reachable over Tailscale.

### Councils and second opinions

- **[claude-octopus](https://github.com/nyldn/claude-octopus)** `★ 4.3k` · Runs several AI models on the same task and surfaces their disagreements before shipping.
- **[claude_codex_bridge](https://github.com/SeemSeam/claude_codex_bridge)** `★ 3.6k` · Visible multi-agent CLI workspace that mixes Codex, Claude, Gemini and other agent CLIs.
- **[delegate-skills](https://github.com/amElnagdy/delegate-skills)** `★ 2.5k` · Skills that hand a coding task to another agent CLI so you review the diff and land the commit.
- **[skill-codex](https://github.com/skills-directory/skill-codex)** `★ 1.5k` · Claude Code skill that delegates prompts to Codex.
- **[claude-council](https://github.com/hex/claude-council)** `★ 911` · Claude Code plugin that asks several AI coding agents one question and shows answers side by side.
- **[squad](https://github.com/mco-org/squad)** `★ 837` · Terminal tool for collaboration between multiple AI agents.
- **[mco](https://github.com/mco-org/mco)** `★ 541` · CLI that runs several coding agents and models in parallel and compares their raw answers.
- **[oh-my-subagents](https://github.com/ringlochid/oh-my-subagents)** `★ 190` · Local subagent orchestration for Codex and Claude with persistent task state and reusable teams.
- **[kimi-first](https://github.com/boringmarketer/kimi-first)** `★ 50` · Claude Code skill that hands implementation work to the Kimi Code CLI and verifies the result.
- **[sync](https://github.com/AgriciDaniel/sync)** `★ 29` · Evidence-gated council orchestration between Claude and Codex.
- **[aqua](https://github.com/vignesh07/aqua)** `★ 25` · Agent-agnostic coordinator for CLI AI agents such as Claude Code and Codex.

<sub><a href="#contents">back to contents</a></sub>

## Specs, loops and factories

Turn agents into a repeatable delivery pipeline.

### Specs and task plans

- **[spec-kit](https://github.com/github/spec-kit)** `★ 143.7k` · **Top pick.** Toolkit for spec-driven development with coding agents.
- **[OpenSpec](https://github.com/Fission-AI/OpenSpec)** `★ 73.3k` · Spec-driven development for AI coding assistants.
- **[claude-task-master](https://github.com/eyaltoledano/claude-task-master)** `★ 28.3k` · AI-powered task management system for Cursor, Lovable, Windsurf, Roo and other agents.
- **[planning-with-files](https://github.com/OthmanAdi/planning-with-files)** `★ 27.7k` · Persistent markdown plans for coding agents that survive crashes and recover sessions.
- **[Trellis](https://github.com/mindfold-ai/Trellis)** `★ 15k` · Engineering framework for AI coding that keeps specs, tasks and memory in the repo for any agent.
- **[agent-os](https://github.com/buildermethods/agent-os)** `★ 5.6k` · Injects your codebase standards into coding agents and helps write better specs.
- **[OpenAgentsControl](https://github.com/darrenhinde/OpenAgentsControl)** `★ 5k` · Agent framework for plan-first development workflows with approval-based execution, for OpenCode.
- **[claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow)** `★ 3.9k` · Spec-driven development workflows for Claude Code, from requirements to design to tasks.
- **[claudex-loop](https://github.com/chaseai-yt/claudex-loop)** `★ 3.3k` · Claude Code skill for four-phase plan hardening, starting with recon and interrogation.
- **[vibecode-pro-max-kit](https://github.com/withkynam/vibecode-pro-max-kit)** `★ 1.2k` · Spec-driven coding harness that gives AI coding agents lasting project memory.
- **[ai-factory](https://github.com/lee-to/ai-factory)** `★ 1.1k` · CLI that installs skills, MCP servers and a spec-driven workflow for many coding agents.
- **[ProductSpec](https://github.com/gokulrajaram/ProductSpec)** `★ 313` · Open standard for describing software intent so AI agents can build from it.

### Plans and task trackers for agents

- **[beads](https://github.com/gastownhall/beads)** `★ 28.3k` · **Top pick.** Task tracker that gives coding agents a persistent memory of their work.
- **[cursor-memory-bank](https://github.com/vanzan01/cursor-memory-bank)** `★ 3.1k` · Modular Cursor custom-mode framework (VAN, PLAN, CREATIVE, IMPLEMENT) with persistent memory.
- **[itsaplan](https://github.com/croffasia/itsaplan)** `★ 2.1k` · Self-hosted Linear alternative where AI agents take issues on the same board as people.
- **[paca](https://github.com/Paca-AI/paca)** `★ 2k` · Self-hosted Scrum board where people and AI agents share sprints, with an MCP server and skills.
- **[cursor-agent-tracking](https://github.com/TechMitten/cursor-agent-tracking)** `★ 136` · Structured system for keeping context and tracking changes in Cursor agent-mode conversations.
- **[pebbles](https://github.com/Martian-Engineering/pebbles)** `★ 34` · Super simple task management for agents, a lighter take on beads.
- **[stellr](https://github.com/teloverge/stellr)** `★ 1` · Interactive star-map of GitHub issues with an agent multiplexer to work them, in Rust and Tauri.

### Agent loops

- **[loop-engineering](https://github.com/cobusgreyling/loop-engineering)** `★ 11.7k` · Patterns, starters and CLI tools for loop engineering with AI coding agents.
- **[ralph-claude-code](https://github.com/frankbria/ralph-claude-code)** `★ 9.7k` · Autonomous development loop for Claude Code that detects when to exit.
- **[loopx](https://github.com/loopx-project/loopx)** `★ 6.5k` · Local-first control plane and workbench that turns long-horizon goals into verifiable results.
- **[ouroboros](https://github.com/Q00/ouroboros)** `★ 6.3k` · Agent OS for AI coding workflows with interview gates, staged evaluation and an evolution loop.
- **[loopy](https://github.com/Forward-Future/loopy)** `★ 3.2k` · Library of practical agent loops plus an installable skill to find, adapt and design them.
- **[PolyArch/humanize](https://github.com/PolyArch/humanize)** `★ 1.6k` · Claude Code plugin for Ralph-style loops with independent Codex review, called RLCR.
- **[loom](https://github.com/valkor-ai/loom)** `★ 1.3k` · Delivery plugin for Codex, Claude Code and OpenCode that plans, builds, checks and repairs a change.
- **[skills](https://github.com/AI-Builder-Club/skills)** `★ 1.3k` · Claude Code skills for codebase harnesses and loop engineering.
- **[gauntlet-loop](https://github.com/robonuggets/gauntlet-loop)** `★ 1.2k` · Turns a goal into a prompt that makes an agent set a quality bar and run builder and critic pairs.
- **[ralph-loop-agent](https://github.com/vercel-labs/ralph-loop-agent)** `★ 843` · Continuous autonomy loop agent for the AI SDK.
- **[codex-autoresearch](https://github.com/TheGreenCedar/codex-autoresearch)** `★ 836` · Codex plugin that runs optimization loops against a measurable target inside a codebase.
- **[architect-loop](https://github.com/DanMcInerney/architect-loop)** `★ 627` · Goal loop where a stronger model designs and reviews while a cheaper model builds.
- **[infinite-agentic-loop](https://github.com/disler/infinite-agentic-loop)** `★ 620` · Experiment showing an infinite agentic loop built from two prompts in Claude Code.
- **[humanfia/humanize](https://github.com/humanfia/humanize)** `★ 362` · Agent flow system for coding agents such as Claude Code and Codex, built for heavy token use.
- **[githubnext/autoloop](https://github.com/githubnext/autoloop)** `★ 81` · Runs agent loops in a repo to automate research, development and maintenance.
- **[mikeyobrien/autoloop](https://github.com/mikeyobrien/autoloop)** `★ 73` · Loop harness for long-running agent work with inspectable runs and presets.
- **[AutoPMF](https://github.com/fabriciobloisi/AutoPMF)** `★ 51` · AI news app with an AutoLoop for product-market fit, steered by ControlNews.md and run on Claude.
- **[menonpg/autoloop](https://github.com/menonpg/autoloop)** `★ 41` · Autoresearch-style loop for autonomous, iterative improvement of any system.
- **[gauntlet-loop-brain](https://github.com/AgriciDaniel/gauntlet-loop-brain)** `★ 15` · Evidence-gated Obsidian knowledge base for bounded multi-agent improvement loops.
- **[sweekuh/autoloop](https://github.com/sweekuh/autoloop)** `★ 6` · Claude Code skill that optimizes any artifact you can score with a command.
- **[helix-loops](https://github.com/caramaschiHG/helix-loops)** `★ 5` · Self-evolving skill for Claude Code and Gemini CLI that creates and manages Ralph-style loops.
- **[agent-playground](https://github.com/Wellux/agent-playground)** `★ 1` · Scheduled Claude Code loops that turn agent traces into vault notes, skills and A/B-tested prompts.

### Software factories

- **[Archon](https://github.com/coleam00/Archon)** `★ 23.8k` · **Top pick.** Open-source harness builder that makes AI coding deterministic and repeatable.
- **[claude-code-action](https://github.com/anthropics/claude-code-action)** `★ 9.7k` · GitHub Action that runs Claude Code on issues and pull requests.
- **[superplane](https://github.com/superplanehq/superplane)** `★ 8.4k` · Open-source factory for one-shot engineering with coding agents.
- **[gh-aw](https://github.com/github/gh-aw)** `★ 5.5k` · Agentic workflows that run coding agents inside GitHub Actions.
- **[fabro](https://github.com/fabro-sh/fabro)** `★ 1.8k` · Open-source dark software factory for expert engineers.
- **[Fusion](https://github.com/Runfusion/Fusion)** `★ 1.3k` · Software factory of multi-node agents that build software around the clock.
- **[eve-software-factory-template](https://github.com/vercel-labs/eve-software-factory-template)** `★ 1.2k` · Template for Foreman, an eve software factory.
- **[super-simple-software-factory](https://github.com/disler/super-simple-software-factory)** `★ 1k` · Agents-plus-code workflows packaged as one skill that can be stamped into any repo.
- **[foreman](https://github.com/thruwire/foreman)** `★ 793` · Supervisor that watches coding agents such as Codex and OpenCode with decision models.
- **[ai-software-factory](https://github.com/coleam00/ai-software-factory)** `★ 453` · Software factory where you plan the release, agents build and review it, and you test in staging.
- **[agentops](https://github.com/boshu2/agentops)** `★ 450` · DevOps-style discipline for coding agents: shape the work, track it as a graph, judge each change.
- **[Finn-loop](https://github.com/finna/Finn-loop)** `★ 321` · Three-skill AI software factory for Claude Code covering spec, build and review.
- **[factory](https://github.com/addyosmani/factory)** `★ 304` · Reference software factory for Claude Code and Codex.
- **[agentic-os](https://github.com/KbWen/agentic-os)** `★ 223` · Governance framework that runs AI coding agents through plan, build, review, test and ship steps.
- **[production-grade](https://github.com/nagisanzenin/production-grade)** `★ 181` · Claude Code plugin with 14 skills that run an autonomous SaaS build pipeline.
- **[dark-factory-experiment](https://github.com/coleam00/dark-factory-experiment)** `★ 172` · Repository that ships its own code through AI workflows that triage, implement, review and merge.
- **[great_cto](https://github.com/avelikiy/great_cto)** `★ 108` · Runs Claude Code as a pipeline of 70 specialist agents.
- **[DeployBot](https://github.com/Forward-Future/DeployBot)** `★ 44` · Agent-managed GitHub merge queue for Codex, Claude Code, Cursor and MCP clients.
- **[software-factory](https://github.com/PromtEngineer/software-factory)** `★ 22` · Claude Code agents turn GitHub issues into reviewed pull requests on Upstash Box.
- **[factory-mission-control](https://github.com/coleam00/factory-mission-control)** `★ 10` · Hub for the AI Software Factory covering its architecture, evolution, PRDs and issues.
- **[port-factory-smoke](https://github.com/coleam00/port-factory-smoke)** `★ 2` · Throwaway smoke test of the AI Software Factory running on Codex with Port.

<sub><a href="#contents">back to contents</a></sub>

## Review, tests and provenance

Catch what agents wrote before it ships.

### AI code review

- **[open-code-review](https://github.com/alibaba/open-code-review)** `★ 48.8k` · **Top pick.** Alibaba's code review tool that combines deterministic pipelines with an LLM agent.
- **[pr-agent](https://github.com/The-PR-Agent/pr-agent)** `★ 13.7k` · **Top pick.** Open-source AI pull request reviewer that works with OpenAI, Anthropic and Ollama models.
- **[defending-code-reference-harness](https://github.com/anthropics/defending-code-reference-harness)** `★ 7.7k` · Skills and an autonomous harness for threat modeling, scanning, triage and patching.
- **[opencommit](https://github.com/di-sukharev/opencommit)** `★ 7.5k` · CLI that writes git commit messages with an LLM, including Claude, GPT and local Ollama models.
- **[claude-code-security-review](https://github.com/anthropics/claude-code-security-review)** `★ 6.6k` · GitHub Action in which Claude reviews code changes for security vulnerabilities.
- **[dmmulroy/anti-slop](https://github.com/dmmulroy/anti-slop)** `★ 5.7k` · Opinionated Oxlint rules that reject low-evidence TypeScript and JavaScript patterns.
- **[ChatGPT-CodeReview](https://github.com/anc95/ChatGPT-CodeReview)** `★ 4.5k` · Probot code review bot powered by ChatGPT.
- **[sentrux](https://github.com/sentrux/sentrux)** `★ 3.3k` · Real-time architecture sensor that gives AI agents feedback on code quality.
- **[mantis](https://github.com/google/mantis)** `★ 2.7k` · Toolkit that lets coding agents find, reproduce and patch vulnerabilities on their own.
- **[pr-lens](https://github.com/coldteadotai/pr-lens)** `★ 2.3k` · Draws each pull request as animated architecture and data-flow walkthroughs for faster review.
- **[pullfrog](https://github.com/pullfrog/pullfrog)** `★ 1.4k` · Open-source, model-agnostic AI GitHub bot that runs in GitHub Actions with your own API keys.
- **[peakoss/anti-slop](https://github.com/peakoss/anti-slop)** `★ 849` · GitHub action that detects and automatically closes low-quality and AI slop pull requests.
- **[jev-review](https://github.com/devagrawal09/jev-review)** `★ 691` · Staged code-review workflow with a local dashboard, built with TypeSafe Jev.
- **[ai-review](https://github.com/Nikita-Filonov/ai-review)** `★ 600` · AI code review tool for GitHub, GitLab, Bitbucket, Azure DevOps and Gitea.
- **[AsyncReview](https://github.com/AsyncFuncAI/AsyncReview)** `★ 460` · Agentic code review tool inspired by DevinReview that uses Recursive Language Models.
- **[entrix](https://github.com/phodal/entrix)** `★ 105` · Turns quality rules and architecture constraints into executable guardrails for code changes.
- **[jev-belay](https://github.com/valentynkit/jev-belay)** `★ 41` · Claude Code Stop hook that blocks an unverified done by checking transcript evidence with Jev.
- **[jev-commit](https://github.com/valentynkit/jev-commit)** `★ 16` · Pre-commit hook where one Jev call checks the commit message against the diff.

### Testing and QA agents

- **[artemis](https://github.com/google/artemis)** `★ 15.5k` · Google tool that turns natural-language instructions into end-to-end Android test automation.
- **[e2e](https://github.com/tester-army/e2e)** `★ 12.1k` · End-to-end testing framework where an agent drives web and mobile apps from natural-language goals.
- **[testsprite-cli](https://github.com/TestSprite/testsprite-cli)** `★ 5.1k` · Official TestSprite CLI for AI-powered automated testing from the terminal.
- **[qawolf/cli](https://github.com/qawolf/cli)** `★ 3.5k` · QA Wolf end-to-end testing from your terminal, CI or AI agent.
- **[reticle](https://github.com/reticlehq/reticle)** `★ 1.3k` · Lets AI coding agents understand and verify the apps they build.
- **[agent-qa](https://github.com/vostride/agent-qa)** · Tests web, Android and iOS apps through CLI/MCP with persistent memidex memory, validated self-improvement and reviewable run evidence.
- **[bowser](https://github.com/disler/bowser)** `★ 268` · Agentic browser automation and UI testing system built from composable skills and subagents.

### Sessions and provenance

- **[entireio/cli](https://github.com/entireio/cli)** `★ 5.3k` · **Top pick.** Hooks into Git to capture AI agent sessions and index them alongside commits.
- **[atlas](https://github.com/pacifio/atlas)** `★ 9.6k` · Source control for agents: run several coding agents and track and query their changes in one place.
- **[claude-tap](https://github.com/liaohch3/claude-tap)** `★ 3.3k` · Intercepts and inspects API traffic from coding agents like Claude Code, Codex CLI and Gemini CLI.
- **[git-ai](https://github.com/git-ai-project/git-ai)** `★ 2.9k` · Git extension that tracks which code in a repo was written by AI.
- **[gateway-skills](https://github.com/Leanmcp/gateway-skills)** `★ 2.1k` · Drop-in AI gateway and skills that log each Claude Code request, file and token in a dashboard.
- **[dataclaw](https://github.com/peteromallet/dataclaw)** `★ 2.1k` · Agent harness that publishes your agent chat history as Hugging Face datasets.
- **[claude-code-transcripts](https://github.com/simonw/claude-code-transcripts)** `★ 1.7k` · Tools for publishing transcripts of Claude Code sessions.
- **[claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability)** `★ 1.6k` · Real-time monitoring of Claude Code agents through simple hook event tracking.
- **[cc-viewer](https://github.com/weiesky/cc-viewer)** `★ 1.1k` · Captures and visualizes Claude Code API requests and responses in real time.
- **[agent-git](https://github.com/Einsia/agent-git)** `★ 414` · Version control for agent sessions.
- **[brain0](https://github.com/Brain0-ai/brain0)** `★ 314` · Decision graph that links every commit to the agent prompts behind it.
- **[codex-rewind](https://github.com/extracurricular-ai/codex-rewind)** `★ 56` · Unofficial Codex CLI build that adds /rewind and /redo to restore files, not just conversations.
- **[ccsession](https://github.com/sorafujitani/ccsession)** `★ 51` · Picker built on fzf that resumes any past Claude Code session from its original directory.
- **[claude-code-rewind](https://github.com/holasoymalva/claude-code-rewind)** `★ 30` · Time machine for Claude Code sessions with automatic snapshots, rollbacks and visual diffs.
- **[claudereview](https://github.com/vignesh07/claudereview)** `★ 21` · CLI and web service to share encrypted Claude Code, Codex and Gemini CLI sessions.

<sub><a href="#contents">back to contents</a></sub>

## Code context

Feed agents the code and docs they need.

### Code graphs and intelligence

- **[serena](https://github.com/oraios/serena)** `★ 30.8k` · **Top pick.** MCP toolkit that gives coding agents IDE-like semantic code retrieval and editing.
- **[graphify](https://github.com/Graphify-Labs/graphify)** `★ 137.9k` · Turns a codebase with its docs, schemas and PDFs into a queryable knowledge graph.
- **[Understand-Anything](https://github.com/Egonex-AI/Understand-Anything)** `★ 88.8k` · Turns any code into an interactive knowledge graph you can explore and search.
- **[codegraph](https://github.com/colbymchenry/codegraph)** `★ 75.8k` · Pre-indexed code knowledge graph that auto-syncs on code changes for many coding agents.
- **[GitNexus](https://github.com/abhigyanpatwari/GitNexus)** `★ 48.1k` · Zero-server code intelligence engine that maps a codebase as a knowledge graph for agents.
- **[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** `★ 47.7k` · Local code intelligence connecting code, docs and infrastructure in a persistent graph for agents.
- **[code-review-graph](https://github.com/tirth8205/code-review-graph)** `★ 32.5k` · Local-first code intelligence graph that gives AI coding tools a persistent map of your codebase.
- **[Trail-Code](https://github.com/trailhq/Trail-Code)** `★ 10.9k` · Code graph and MCP server that gives Claude Code, Cursor, Codex and other agents codebase context.
- **[code-graph-rag](https://github.com/vitali87/code-graph-rag)** `★ 5.3k` · RAG over a knowledge graph that lets AI query and edit multi-language codebases.
- **[CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext)** `★ 4.4k` · MCP server and CLI that index local code into a graph database to give AI assistants context.
- **[SocratiCode](https://github.com/giancarloerra/SocratiCode)** `★ 3.4k` · Codebase intelligence with hybrid search and dependency graphs, as plugin, skill or MCP.
- **[aoci-code](https://github.com/aoci-spec/aoci-code)** `★ 1.8k` · Persistent, Git-versioned map of a codebase and its database schema for coding agents to read.
- **[sdl-mcp](https://github.com/GlitterKill/sdl-mcp)** `★ 496` · Symbol-graph context layer that keeps coding agents inside a token budget.
- **[compass](https://github.com/crabbuild/compass)** `★ 175` · Local-first knowledge graph engine for code and project artifacts, written in Rust.
- **[tree-sitter-analyzer](https://github.com/aimasteracc/tree-sitter-analyzer)** `★ 61` · Code-intelligence MCP for AI agents with call graphs and blast radius across 13 languages.
- **[IntentGraph](https://github.com/Raytracer76/IntentGraph)** `★ 27` · Turns a codebase into queryable function-level dependencies for AI coding agents.
- **[mastermind](https://github.com/xcrft/mastermind)** `★ 13` · Local-first repo context for coding agents: codegraph, cited knowledge and change impact.

### Semantic code search

- **[claude-context](https://github.com/zilliztech/claude-context)** `★ 12.7k` · Code search MCP server that makes an entire codebase available as context for coding agents.
- **[zvec-grep](https://github.com/zvec-ai/zvec-grep)** `★ 4.2k` · Local-first workspace search for humans and AI agents, with full-text and vector modes.
- **[jevgrep](https://github.com/dzhng/jevgrep)** `★ 3k` · CLI for coding agents that finds relevant files and source context by asking what code does.
- **[cocoindex-code](https://github.com/cocoindex-io/cocoindex-code)** `★ 3k` · Lightweight AST-based code search CLI that speeds up coding agents.
- **[osgrep](https://github.com/Ryandonofrio3/osgrep)** `★ 1.1k` · Open-source semantic grep that gives an AI agent search by meaning.
- **[sgrep](https://github.com/context-dot-dev/sgrep)** `★ 333` · Local plain-English search over code and documents for agents, with no hosted index.
- **[oce](https://github.com/oce-ai/oce)** `★ 127` · Self-hosted, ACE-compatible code retrieval service that indexes source files with cAST-aware chunks.
- **[autodev-codebase](https://github.com/anrgct/autodev-codebase)** `★ 121` · Code semantic search tool built on vector embeddings, with an MCP server and multi-model support.
- **[jegrep](https://github.com/can1357/jegrep)** `★ 119` · Semantic grep that finds code from a description, powered by Jev.

### Repo packers and live docs

- **[context7](https://github.com/upstash/context7)** `★ 63.9k` · **Top pick.** Platform and MCP server that serves up-to-date library docs to AI coding agents.
- **[repomix](https://github.com/yamadashy/repomix)** `★ 29.1k` · Packs an entire repository into a single AI-friendly file for use in prompts.
- **[deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open)** `★ 18.3k` · Open-source DeepWiki that generates AI wikis for GitHub, GitLab and Bitbucket repositories.
- **[openwiki](https://github.com/langchain-ai/openwiki)** `★ 17.6k` · CLI that writes and maintains agent documentation for your codebase.
- **[gitingest](https://github.com/coderamp-labs/gitingest)** `★ 16k` · Turns any GitHub URL into a prompt-friendly extract of a codebase.
- **[context-hub](https://github.com/andrewyng/context-hub)** `★ 14k` · CLI that gives coding agents curated, versioned API docs and lets them annotate gaps.
- **[code2prompt](https://github.com/mufeedvh/code2prompt)** `★ 7.7k` · CLI that converts a codebase into one LLM prompt with source tree, templating and token counts.
- **[packrun](https://github.com/midday-ai/packrun)** `★ 3.8k` · Package registry for AI agents with comparisons, scoring and an MCP server for Cursor and Claude.
- **[adrenaline](https://github.com/shobrook/adrenaline)** `★ 3.7k` · Chat interface that answers questions about a codebase and visualizes it.
- **[apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp)** `★ 1.4k` · MCP server for searching Apple Developer Documentation, WWDC videos and Swift APIs.
- **[better-context](https://github.com/davis7dotsh/better-context)** `★ 1.2k` · Gives coding agents up-to-date context on the libraries and technologies in a project.
- **[repoprompt-ce](https://github.com/repoprompt/repoprompt-ce)** `★ 972` · Native macOS context-engineering app for AI coding agents, with an MCP CLI.
- **[RepoToTextForLLMs](https://github.com/Doriandarko/RepoToTextForLLMs)** `★ 794` · Fetches a GitHub repository's READMEs, structure and non-binary files as text for LLM analysis.
- **[RepoToText](https://github.com/JeremiahPetersen/RepoToText)** `★ 579` · Turns an entire GitHub repo into one organized text file for use with LLMs.
- **[AutoDoc-ChatGPT](https://github.com/awekrx/AutoDoc-ChatGPT)** `★ 391` · Python script that uses ChatGPT to generate documentation for code automatically.
- **[GenerateAgents.md](https://github.com/originalankur/GenerateAgents.md)** `★ 259` · Generates an Agents.md for LLMs using DSPy's recursive language model.
- **[dash-mcp-server](https://github.com/Kapeli/dash-mcp-server)** `★ 188` · MCP server that gives agents access to Dash, the macOS API documentation browser.
- **[RepoChat-200k](https://github.com/chenran-627/RepoChat-200k)** `★ 170` · Chat with a GitHub repo through Claude's 200k context window instead of RAG.
- **[.better-coding-agents](https://github.com/bmdavis419/.better-coding-agents)** `★ 169` · Clones library source as git subtrees so coding agents can search it for answers.

### Token savers

- **[rtk](https://github.com/rtk-ai/rtk)** `★ 84.9k` · **Top pick.** CLI proxy that cuts the tokens agents spend on dev commands.
- **[caveman](https://github.com/JuliusBrussee/caveman)** `★ 115.8k` · Skill and proxy that cuts coding-agent tokens by about 65% by talking like a caveman.
- **[headroom](https://github.com/headroomlabs-ai/headroom)** `★ 78.2k` · Compresses tool outputs, logs, files and RAG chunks before they reach the LLM to save tokens.
- **[context-mode](https://github.com/mksglu/context-mode)** `★ 32.7k` · Cuts coding-agent context use by sandboxing tool output and persisting session memory.
- **[fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction)** `★ 7.8k` · Claude Code plugin that drops stale tool output with Jev instead of writing a compaction summary.
- **[claude-token-efficient](https://github.com/drona23/claude-token-efficient)** `★ 6.1k` · Single CLAUDE.md file that keeps Claude responses terse to cut output verbosity.
- **[opencode-dynamic-context-pruning](https://github.com/Tarquinen/opencode-dynamic-context-pruning)** `★ 4.4k` · OpenCode plugin that prunes conversation context to cut token usage.
- **[Chisle](https://github.com/JayPokale/Chisle)** `★ 723` · Cuts a coding agent's token use with terse prose, YAGNI-first code and tool-output compression.
- **[claude-token-optimizer](https://github.com/nadimtuhin/claude-token-optimizer)** `★ 635` · CLI that sets up a small CLAUDE.md with on-demand docs to cut tokens loaded at session start.
- **[context-attachment-manager](https://github.com/chipfighter/context-attachment-manager)** `★ 558` · Keeps long image chats in Codex and Claude fast by pulling back only the images needed.
- **[Astra-Ares](https://github.com/miuuyy/Astra-Ares)** `★ 310` · Adaptive reasoning effort for Codex tasks, powered by Jev to reduce token usage.
- **[Supercompress](https://github.com/Supercompress/Supercompress)** `★ 138` · Query-aware context compression for LLMs and coding agents, cutting about 65% of input tokens.
- **[claude-context-optimizer](https://github.com/egorfedorov/claude-context-optimizer)** `★ 125` · Claude Code plugin that tracks token usage and wasted context to cut API costs.
- **[sgaabdu4/claude-code-tips](https://github.com/sgaabdu4/claude-code-tips)** `★ 92` · Token-saving stack for Claude Code: context-mode, RTK, Headroom, Caveman and hooks.
- **[rlm-rs](https://github.com/zircote/rlm-rs)** `★ 62` · Rust CLI that brings the Recursive Language Model pattern to Claude Code for very large documents.
- **[cache-audit](https://github.com/ussumant/cache-audit)** `★ 61` · Claude Code skill that audits a setup against six prompt-caching rules.
- **[token-reducer](https://github.com/Madhan230205/token-reducer)** `★ 52` · Local-first context compression plugin that cuts Claude Code token usage.

<sub><a href="#contents">back to contents</a></sub>

## Guides and lists

Guides, courses and curated lists for working with coding agents.

### Claude Code guides

- **[awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)** `★ 56.8k` · **Top pick.** Curated list of skills, agents, status lines, plugins and tooling for Claude Code.
- **[claude-howto](https://github.com/luongnv89/claude-howto)** `★ 45.9k` · **Top pick.** Visual, example-driven guide to Claude Code with copy-paste templates.
- **[claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)** `★ 68.3k` · Best-practice guide for Claude Code, from vibe coding to agentic engineering.
- **[ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips)** `★ 10.3k` · 45+ tips for getting the most out of Claude Code, from basics to advanced.
- **[claude-code-ultimate-guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide)** `★ 6.3k` · Claude Code guide covering agentic workflows, hooks, skills, MCP servers and quizzes.
- **[zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide)** `★ 4.7k` · Guide to Claude Code setup, commands, workflows, agents, skills and tips, beginner to power user.
- **[Claude-Code-Everything-You-Need-to-Know](https://github.com/wesammustafa/Claude-Code-Everything-You-Need-to-Know)** `★ 3.5k` · Claude Code guide in three levels, beginner to advanced, with hands-on lessons.
- **[Cranot/claude-code-guide](https://github.com/Cranot/claude-code-guide)** `★ 2.9k` · Claude Code CLI guide that is auto-updated every two days.
- **[claude-code-engineering](https://github.com/huangjia2019/claude-code-engineering)** `★ 1.1k` · Course repo on using Claude Code for real engineering work, not just writing code.
- **[claude-code-is-programmable](https://github.com/disler/claude-code-is-programmable)** `★ 311` · Examples of using Claude Code as a programmable agentic coding tool to scale compute.
- **[claude-code-docs](https://github.com/thevibeworks/claude-code-docs)** `★ 164` · Markdown archive of Anthropic's builder docs, refreshed four times daily.
- **[opus-4-7-boris](https://github.com/robonuggets/opus-4-7-boris)** `★ 22` · Claude Code skill that applies Boris Cherny's six recommendations for tuning Claude Opus 4.7.
- **[claude-mods-brain](https://github.com/AgriciDaniel/claude-mods-brain)** `★ 19` · Source-cited Obsidian knowledge base on how Claude Code mods work and how to build them.

### Codex and Copilot guides

- **[Mastering-GitHub-Copilot-for-Paired-Programming](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming)** `★ 8.2k` · Multi-module course on using GitHub Copilot as an AI pair programmer.
- **[copilot-cli-for-beginners](https://github.com/github/copilot-cli-for-beginners)** `★ 2.9k` · Beginner course for getting started with the GitHub Copilot CLI.
- **[codex-cli-best-practice](https://github.com/shanraisshan/codex-cli-best-practice)** `★ 1k` · Best-practice guide for Codex CLI, from vibe coding to agentic engineering.

### Harness and context engineering

- **[learn-harness-engineering](https://github.com/walkinglabs/learn-harness-engineering)** `★ 22.2k` · **Top pick.** Beginner tutorial on harness engineering, from zero to one.
- **[Context-Engineering](https://github.com/jasontang-ai/Context-Engineering)** `★ 9.3k` · First-principles handbook on context engineering: designing, orchestrating and optimizing context.
- **[deusyu/harness-engineering](https://github.com/deusyu/harness-engineering)** `★ 6.2k` · Chinese-language study guide to harness engineering, from concepts to independent practice.
- **[ai-boost/awesome-harness-engineering](https://github.com/ai-boost/awesome-harness-engineering)** `★ 5k` · Curated list on AI agent harness engineering: tools, patterns, evals, memory, MCP and observability.
- **[walkinglabs/awesome-harness-engineering](https://github.com/walkinglabs/awesome-harness-engineering)** `★ 4.5k` · Curated tools and guides for harness engineering.
- **[Awesome-Context-Engineering](https://github.com/Meirtz/Awesome-Context-Engineering)** `★ 3.3k` · Survey with hundreds of papers on context engineering, from prompting to production AI systems.
- **[lopopolo/harness-engineering](https://github.com/lopopolo/harness-engineering)** `★ 2.7k` · Anthology, field guide and agent context bundle on harness engineering.
- **[100x-loops](https://github.com/Siddhant-Goswami/100x-loops)** `★ 44` · Tutorial loops in which Claude Code Stop hooks keep the agent working until the tests pass.

### Vibe coding

- **[vibe-coding-cn](https://github.com/2025Emma/vibe-coding-cn)** `★ 23.1k` · Chinese guide to vibe coding as pair programming with AI, from setup to workflow.
- **[easy-vibe](https://github.com/datawhalechina/easy-vibe)** `★ 20.2k` · Beginner course in vibe coding for AI product builders.
- **[vibe-vibe](https://github.com/datawhalechina/vibe-vibe)** `★ 6.2k` · Systematic vibe coding tutorial from zero to full-stack.
- **[awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding)** `★ 5.4k` · Curated list of vibe coding references for collaborating with AI to write code.
- **[vibe-coding](https://github.com/EnzeD/vibe-coding)** `★ 4.8k` · Guide to vibe coding with Claude Code and Codex.
- **[how-to-vibecoding](https://github.com/1EchA/how-to-vibecoding)** `★ 936` · Chinese tutorial series on vibe coding, from setup to multi-agent work with MCP and Skills.
- **[Awesome-Vibecoding-Guide](https://github.com/bobvibes/Awesome-Vibecoding-Guide)** `★ 793` · Guide to AI-assisted coding drawn from real commercial projects.
- **[vibe](https://github.com/di-sukharev/vibe)** `★ 767` · Russian-language template for vibe coding web and mobile apps, sites and admin panels.
- **[next-ai-starter](https://github.com/kleneway/next-ai-starter)** `★ 510` · Next.js starter kit optimized for building applications with AI coding tools.
- **[awesome-vibe-coding-guide](https://github.com/analyticalrohit/awesome-vibe-coding-guide)** `★ 387` · Guide to vibe coding with best practices and tips for controlled AI-assisted coding.

<sub><a href="#contents">back to contents</a></sub>

## The Wellux awesome family

Every list comes from the same 6,623 starred repos, sorted by the job they do. Each repo has exactly one home.

| List | What is inside | Repos |
|:---|:---|---:|
| **[awesome-agent-os](https://github.com/Wellux/awesome-agent-os)** | Personal agents and the ecosystems around them: OpenClaw, Hermes, DeepSeek Harness, cockpits, company OS and devices. | 436 |
| **awesome-coding-agents** (you are here) | Claude Code, Codex, OpenCode, Pi and Herdr with setups, parallel sessions, loops, code context, usage and guides. | 459 |
| **[awesome-agent-skills](https://github.com/Wellux/awesome-agent-skills)** | Skill libraries, SKILL.md tooling, subagents, rules files, prompts and system prompts. | 225 |
| **[awesome-mcp-connectors](https://github.com/Wellux/awesome-mcp-connectors)** | MCP servers, gateways, connectors, agent CLIs, browser and computer use and web data that give agents hands. | 240 |
| **[awesome-agent-memory](https://github.com/Wellux/awesome-agent-memory)** | Memory layers, RAG, vector search, document parsing, second brains and research agents, so agents stop forgetting. | 289 |
| **[awesome-agent-engineering](https://github.com/Wellux/awesome-agent-engineering)** | Frameworks, multi-agent systems, workflows, voice agents, guardrails, evals and the courses to build them. | 369 |
| **[awesome-ai-models](https://github.com/Wellux/awesome-ai-models)** | Run, route, train and study AI models: local inference, gateways, open models, decision models, vision and robotics. | 594 |
| **[awesome-ai-creator-stack](https://github.com/Wellux/awesome-ai-creator-stack)** | Open-source AI tools and agent skills for creators: voice, video, motion, images, 3D, design, slides and writing. | 435 |
| **[awesome-ai-at-work](https://github.com/Wellux/awesome-ai-at-work)** | AI agents, apps and skills for real work: research, finance, marketing, sales, office, data, careers and industries. | 213 |

## How picks are made

1. Starred because it was useful, not because it trended.
2. Public on GitHub and mostly open source; check each license before you build on it.
3. One home per repo: the job it does best decides the section.
4. Inside a section: top picks first, then by stars.

Star counts as of 2026-10-29. 15 archived repos are left out.

## Contribute

Know a repo that does one job better? Open an issue with the link and one sentence on the job it does. Details in [CONTRIBUTING.md](CONTRIBUTING.md).

## Why this list exists

It is the shopping list behind **myOS**, an open-source personal operating system for you and your agents. myOS launches on **1 January 2027, 5 pm CET**. Watch <a href="https://github.com/Wellux">Wellux</a> to see it land, and star this list if it saved you an afternoon.


---

<p align="center"><sub>Curated by <a href="https://github.com/Wellux">Marco Mengele · Wellux</a> · From leak to solution. One block at a time.</sub></p>
