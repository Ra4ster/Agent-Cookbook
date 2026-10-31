# Agent Cookbook

This repo is a collection of useful tools for people needing templates, plugins, and files in their agentic creation and vibecoding.

## Table of Contents

- [Plugins per Model](#plugins-per-model)
  - [Claude](#claude)
    - [Graphic Design, UI/UX & Frontend](#graphic-design-uiux--frontend)
    - [Language Support & Code Intelligence (TypeScript, Clang, Rust, Python, Go)](#language-support--code-intelligence-typescript-clang-rust-python-go)
    - [Engineering, Architecture & Code Quality](#engineering-architecture--code-quality)
    - [Databases, DevOps & Cloud Infrastructure](#databases-devops--cloud-infrastructure)
    - [Persistent Memory & Context Optimization](#persistent-memory--context-optimization)
    - [Multi-Agent Orchestration, Planning & Autonomous Loops](#multi-agent-orchestration-planning--autonomous-loops)
    - [Browser Automation & Inspection](#browser-automation--inspection)
    - [Reverse Engineering & Terminal Utilities](#reverse-engineering--terminal-utilities)
    - [Research, Writing & Knowledge Work](#research-writing--knowledge-work)
    - [Marketing, SEO & Media Production](#marketing-seo--media-production)
    - [Specialized Domains (Security, Finance, Career)](#specialized-domains-security-finance-career)
    - [Plugin Ecosystems, Registries & Cross-Model Extensions](#plugin-ecosystems-registries--cross-model-extensions)
  - [ChatGPT](#chatgpt)
    - [Coding, Prototyping & Vibecoding GPTs](#coding-prototyping--vibecoding-gpts)
    - [Architecture, Diagrams & UI Conversion](#architecture-diagrams--ui-conversion)
    - [Prompt Frameworks & System Instruction Kits](#prompt-frameworks--system-instruction-kits)
    - [Custom Actions & API Connectors (OpenAPI)](#custom-actions--api-connectors-openapi)
    - [Data Science, Research & Computational Engines](#data-science-research--computational-engines)
  - [Kimi](#kimi)
    - [Official CLI & Core Runtimes](#official-cli--core-runtimes)
    - [Agent Skills & Workflow Plugins](#agent-skills--workflow-plugins)
    - [Long-Context & Document Intelligence Tools](#long-context--document-intelligence-tools)
    - [Community Bridges & Developer Utilities](#community-bridges--developer-utilities)
  - [Gemini (Extensions)](#gemini-extensions)
    - [Google Workspace & Core Web Extensions](#google-workspace--core-web-extensions)
    - [Gemini CLI Developer Extensions & MCP](#gemini-cli-developer-extensions--mcp)
    - [Code Assist & GitHub Workflow Extensions](#code-assist--github-workflow-extensions)
    - [Cloud, BigQuery & Data Intelligence](#cloud-bigquery--data-intelligence)
- [AGENTS.md](#agentsmd)
- [Tooling Suggestions](#tooling-suggestions)
  - [Vibe Coding IDEs & App Builders](#vibe-coding-ides--app-builders)
    - [AI-Native IDEs & Agentic Workspaces](#ai-native-ides--agentic-workspaces)
    - [Autonomous Software Engineers & Cloud Agents](#autonomous-software-engineers--cloud-agents)
    - [Prompt-to-App & Full-Stack Prototyping Platforms](#prompt-to-app--full-stack-prototyping-platforms)
    - [Terminal Coding Agents & CLI Workflows](#terminal-coding-agents--cli-workflows)
    - [Enterprise Code Intelligence & Code Graph Assistants](#enterprise-code-intelligence--code-graph-assistants)
  - [Model Context Protocol (MCP) Servers](#model-context-protocol-mcp-servers)
    - [Core Developer, Version Control & Local Workspaces](#core-developer-version-control--local-workspaces)
    - [Databases, Data Warehouses & Cache](#databases-data-warehouses--cache)
    - [Web Browsing, Search & Content Extraction](#web-browsing-search--content-extraction)
    - [DevOps, Cloud Infrastructure & Observability](#devops-cloud-infrastructure--observability)
    - [Team Collaboration, Project Management & Docs](#team-collaboration-project-management--docs)
  - [Core Agent Frameworks](#core-agent-frameworks)
    - [Graph-Based & Stateful Multi-Agent Orchestrators](#graph-based--stateful-multi-agent-orchestrators)
    - [Code-First & Type-Safe Agent Frameworks](#code-first--type-safe-agent-frameworks)
    - [Optimization, Evaluation & Production Runtimes](#optimization-evaluation--production-runtimes)

---

<br/><br/><br/>

# Plugins per Model

<img src="assets/logos/claude.png" alt="Claude" height="70">

## Claude

### Graphic Design, UI/UX & Frontend

<table>
<tr>
<td width="50%" valign="top">

### [frontend-design](https://claude.com/marketplace/plugins/frontend-design)

This plugin enables Claude to create polished code with bold aesthetic choices, distinctive typography and color palettes, high-impact animations, and context-aware visual details. Key design areas include thoughtful typography with unexpected font pairings, orchestrated motion and scroll-triggered interactions, spatial composition with asymmetry and grid-breaking elements, and visual depth through gradients, textures, and layered effects.

**How to use:**
Simply ask Claude to build frontend interfaces and this skill activates automatically. Try prompts like "Create a dashboard for a music streaming app", "Build a landing page for an AI security startup", or "Design a settings panel with dark mode support".

</td>
<td width="50%" valign="top">

### [figma](https://claude.com/marketplace/plugins/figma)

Access figma design context, extract component information, retrieve design tokens, and translate designs into production-ready code with pixel-perfect fidelity.

**How to use:**
Share a Figma URL and ask Claude to implement the design. Use /implement-design to translate Figma frames into code using your project's design system. Use /create-design-system-rules to generate custom guidelines that encode your team's development conventions. Use /code-connect-components to establish mappings between Figma components and your codebase implementations.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [playground](https://claude.com/marketplace/plugins/playground)

Choose from six built-in templates: **Design Playground** for exploring visual components like buttons, cards, and typography; **Data Explorer** for constructing SQL queries, API calls, and regex patterns; **Concept Map** for knowledge mapping and educational tools; **Document Critique** for review workflows with approve/reject actions; **Diff Review** for line-by-line code review; and **Code Map** for visualizing codebase relationships and data flow. Each playground ships with a dark theme, sensible defaults, 3–5 named presets, and instant live preview updates as you adjust controls. The generated prompt output uses qualitative, human-readable language rather than raw value dumps, making it ready to paste directly into Claude or other tools.

**How to use:**
Invoke the skill with /playground followed by what you want to explore. Try prompts like: "create a playground for button design styles", "build a SQL query explorer for my users table", "make an interactive concept map for machine learning fundamentals", or "create a diff review tool for my PR changes".

</td>
<td width="50%" valign="top">

### [liquid-skills](https://claude.com/marketplace/plugins/liquid-skills)

Liquid language fundamentals, CSS/JS/HTML coding standards, and WCAG accessibility patterns for Shopify themes.

**How to use:**
Install via `npx skills add Shopify/liquid-skills --agent claude-code` or `/plugin marketplace add liquid-skills`. Activates automatically when writing or refactoring Shopify Liquid templates and theme files.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Mintlify](https://claude.com/marketplace/plugins/mintlify)

Key capabilities include creating and editing pages with correct MDX and component syntax, restructuring navigation, updating site configuration, and opening pull requests with your changes. A live documentation lookup connects Claude to Mintlify's published docs for real-time reference if the built-in knowledge is ever insufficient to complete a task.

**How to use:**
Ask Claude to help with any Mintlify task and the skill activates automatically. Try prompts like "Update the quickstart guide based on this user feedback", "Set up a changelog", or "Use the mint CLI to get recent user comments and identify any pages to update." For live editing sessions, start with "check out my Mintlify project." Claude will authenticate and open a preview so you can watch changes render in real time.

</td>
<td width="50%" valign="top">

### [Superdesign](https://claude.com/marketplace/plugins/superdesign)

Design or redesign frontend UI, presentations, and marketing graphics on the Superdesign infinite canvas. Uses approved slide outlines, project context, and branchable drafts you refine.

**How to use:**
Install via `/plugin marketplace add superdesign` or visit https://superdesign.dev. Use `/superdesign` to design frontend UI, marketing graphics, and slide outlines on an infinite canvas.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [vercel-react-best-practices](https://claudecowork.im/resources/vercel-react-best-practices)

React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, reviewing, or refactoring React/Next.js code to ensure optimal performance patterns. Triggers on tasks involving React components, Next.js pages, data fetching, bundle optimization, or performance improvements.

**How to use:**

1. Quick install (skills CLI) `npx skills add vercel-labs/agent-skills --skill vercel-react-best-practices --agent claude-code` (Installs vercel-react-best-practices into the current project's .claude/skills/ directory). _Requires Node.js and the skills CLI._
2. Manual install: Create ~/.claude/skills/<name>/ and copy the SKILL.md file from the repository into it. The directory name must match the skill name. _⚠️ Exact file layout and requirements vary by repository — always check the repo README first._

</td>
<td width="50%" valign="top">

### [Web Design Guidelines](https://claudemarketplaces.com/skills/vercel-labs/agent-skills/web-design-guidelines)

A solid UI audit tool that pulls the latest Web Interface Guidelines from Vercel's GitHub repo and checks your code against them. Point it at your HTML, CSS, or component files and it'll flag accessibility issues, design inconsistencies, and UX problems in a clean file:line format. The guidelines stay current since it fetches fresh rules on each run rather than using stale built-in checks. Handy for catching common web standards violations before they ship, especially if you're working fast and might miss obvious accessibility or usability issues.

**How to use:**
Project: `npx -y skills add vercel-labs/agent-skills --skill web-design-guidelines --agent claude-code`. Globally: `npx -y skills add vercel-labs/agent-skills --skill web-design-guidelines --agent claude-code -g`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Taste Skill](https://github.com/Leonxlnx/taste-skill) (✨ Multi-Agent)

Agent skills that give coding agents taste: art direction, typography pairings, color systems, layout constraints, reference images, and browser validation instead of generic AI slop.

**How to use:**
Install globally using `npx skills add Leonxlnx/taste-skill --skill design-taste-frontend --agent claude-code --global` or run `npx skills add Leonxlnx/taste-skill`. For more information, view https://www.tasteskill.dev/guide.

</td>
<td width="50%" valign="top">

### [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)

An AI skill that provides design intelligence for building professional UI/UX across multiple platforms, enforcing visual hierarchy, accessible color contrast, and balanced spatial composition.

**How to use:**
Install via `npx skills add nextlevelbuilder/ui-ux-pro-max-skill --agent claude-code`. Ask Claude to review a UI or prompt: "Design a modern, responsive SaaS dashboard using ui-ux-pro-max".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [impeccable](https://github.com/pbakaus/impeccable)

The design vocabulary for your coding agent created by Paul Bakaus. Steer with polish and bolder, review with critique and audit, and catch AI slop before it ships.

**How to use:**
Install via `npx skills add pbakaus/impeccable --agent claude-code`. Use commands like `/polish`, `/critique`, or `/audit` on your UI components.

</td>
<td width="50%" valign="top">

### [hallmark](https://github.com/Nutlope/hallmark)

Anti-AI-slop design skill for Claude Code, Cursor, and Codex created by Hassan El Mghari, enforcing disciplined typography pairings, curated colors, and clean aesthetic structures.

**How to use:**
Install via `npx skills add Nutlope/hallmark --agent claude-code`. Claude automatically applies Hallmark design conventions when authoring or refactoring frontend interfaces.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [diagram-design](https://github.com/cathrynlavery/diagram-design)

Editorial diagram design for Claude Code, Codex, GitHub Copilot, and Cursor. Features 45 diagram types rendered in self-contained HTML + SVG with no shadows and no Mermaid slop.

**How to use:**
Install via `npx skills add cathrynlavery/diagram-design --agent claude-code`. Ask Claude: "Generate an editorial architecture diagram in HTML+SVG for this authentication workflow".

</td>
<td width="50%" valign="top">

### [frontend-slides](https://github.com/zarazhangrui/frontend-slides)

Create beautiful, interactive presentation slides on the web using a coding agent's frontend skills, complete with custom typography, responsive layouts, and zero external dependencies.

**How to use:**
Install via `npx skills add zarazhangrui/frontend-slides --agent claude-code`. Ask Claude: "Design an interactive 10-slide HTML presentation explaining our Q3 engineering architecture".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ppt-master](https://github.com/hugohe3/ppt-master)

AI turns documents or topics into real, native Microsoft PowerPoint decks—with native shapes, transitions and animations, data-backed charts and tables on demand, audio narration from speaker notes, and custom `.pptx` templates.

**How to use:**
Install via `npx skills add hugohe3/ppt-master --agent claude-code`. Ask Claude: "Convert this document into a native PowerPoint deck using ppt-master".

</td>
<td width="50%" valign="top">

### [baoyu-skills](https://github.com/JimLiu/baoyu-skills)

Modular agent skills shared by Baoyu for daily productivity, technical diagramming (`baoyu-diagram`), article illustrations (`baoyu-article-illustrator`), and UI/UX design.

**How to use:**
Install via `npx skills add jimliu/baoyu-skills --agent claude-code`. Triggers automatically when generating illustrations, conceptual diagrams, or markdown visual assets.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [text-to-cad](https://github.com/earthtojake/text-to-cad)

Design physical products with AI. Generates parametric, manufacturing-ready 3D CAD models using Python `build123d` and OpenCascade, exporting standard STEP, STL, DXF, and 3MF files.

**How to use:**
Install via `pip install text-to-cad` or register as an MCP server. Prompt Claude: "Generate a parametric 3D printable mounting bracket for a Raspberry Pi 4 and export to STEP".

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Language Support & Code Intelligence (TypeScript, Clang, Rust, Python, Go)

<table>
<tr>
<td width="50%" valign="top">

### [typescript-lsp](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/typescript-lsp)

Official Anthropic TypeScript and JavaScript language server plugin for Claude Code. Provides semantic code intelligence, accurate go-to-definition, find-references, and compiler diagnostics across `.ts`, `.tsx`, `.js`, `.jsx`, `.mts`, and `.cjs` files.

**How to use:**
Install via `/plugin install typescript-lsp@claude-plugins-official` (or `npx skills add anthropics/claude-plugins-official --skill typescript-lsp --agent claude-code`). Ensure `typescript-language-server` is installed globally via `npm install -g typescript-language-server typescript`.

</td>
<td width="50%" valign="top">

### [clangd-lsp](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/clangd-lsp)

Official Anthropic C and C++ language server plugin for Claude Code. Integrates LLVM `clangd` directly into Claude Code for code intelligence, semantic symbol lookups, compiler warnings, and formatting across `.c`, `.cpp`, `.cc`, `.h`, and `.hpp` files.

**How to use:**
Install via `/plugin install clangd-lsp@claude-plugins-official`. Ensure `clangd` is installed on your system (e.g. `brew install llvm` or `sudo apt install clangd`).

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [rust-analyzer-lsp](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/rust-analyzer-lsp)

Official Anthropic Rust language server plugin for Claude Code. Provides IDE-grade code intelligence, trait resolution, borrow-checker diagnostics, and type inference using `rust-analyzer`.

**How to use:**
Install via `/plugin install rust-analyzer-lsp@claude-plugins-official`. Ensure `rust-analyzer` is installed via `rustup component add rust-analyzer`.

</td>
<td width="50%" valign="top">

### [pyright-lsp](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/pyright-lsp)

Official Anthropic Python language server plugin for Claude Code, integrating Microsoft Pyright for static type analysis, parameter hints, and cross-file symbol resolution.

**How to use:**
Install via `/plugin install pyright-lsp@claude-plugins-official`. Ensure `pyright` is installed globally via `npm install -g pyright`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [gopls-lsp](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/gopls-lsp)

Official Anthropic Go language server plugin for Claude Code. Connects Claude directly to Google's official `gopls` language server for Go packages, interface implementations, and type checking.

**How to use:**
Install via `/plugin install gopls-lsp@claude-plugins-official`. Ensure `gopls` is installed via `go install golang.org/x/tools/gopls@latest`.

</td>
<td width="50%" valign="top">

### [cclsp](https://github.com/ktnyt/cclsp)

Dedicated Language Server Protocol (LSP) adapter and MCP server tailored specifically for Claude Code. Bridges coding agents to native language servers like `typescript-language-server`, `clangd`, and `gopls` to eliminate line/column counting errors and provide robust semantic navigation without relying on brittle text grep.

**How to use:**
Install via `npm install -g cclsp` or add the MCP server with `claude mcp add cclsp -- npx -y cclsp`. Configure project language server binaries in your settings.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [clangd-mcp-server](https://github.com/felipeerias/clangd-mcp-server)

LLVM `clangd` Language Server Model Context Protocol integration for C and C++ projects. Enables Claude Code to query compiler diagnostics, resolve complex macros, inspect header inclusions, track call hierarchies, and navigate AST symbols using a project's `compile_commands.json`.

**How to use:**
Ensure `clangd` is installed on your system. Register the MCP server via `claude mcp add clangd -- npx -y clangd-mcp-server --workspace /path/to/project`. Ask Claude: "Run clang diagnostics and resolve this undefined symbol in main.cpp".

</td>
<td width="50%" valign="top">

### [mcp-language-server](https://github.com/isaacphi/mcp-language-server)

Universal stdio LSP-to-MCP bridge by Isaac Phi. Connects Claude Code to any standard Language Server Protocol binary (`typescript-language-server`, `clangd`, `rust-analyzer`, `pyright`, or `gopls`) and exposes unified tools for definition lookups, reference discovery, hover signatures, and diagnostics.

**How to use:**
Install the binary via Go: `go install github.com/isaacphi/mcp-language-server/cmd/mcp-language-server@latest`. Register with Claude Code: `claude mcp add lsp-server mcp-language-server --workspace /path/to/project --lsp <language-server-binary>`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [rust-analyzer-mcp](https://github.com/rust-lang/rust-analyzer)

Native Rust MCP server bridge for `rust-analyzer`. Feeds Claude Code accurate borrow-checker hints, type inferences, trait implementations, macro expansions, and cargo compilation errors directly from the Rust compiler.

**How to use:**
Install via cargo: `cargo install rust-analyzer-mcp` (or configure via community MCP bridges). Add to Claude Code with `claude mcp add rust-analyzer -- rust-analyzer-mcp`.

</td>
<td width="50%" valign="top">

### [pyright-mcp](https://github.com/microsoft/pyright)

Fast, type-aware Python language server integration connecting Claude Code to Microsoft Pyright. Provides instant type validation, parameter signature lookups, import resolution, and syntax error tracking across large Python codebases.

**How to use:**
Install Pyright with `npm install -g pyright`. Add through an LSP bridge (e.g. `mcp-language-server` or `cclsp`) using `--lsp pyright-langserver --stdio`. Claude automatically surfaces type discrepancies when generating Python code.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [LSP-MCP-Server](https://github.com/goodwinka/LSP-MCP-Server)

Multi-language LSP router for AI coding agents that dynamically inspects file paths and file extensions, routing semantic queries automatically to the appropriate background language server (`clangd`, `pyright`, `typescript-language-server`, etc.).

**How to use:**
Clone and install via `npm install -g lsp-mcp-server`. Start the daemon and register with `claude mcp add lsp-router -- lsp-mcp-server`.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Engineering, Architecture & Code Quality

<table>
<tr>
<td width="50%" valign="top">

### [feature-dev](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/feature-dev)

Official Anthropic guided 7-phase feature development plugin. Deploys specialized sub-agents (code-explorer, code-architect, code-reviewer) to systematically discover codebase architecture, ask clarifying questions, design implementation plans, and verify code quality before shipping.

**How to use:**
Install via `/plugin install feature-dev@claude-plugins-official`. Launch the interactive workflow with `/feature-dev` or pass a feature prompt: `/feature-dev Add user authentication with OAuth`.

</td>
<td width="50%" valign="top">

### [code-simplifier](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/code-simplifier)

Official Anthropic agent plugin that simplifies and refines code for clarity, consistency, and maintainability while strictly preserving existing functionality, fighting against AI over-engineering and cognitive bloat.

**How to use:**
Install via `/plugin install code-simplifier@claude-plugins-official`. Run `/simplify` or prompt Claude: "Review and simplify this module to remove unnecessary abstractions".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [pr-review-toolkit](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/pr-review-toolkit)

Official Anthropic pull request review toolkit featuring specialized review agents focused on security vulnerabilities, error handling edge-cases, type design, code simplification, and test coverage.

**How to use:**
Install via `/plugin install pr-review-toolkit@claude-plugins-official`. Use commands like `/pr-review` or `/review-pr <pr-url>` to generate thorough, multi-agent code critiques.

</td>
<td width="50%" valign="top">

### [commit-commands](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/commit-commands)

Official Anthropic git workflow plugin providing automated commands for generating conventional, semantic commit messages, staging atomic changes, pushing, and opening PRs.

**How to use:**
Install via `/plugin install commit-commands@claude-plugins-official`. Use `/commit` to automatically inspect diffs and generate a clean commit message, or `/push` and `/pr` to manage pull requests.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [claude-md-management](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/claude-md-management)

Official Anthropic tools to maintain and optimize `CLAUDE.md` files. Audits instruction quality, captures session learnings, and keeps project memory synchronized with evolving architectures.

**How to use:**
Install via `/plugin install claude-md-management@claude-plugins-official`. Run `/claude-md update` or `/claude-md audit` to optimize your project rules.

</td>
<td width="50%" valign="top">

### [code-modernization](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/code-modernization)

Official Anthropic modernization plugin for legacy codebases. Extracts business rules, produces interactive architecture maps, security hardens components, and guides step-by-step refactoring with behavioral equivalence guarantees.

**How to use:**
Install via `/plugin install code-modernization@claude-plugins-official`. Run `/modernize` to assess legacy code and formulate an upgrade roadmap.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [hookify](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/hookify)

Official Anthropic plugin that makes it easy to configure, test, and manage Claude Code lifecycle hooks (`pre-tool`, `post-tool`, `pre-commit`) to enforce custom safety guardrails and coding standards.

**How to use:**
Install via `/plugin install hookify@claude-plugins-official`. Use `/hookify` to generate and audit custom lifecycle hooks.

</td>
<td width="50%" valign="top">

### [superpowers](https://github.com/obra/superpowers)

An agentic skills framework and software development methodology that works, providing structured practices for specification, iterative implementation, testing, and Git hygiene.

**How to use:**
Install via `npx skills add obra/superpowers --agent claude-code` or copy to `~/.claude/skills/superpowers`. Instruct Claude to follow the superpowers methodology during feature development.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [skills](https://github.com/mattpocock/skills)

Skills for Real Engineers straight from Matt Pocock's `.agents` directory, encoding TypeScript best practices, type gymnastics, idiomatic patterns, and clean code hygiene.

**How to use:**
Install via `npx skills add mattpocock/skills --agent claude-code`. Activates automatically when writing, refactoring, or reviewing TypeScript code.

</td>
<td width="50%" valign="top">

### [agent-skills](https://github.com/addyosmani/agent-skills)

Addy Osmani's production-grade engineering skills for AI coding agents, focusing on web performance optimization, Core Web Vitals, modern JavaScript patterns, and progressive enhancement.

**How to use:**
Install via `npx skills add addyosmani/agent-skills --agent claude-code`. Use when auditing web performance or building production web applications.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [skills](https://github.com/anthropics/skills)

Anthropic's official public repository for Agent Skills, including standard programming patterns, algorithmic approaches, and baseline file and codebase manipulation skills.

**How to use:**
Install individual skills or the full bundle via `npx skills add anthropics/skills --agent claude-code`.

</td>
<td width="50%" valign="top">

### [skills](https://github.com/google/skills)

Official Google repository of Agent Skills for Google products and technologies, including Google Cloud Platform, Firebase, Android, Web APIs, and Gemini integrations.

**How to use:**
Install via `npx skills add google/skills --agent claude-code`. Activates when developing on GCP, Firebase, or Google developer platforms.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [open-code-review](https://github.com/alibaba/open-code-review)

Alibaba's battle-tested hybrid code review engine combining deterministic Go analysis pipelines with LLM agents to deliver line-level comments on NPE, thread-safety, XSS, and SQL injection.

**How to use:**
Install via `go install github.com/alibaba/open-code-review/cmd/ocr@latest` or add to Claude Code. Run `ocr review` on a branch diff or pull request.

</td>
<td width="50%" valign="top">

### [compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)

Official Compound Engineering plugin by Every, operationalizing the cycle of brainstorm, plan, build, review, and compound (saving reusable patterns back to local memory).

**How to use:**
Install via `/plugin marketplace add EveryInc/compound-engineering-plugin` or `npx skills add EveryInc/compound-engineering-plugin`. Run `/compound` after finishing tasks to persist institutional learnings.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ponytail](https://github.com/DietrichGebert/ponytail)

Makes your AI agent think like the laziest senior dev in the room. Enforces YAGNI, standard library reuse, and minimalist solutions before writing new code.

**How to use:**
Install via `npx skills add DietrichGebert/ponytail --agent claude-code` or `/plugin marketplace add DietrichGebert/ponytail`. Adjust intensity with `/ponytail lite`, `/ponytail full`, or `/ponytail ultra`.

</td>
<td width="50%" valign="top">

### [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)

A single `CLAUDE.md` ruleset to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls, hallucinations, and overcomplication.

**How to use:**
Install via `npx skills add multica-ai/andrej-karpathy-skills --agent claude-code` or copy the contents into your project's `CLAUDE.md`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [repomix](https://github.com/yamadashy/repomix)

Packs your entire repository into a single AI-friendly file with XML tags, token budget guards, an MCP server, and native Claude Agent Skills generation (`--skill-generate`).

**How to use:**
Generate Claude Agent Skills with `npx repomix --skill-generate`, or add the MCP server with `claude mcp add repomix -- npx -y repomix --mcp`.

</td>
<td width="50%" valign="top">

### [GitNexus](https://github.com/abhigyanpatwari/GitNexus)

Zero-server code intelligence engine that maps symbols, call chains, dependencies, and execution flows into an in-browser or local knowledge graph with Graph RAG MCP support.

**How to use:**
Add the MCP server with `claude mcp add gitnexus -- npx -y gitnexus-mcp`. Ask Claude: "Analyze the blast radius of modifying this auth service".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything)

Turns any codebase into an interactive knowledge graph you can explore, search, and ask questions about, prioritizing pedagogical graphs over vanity charts.

**How to use:**
Install via `npx skills add Egonex-AI/Understand-Anything --agent claude-code`. Ask Claude: "Map out the architecture of this project using Understand-Anything".

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Databases, DevOps & Cloud Infrastructure

<table>
<tr>
<td width="50%" valign="top">

### [github](https://github.com/modelcontextprotocol/servers/tree/main/src/github)

Official GitHub Model Context Protocol server enabling Claude Code to search repositories, inspect file contents across commits, create and update pull requests, query issues, and read CI/CD run logs directly.

**How to use:**
Add the MCP server via `claude mcp add github -- npx -y @modelcontextprotocol/server-github` and provide a `GITHUB_PERSONAL_ACCESS_TOKEN`. Ask Claude: "List open issues labeled bug" or "Create a PR for this branch".

</td>
<td width="50%" valign="top">

### [postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)

Official PostgreSQL Model Context Protocol server providing read-only database exploration, schema introspection, index checking, and query execution planning (`EXPLAIN ANALYZE`).

**How to use:**
Register the MCP server via `claude mcp add postgres -- npx -y @modelcontextprotocol/server-postgres postgresql://user:pass@localhost:5432/dbname`. Ask Claude: "Inspect the schema of the users table and explain how to write this migration".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)

Official SQLite Model Context Protocol server allowing Claude Code to inspect local database schemas, run exploratory SQL queries, verify data integrity, and test migrations in real time.

**How to use:**
Register the MCP server with `claude mcp add sqlite -- npx -y @modelcontextprotocol/server-sqlite --db /path/to/database.db`. Ask Claude to inspect table structures or validate queries.

</td>
<td width="50%" valign="top">

### [docker-mcp](https://github.com/ckreiling/mcp-server-docker)

Docker container and image management MCP server for Claude Code. Inspects running containers, streams container logs, checks Docker compose networks, and assists in debugging failing Docker builds.

**How to use:**
Add via `claude mcp add docker -- npx -y mcp-server-docker`. Ask Claude: "Inspect the logs of the running web container and diagnose why the port is unmapped".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [playwright-mcp](https://github.com/executeautomation/mcp-playwright)

Playwright browser automation and testing MCP server for coding agents. Executes end-to-end tests, inspects dynamic DOM elements, captures full-page screenshots, and verifies visual regressions.

**How to use:**
Register via `claude mcp add playwright -- npx -y @executeautomation/playwright-mcp-server`. Instruct Claude: "Navigate to localhost:3000/login, fill in test credentials, and assert the dashboard renders properly".

</td>
<td width="50%" valign="top">

### [sentry](https://github.com/getsentry/sentry-mcp)

Official Sentry MCP server that connects Claude Code directly to production telemetry, allowing Claude to inspect unresolved issues, retrieve full stack traces, analyze breadcrumbs, and formulate fixes.

**How to use:**
Register with `claude mcp add sentry -- npx -y @sentry/mcp-server` using your Sentry auth token. Prompt Claude: "Look up recent Sentry issues tagged with TypeError in auth service and suggest fixes".

</td>
</tr>
</table>

### Persistent Memory & Context Optimization

<table>
<tr>
<td width="50%" valign="top">

### [claude-mem](https://github.com/thedotmack/claude-mem)

Persistent context across sessions for Claude Code and coding agents. Captures actions and decisions during sessions, compresses them with AI, and injects relevant context into future sessions.

**How to use:**
Install via `npx skills add thedotmack/claude-mem` or follow setup instructions in the repo. Operates automatically in the background across sessions.

</td>
<td width="50%" valign="top">

### [headroom](https://github.com/headroomlabs-ai/headroom)

High-performance proxy and MCP server that compresses tool outputs, logs, files, and RAG chunks before they reach the LLM, cutting tokens by 20–95% without loss of precision.

**How to use:**
Add as an MCP server with `claude mcp add headroom -- npx -y @headroom/mcp` or run as a local proxy in front of Claude Code.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [context-mode](https://github.com/mksglu/context-mode)

Context window optimization system that sandboxes heavy tool outputs (up to 98% token reduction) and persists session memory across compactions using SQLite FTS5 search.

**How to use:**
Add the MCP server via `claude mcp add context-mode -- npx -y context-mode-server` and register lifecycle hooks to automatically intercept command outputs.

</td>
<td width="50%" valign="top">

### [context7](https://github.com/upstash/context7)

Upstash's platform providing up-to-date documentation and API references directly to AI agents via MCP, avoiding stale knowledge and hallucinated APIs.

**How to use:**
Add the MCP server with `claude mcp add context7 -- npx -y @upstash/context7-mcp`. Claude will query current docs dynamically when working with supported libraries.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [mempalace](https://github.com/MemPalace/mempalace)

Open-source spatial AI memory system based on the Method of Loci, providing benchmark-leading verbatim recall across long tasks without expensive API calls or lossy summarization.

**How to use:**
Install via `pip install mempalace` or add the MCP server. Configure persistent storage paths in your workspace for cross-session recall.

</td>
<td width="50%" valign="top">

### [agentmemory](https://github.com/rohitg00/agentmemory)

Persistent memory for AI coding agents based on real-world benchmarks, using lifecycle hooks to track changes and hybrid search (BM25 + vector + graph) to retrieve past decisions.

**How to use:**
Install via `npm install -g agentmemory`. Start the local background service with `agentmemory start` and connect it via MCP.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [gbrain](https://github.com/garrytan/gbrain)

Garry Tan's opinionated agent brain, utilizing a local PostgreSQL/PGLite database to maintain a self-updating, graph-structured knowledge base that agents read from and write to.

**How to use:**
Clone the repository and initialize via `npx gbrain init`. Connect the MCP server to Claude Code for local-first persistent project memory.

</td>
<td width="50%" valign="top">

### [beads](https://github.com/gastownhall/beads)

A memory upgrade and dependency-aware issue tracker for coding agents backed by Dolt (version-controlled SQL), managing task graphs and concurrent multi-agent updates without merge conflicts.

**How to use:**
Install via `npm install -g beads-cli` or `pip install beads`. Run `beads init` in your repository and prompt Claude: "Check beads for the next task and update progress".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [OpenViking](https://github.com/volcengine/OpenViking)

ByteDance Volcengine's self-evolving context database unifying agent memory, knowledge RAG, and skills through a hierarchical virtual filesystem (`viking://`) with tiered L0/L1/L2 loading.

**How to use:**
Run the OpenViking daemon locally and connect Claude Code via the provided MCP server. Use it to store project architecture notes and reusable agent skills.

</td>
<td width="50%" valign="top">

### [qmd](https://github.com/tobi/qmd)

Tobias Lütke's local CLI search engine for markdown notes, documentation, and agent knowledge bases, combining BM25 search, on-device vector embeddings, and LLM re-ranking.

**How to use:**
Install with `npm install -g qmd`. Index your notes or docs directory with `qmd index ./docs` and run searches directly from Claude Code.

</td>
</tr>
</table>

### Multi-Agent Orchestration, Planning & Autonomous Loops

<table>
<tr>
<td width="50%" valign="top">

### [ECC](https://github.com/affaan-m/ECC)

Everything Claude Code (ECC) is a complete agent harness optimization system bundling skills, instincts, persistent memory, security checks, and research-first workflows.

**How to use:**
Install via `npx skills add affaan-m/ECC --agent claude-code`. Take advantage of pre-configured slash commands like `/plan` and `/audit`.

</td>
<td width="50%" valign="top">

### [ruflo](https://github.com/ruvnet/ruflo)

The original agent harness for deploying intelligent multi-player swarms, coordinating autonomous workflows, and orchestrating 100+ specialized subagent roles with adaptive memory.

**How to use:**
Initialize using `npx ruflo@latest init wizard` or add via the Claude Code plugin marketplace with `/plugin marketplace add ruvnet/ruflo`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)

Teams-first multi-agent orchestration framework for Claude Code with zero learning curve, managing parallel agents, background execution, and workflow coordination.

**How to use:**
Install via `npm install -g oh-my-claude-sisyphus` or follow documentation at https://yeachan-heo.github.io/oh-my-claudecode-website.

</td>
<td width="50%" valign="top">

### [planning-with-files](https://github.com/OthmanAdi/planning-with-files)

Persistent file-based planning for AI coding agents and long-running tasks. Uses crash-proof markdown plans (`task_plan.md`, `findings.md`) with deterministic completion gates to survive compactions and `/clear`.

**How to use:**
Install via `npx skills add OthmanAdi/planning-with-files --agent claude-code`. Ask Claude: "Execute this feature using planning-with-files".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [claude-task-master](https://github.com/eyaltoledano/claude-task-master)

AI-powered task-management system that breaks high-level PRDs and feature requests into granular, dependency-aware task graphs with status tracking.

**How to use:**
Install via `npm install -g claude-task-master`. Run `task-master init` and use `task-master next` or MCP tools inside Claude Code.

</td>
<td width="50%" valign="top">

### [ralph](https://github.com/snarktank/ralph)

Autonomous AI agent loop that runs repeatedly with fresh context windows until all items in a Product Requirements Document (PRD) or checklist are fully implemented.

**How to use:**
Set up a `prd.json` or `prd.md` task list and run `npx ralph run`. Claude Code will pick up each task, implement it, commit, and loop until finished.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents)

A curated collection of 100+ specialized Claude Code subagents covering frontend, backend, DevOps, code review, debugging, and software architecture.

**How to use:**
Install via `npx skills add VoltAgent/awesome-claude-code-subagents --agent claude-code`. Delegate tasks to specific subagents using `@subagent-name <prompt>`.

</td>
<td width="50%" valign="top">

### [Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep)

ARIS (Auto-Research-In-Sleep) lightweight Markdown skills for autonomous ML research, featuring cross-model adversarial review loops, idea discovery, and overnight experiment automation.

**How to use:**
Install via `npx skills add wanshuiyin/Auto-claude-code-research-in-sleep --agent claude-code`. Configure the research topic and let Claude run autonomous experiment cycles.

</td>
</tr>
</table>

### Browser Automation & Inspection

<table>
<tr>
<td width="50%" valign="top">

### [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp)

Official Google Chrome DevTools MCP server enabling Claude Code to click, type, submit forms, capture mobile viewports, inspect console errors, and profile performance traces.

**How to use:**
Add the MCP server via `claude mcp add chrome-devtools -- npx -y @chromestatus/chrome-devtools-mcp`. Ask Claude: "Open localhost:3000, take a screenshot, and inspect console errors".

</td>
<td width="50%" valign="top">

### [agent-browser](https://github.com/vercel-labs/agent-browser)

Browser automation CLI built by Vercel Labs for AI coding agents to navigate web apps, run headless tests, verify layouts, and extract page state.

**How to use:**
Install via `npm install -g @vercel/agent-browser` or add with `npx skills add vercel-labs/agent-browser --agent claude-code`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ego-lite](https://github.com/citrolabs/ego-lite)

Fast, zero-config browser for AI agents that shares your real logged-in browser state (cookies, logins, sessions) in isolated background spaces without interrupting your active browsing.

**How to use:**
Download Ego Lite from https://github.com/citrolabs/ego-lite and connect it via MCP or CLI. Ask Claude to perform actions in authenticated web dashboards.

</td>
<td width="50%" valign="top">

### [browser-harness](https://github.com/browser-use/browser-harness)

Minimalist Chrome DevTools Protocol (CDP) bridge connecting Claude Code directly to your active Chrome browser without heavy automation frameworks.

**How to use:**
Install via `npm install -g browser-harness`. Start Chrome with `--remote-debugging-port=9222` and prompt Claude to navigate and inspect pages.

</td>
</tr>
</table>

### Reverse Engineering & Terminal Utilities

<table>
<tr>
<td width="50%" valign="top">

### [rea](https://github.com/morluto/rea)

Reverse engineer anything with agents. Connects Claude Code to disassemblers, decompilers, and runtime inspection tools to analyze native binaries, APKs, Electron apps, and network traffic.

**How to use:**
Add the MCP server with `claude mcp add rea -- npx -y rea-server` or install via `npx skills add morluto/rea`. Run `/rea` or ask Claude to analyze a target binary or decompiled bundle.

</td>
<td width="50%" valign="top">

### [CLI-Anything](https://github.com/HKUDS/CLI-Anything)

HKUDS framework that converts complex GUI applications (Blender, GIMP, LibreOffice, CAD) into agent-native command-line interfaces with structured JSON inputs and outputs.

**How to use:**
Install application CLI bridges from https://clianything.cc/ and grant Claude Code execution permissions for the command tools.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [claude-hud](https://github.com/jarrodwatts/claude-hud)

Real-time terminal status line plugin for Claude Code displaying context-window usage, active tools, running subagents, session token spend, and todo progress.

**How to use:**
Install via Claude Code plugin marketplace: `/plugin marketplace add jarrodwatts/claude-hud`. Status telemetry renders at the bottom of your terminal automatically.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Research, Writing & Knowledge Work

<table>
<tr>
<td width="50%" valign="top">

### [academic-research-skills](https://github.com/Imbad0202/academic-research-skills)

Academic research skills for Claude Code covering the complete workflow: research, literature review, paper drafting, peer review, revision, and citation finalization.

**How to use:**
Install via `npx skills add Imbad0202/academic-research-skills --agent claude-code`. Ask Claude to run literature analyses or review research manuscripts.

</td>
<td width="50%" valign="top">

### [obsidian-skills](https://github.com/kepano/obsidian-skills)

Official agent skills for Obsidian created by Steph Ango (CEO of Obsidian), teaching Claude to navigate Obsidian vaults, use Obsidian CLI, and manipulate JSON Canvas files.

**How to use:**
Install via `npx skills add kepano/obsidian-skills --agent claude-code`. Prompt Claude: "Organize my daily notes into a weekly synthesis in my Obsidian vault".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [last30days-skill](https://github.com/mvanhorn/last30days-skill)

Real-time research skill that synthesizes information across Reddit, X, YouTube, Hacker News, Polymarket, and web sources over the last 30 days into grounded summaries.

**How to use:**
Install via `npx skills add mvanhorn/last30days-skill --agent claude-code`. Ask Claude: "What are the latest developer reactions to the newest Next.js release in the last 30 days?"

</td>
<td width="50%" valign="top">

### [humanizer](https://github.com/blader/humanizer)

Agent skill that removes formulaic AI writing tells, predictable transition phrases, and corporate fluff to produce natural, punchy human-sounding text.

**How to use:**
Install via `npx skills add blader/humanizer --agent claude-code`. Run `/humanize` or prompt Claude to polish technical blog posts and documentation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)

Anthropic's open-source collection of 120+ plugins tailored for knowledge workers and professionals using Claude Cowork and Claude Code.

**How to use:**
Install individual plugins from the directory in Claude Cowork or Claude Code with `/plugin add anthropics/knowledge-work-plugins/<plugin-name>`.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Marketing, SEO & Media Production

<table>
<tr>
<td width="50%" valign="top">

### [marketingskills](https://github.com/coreyhaines31/marketingskills)

Comprehensive marketing skills bundle for Claude Code and AI agents covering conversion rate optimization (CRO), direct-response copywriting, SEO, and growth engineering.

**How to use:**
Install via `npx skills add coreyhaines31/marketingskills --agent claude-code`. Prompt Claude: "Audit our landing page value proposition and suggest 3 high-converting hero headlines".

</td>
<td width="50%" valign="top">

### [claude-seo](https://github.com/AgriciDaniel/claude-seo)

Universal SEO skill for Claude Code with 26 sub-skills and 19 sub-agents covering technical SEO, Schema.org, E-E-A-T, AI search optimization (GEO/AEO), backlinks, and audits.

**How to use:**
Install via `npx skills add AgriciDaniel/claude-seo --agent claude-code`. Run `/seo-audit` or ask Claude to analyze website schema and indexability.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [hyperframes](https://github.com/heygen-com/hyperframes)

Programmatic HTML-to-video rendering framework by HeyGen, allowing coding agents to author motion graphics, social video snippets, and animations using web technologies.

**How to use:**
Install via `npx skills add heygen-com/hyperframes`. Prompt Claude: "Build a 10-second product feature reveal video using hyperframes".

</td>
<td width="50%" valign="top">

### [claude-video](https://github.com/bradautomates/claude-video)

Gives Claude Code the ability to "watch" any video file or URL. Automatically extracts keyframes with FFmpeg, transcribes audio with Whisper, and provides visual and audio context.

**How to use:**
Install via `npx skills add bradautomates/claude-video --agent claude-code`. Run `/watch <video_url_or_file>` to have Claude analyze tutorials, Loom recordings, or bug demos.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [brag](https://github.com/latent-spaces/brag)

One-command project launch video generator that inspects your codebase, writes a compelling demo narrative, and renders a 20-second launch video.

**How to use:**
Install via `npx skills add latent-spaces/brag --agent claude-code`. Run `/brag` or `/brag-slim` in your project repository to generate a release video.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Specialized Domains (Security, Finance, Career)

<table>
<tr>
<td width="50%" valign="top">

### [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills)

817 structured cybersecurity skills mapped across 6 industry frameworks (MITRE ATT&CK, NIST CSF 2.0, MITRE ATLAS, D3FEND, NIST AI RMF, MITRE F3) spanning 29 security domains.

**How to use:**
Install via `npx skills add mukul975/Anthropic-Cybersecurity-Skills --agent claude-code`. Ask Claude: "Perform a security assessment of this API gateway against NIST CSF 2.0".

</td>
<td width="50%" valign="top">

### [financial-services](https://github.com/anthropics/financial-services)

Official Anthropic reference agents, vertical plugins, and data connectors for investment banking, private equity, equity research, and wealth management workflows in Claude Cowork and Claude Code.

**How to use:**
Install into Claude Cowork or Claude Code via `/plugin marketplace add anthropics/financial-services`. Use commands like `/comps`, `/dcf`, and `/earnings`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [career-ops](https://github.com/career-ops-hq/career-ops)

Open-source job search and application optimization pipeline for Claude Code. Scores job postings (1–5 fit score), tailors clean ATS-friendly PDF resumes, and prepares customized interview briefs.

**How to use:**
Initialize with `npx @santifer/career-ops init` or install via `npx skills add career-ops-hq/career-ops`. Point Claude to job posting URLs to analyze compatibility and draft materials.

</td>
<td width="50%" valign="top">

### [pm-skills](https://github.com/phuryn/pm-skills)

Product Management skills marketplace with 100+ skills and commands covering opportunity solution trees, PRD drafting, customer interview synthesis, and go-to-market strategy.

**How to use:**
Install via `npx skills add phuryn/pm-skills --agent claude-code`. Use commands like `/prd`, `/opportunity-tree`, or `/interview-synth` to structure product work.

</td>
</tr>
</table>

### Plugin Ecosystems, Registries & Cross-Model Extensions

<table>
<tr>
<td width="50%" valign="top">

### [claude-plugins-official](https://github.com/anthropics/claude-plugins-official)

Official, Anthropic-managed directory of high-quality Claude Code plugins, including data connectors, developer tools, and workflow automations.

**How to use:**
Explore and install plugins directly inside Claude Code with `/plugin marketplace` or `/plugin add <plugin-name>`.

</td>
<td width="50%" valign="top">

### [agents](https://github.com/wshobson/agents)

Multi-harness agentic plugin marketplace supporting 90+ tools, skills, and agents across Claude Code, Cursor, Codex, OpenCode, and Antigravity.

**How to use:**
Install via `npx skills add wshobson/agents --agent claude-code`. Select and configure agent packs for your team's workflow.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)

Curated directory of 2,877+ reusable AI agent skills for Claude Code, Codex, and Cursor, featuring AAS Core local catalog discovery and plan preview.

**How to use:**
Install AAS Core via `npx skills add sickn33/agentic-awesome-skills --agent claude-code`. Search and activate skills as needed.

</td>
<td width="50%" valign="top">

### [claude-skills](https://github.com/alirezarezvani/claude-skills)

Comprehensive collection of 380+ Claude Code skills, 70+ slash commands, and 30+ specialized agents covering software engineering, marketing, compliance, and executive advisory.

**How to use:**
Install via `npx skills add alirezarezvani/claude-skills --agent claude-code`. Enable modules matching your target tech stack or domain.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [codex-plugin-cc](https://github.com/openai/codex-plugin-cc)

Official OpenAI plugin for Claude Code that enables Claude to review code, delegate complex subtasks, or verify solutions using OpenAI Codex.

**How to use:**
Install via `/plugin marketplace add openai/codex-plugin-cc`. Use commands `/codex review` or `/codex delegate <task>` (requires OpenAI API key).

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

<img src="assets/logos/chatgpt.png" alt="ChatGPT" height="70">

## ChatGPT

### Coding, Prototyping & Vibecoding GPTs

<table>
<tr>
<td width="50%" valign="top">

### [Code Copilot](https://chatgpt.com/g/g-2DQzUabbq-code-copilot)

The top-ranked programming assistant in the GPT Store. Specializes in multi-language debugging, performance audits, edge-case analysis, and code refactoring, providing senior-developer code reviews without verbose filler prose.

**How to use:**
Mention `@Code Copilot` in ChatGPT or launch directly from the store. Paste your snippet or stack trace and ask: "Analyze this function for memory leaks and concurrency pitfalls".

</td>
<td width="50%" valign="top">

### [Grimoire](https://chatgpt.com/g/g-n7Rs0IK86-grimoire)

The premier vibecoding wizard built for rapid prototyping, full-stack scaffolding, and prompt-driven software development. Features custom hotkey commands (`K` for command menu, `P` for project scaffolding, `R` for documentation) to build websites, web apps, and scripts from natural language.

**How to use:**
Open Grimoire and describe your application idea. Type `K` to view command shortcuts or prompt: "Build an interactive single-page Kanban board with React and Tailwind CSS".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [DesignerGPT](https://chatgpt.com/g/g-2EoUIDhe9-designergpt)

Builds and instantly hosts responsive multi-page web applications and landing pages directly through chat, generating clean HTML/CSS with immediate live preview hosting.

**How to use:**
Prompt DesignerGPT: "Create a modern dark-mode landing page for a developer CLI tool with pricing tiers and interactive FAQ".

</td>
<td width="50%" valign="top">

### [SQL Expert](https://chatgpt.com/g/g-m56kpU0bK-sql-expert)

Database optimization and query generation GPT for PostgreSQL, MySQL, SQLite, and Snowflake. Writes complex joins, optimizes query execution plans (`EXPLAIN`), and suggests composite indexes.

**How to use:**
Provide your schema DDL and query goals: "Optimize this slow 4-table join and suggest appropriate composite indexes".

</td>
</tr>
</table>

### Architecture, Diagrams & UI Conversion

<table>
<tr>
<td width="50%" valign="top">

### [Diagrams: Show Me](https://chatgpt.com/g/g-5QGCDylER-diagrams-show-me)

Interactive architectural and workflow visualization GPT. Generates and renders system architectures, sequence diagrams, state machines, and ER diagrams directly in chat using Mermaid.js and PlantUML.

**How to use:**
Prompt: "Draw a sequence diagram for OAuth2 authorization code flow with PKCE" or paste your database schema to generate an entity-relationship diagram.

</td>
<td width="50%" valign="top">

### [Screenshot to Code GPT](https://chatgpt.com/g/g-h8l0HPuvh-screenshot-to-code)

Frontend code generator that takes screenshots of user interfaces, wireframes, or Figma mockups and converts them into production-ready Tailwind CSS, React, Vue, or clean HTML.

**How to use:**
Upload an image or UI screenshot and ask: "Convert this navbar and dashboard layout into responsive React components with Tailwind CSS".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ActionsGPT](https://chatgpt.com/g/g-TYAcjhGDG-actionsgpt)

Developer tool for designing, building, and validating OpenAPI 3.0 schemas for ChatGPT Custom Actions. Configures authentication, parameter definitions, and request/response structures.

**How to use:**
Paste your API docs or cURL commands and prompt: "Convert this API into an OpenAPI 3.0 schema formatted for ChatGPT Custom Actions".

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Prompt Frameworks & System Instruction Kits

<table>
<tr>
<td width="50%" valign="top">

### [ChatGPT-AutoExpert (Developer Edition)](https://github.com/spdustin/ChatGPT-AutoExpert)

Dustin Miller's comprehensive meta-prompting and instruction framework for ChatGPT. Adds verbosity controls, deep multi-turn reasoning, and custom `/memory` session checkpoints to eliminate AI apologies and enforce expert-level software engineering responses.

**How to use:**
Copy the Developer Edition instructions from the repository into your ChatGPT _Custom Instructions_. Use the `/memory` command to snapshot chat state and context.

</td>
<td width="50%" valign="top">

### [Fabric](https://github.com/danielmiessler/fabric)

Daniel Miessler's open-source framework and modular prompt library providing battle-tested Markdown patterns (`create_stride_threat_model`, `review_code`, `explain_code`, `extract_wisdom`) for ChatGPT and coding models.

**How to use:**
Install via `go install github.com/danielmiessler/fabric@latest` or copy individual Markdown patterns directly into your ChatGPT sessions.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [prompts.chat](https://github.com/f/prompts.chat)

The largest open-source community repository of ChatGPT persona templates, coding prompts, and specialized developer roles (Linux terminal emulator, SQL developer, code reviewer).

**How to use:**
Browse prompt templates at https://prompts.chat and paste the system prompt into ChatGPT to instantly initialize specialized developer roles.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Custom Actions & API Connectors (OpenAPI)

<table>
<tr>
<td width="50%" valign="top">

### [GitHub Custom Action for ChatGPT](https://docs.github.com/en/rest)

OpenAPI-based Custom Action that provides ChatGPT direct access to GitHub REST APIs to inspect repository file trees, view pull request diffs, query issues, and comment on PRs.

**How to use:**
In your Custom GPT configuration, add an Action importing the GitHub REST OpenAPI schema and authenticate with a fine-grained GitHub Personal Access Token.

</td>
<td width="50%" valign="top">

### [Zapier AI Actions](https://actions.zapier.com/)

Connects ChatGPT to over 6,000+ business and developer applications (Linear, Jira, Slack, Notion, Google Workspace) via conversational actions.

**How to use:**
Configure actions at actions.zapier.com and import the Zapier OpenAPI action URL into your Custom GPT to trigger actions across your tech stack.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Postman API Platform Action](https://www.postman.com/)

Bridges Postman collections with ChatGPT Custom Actions, enabling the model to explore live API endpoints, run synthetic requests, and validate response contracts against OpenAPI specifications.

**How to use:**
Export your Postman collection as an OpenAPI 3.0 specification and paste it into your Custom GPT's Action configuration.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Data Science, Research & Computational Engines

<table>
<tr>
<td width="50%" valign="top">

### [Wolfram](https://chatgpt.com/g/g-0S5FXStqS-wolfram)

Connects ChatGPT to the Wolfram|Alpha computational engine and Wolfram Language for exact symbolic mathematics, discrete math, differential equations, physics simulations, and scientific graphing.

**How to use:**
Mention `@Wolfram` in ChatGPT: "Solve this second-order differential equation and plot the phase portrait".

</td>
<td width="50%" valign="top">

### [Consensus](https://chatgpt.com/g/g-bo0Fi5Mf7-consensus)

Scientific research assistant connected to 200M+ peer-reviewed academic papers. Conducts literature searches, extracts grounded scientific consensus, and synthesizes citations for technical research.

**How to use:**
Ask Consensus: "What does the research say about developer productivity gains with LLM pair programming? Include paper citations".

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Advanced Data Analysis (Code Interpreter)](https://help.openai.com/en/articles/6825453-chatgpt-advanced-data-analysis)

OpenAI's native sandboxed Python execution environment built into ChatGPT. Executes Python code in real time to analyze datasets, test algorithms, parse ASTs, process images, and generate downloadable files.

**How to use:**
Enable Advanced Data Analysis in ChatGPT Plus/Team/Enterprise. Upload data files, server logs, or scripts and instruct ChatGPT to process and visualize them.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

<img src="assets/logos/kimi.png" alt="Kimi" height="70">

## Kimi

### Official CLI & Core Runtimes

<table>
<tr>
<td width="50%" valign="top">

### [kimi-code](https://github.com/MoonshotAI/kimi-code)

Official AI-powered coding agent from Moonshot AI built directly for your terminal. Distributed as a standalone binary with millisecond-speed startup, native Model Context Protocol (MCP) support, conversational `/mcp-config` tooling, multimodal screen recording analysis, and autonomous shell execution loops.

**How to use:**

1. Single-binary install (macOS/Linux): `curl -fsSL https://code.kimi.com/kimi-code/install.sh | bash` (or on Windows: `irm https://code.kimi.com/kimi-code/install.ps1 | iex`).
2. Via npm: `npm install -g @moonshot-ai/kimi-code`.
3. Run `kimi` in your repository and authenticate with `/login`.

</td>
<td width="50%" valign="top">

### [kimi-plugin-cc](https://github.com/linxule/kimi-plugin-cc)

Dual-model integration plugin that connects Claude Code or Codex CLI directly to Kimi. Enables cross-model adversarial code reviews, second-opinion verification, and background task delegation to Kimi's high-speed reasoning models.

**How to use:**
Install via Claude Code plugin marketplace or `npx skills add linxule/kimi-plugin-cc --agent claude-code`. Use commands like `/kimi:review` or `/kimi:delegate <task>` to run cross-model reviews.

</td>
</tr>
</table>

### Agent Skills & Workflow Plugins

<table>
<tr>
<td width="50%" valign="top">

### [kimi-skills](https://github.com/haomingz/kimi-skills)

Curated directory of modular Agent Skills (`SKILL.md`) for Kimi Code. Encodes structured workflows for automated refactoring, test-driven development (TDD), architecture extraction, and multi-file code generation.

**How to use:**
Install individual skills using `kimi skill install <skill-name>` or copy the desired `SKILL.md` file into your project's `.kimi/skills/` directory.

</td>
<td width="50%" valign="top">

### [kimi-code-hooks](https://github.com/MoonshotAI/kimi-code)

Programmable lifecycle hook system for Kimi Code, allowing developers to configure deterministic pre-tool approvals, post-tool formatting (Prettier, Black, Clang-Format), and automated git pre-commit checks.

**How to use:**
Configure custom lifecycle scripts inside `.kimi/hooks.json` or run `kimi hook add <hook-event>` within your project.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [kimi-subagents](https://github.com/MoonshotAI/kimi-code)

Multi-agent delegation framework for Kimi Code, enabling the primary orchestrating agent to spawn parallel, sandboxed subagents for isolated research, unit test execution, and dependency auditing.

**How to use:**
In Kimi Code, delegate subtasks with `@subagent <task>` or configure specialized agent personas in `.kimi/agents/`.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Long-Context & Document Intelligence Tools

<table>
<tr>
<td width="50%" valign="top">

### [moonshot-mcp-server](https://github.com/MoonshotAI)

Model Context Protocol server exposing Moonshot Kimi's frontier 2M token context window, file ingestion APIs, and structured JSON generation to any MCP-compliant coding assistant or IDE.

**How to use:**
Register the MCP server in your configuration: `claude mcp add moonshot -- npx -y @moonshot-ai/mcp-server --api-key $MOONSHOT_API_KEY`. Ask your agent to ingest massive 500-page specs or whole multi-repo codebases in a single prompt.

</td>
<td width="50%" valign="top">

### [moonshot-python](https://github.com/MoonshotAI/moonshot-python)

Official Moonshot AI Python SDK with native streaming, file caching, tool calling, and long-context document analysis utilities optimized for large-scale code synthesis.

**How to use:**
Install via `pip install moonshot-ai`. Use `moonshot.Client(api_key=...)` to upload files, index codebases, and stream completions with Kimi reasoning models.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [kimi-researcher](https://github.com/MoonshotAI)

Deep research and autonomous multi-source information synthesis agent. Ingests dozens of technical documentation pages, academic PDFs, and GitHub readmes to synthesize grounded architecture recommendations.

**How to use:**
Run via Kimi CLI or API with `kimi research "<technical-topic>" --depth deep`. Produces a structured Markdown research brief with verifiable source citations.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Community Bridges & Developer Utilities

<table>
<tr>
<td width="50%" valign="top">

### [Kimi-Free-API](https://github.com/xiaoY233/Kimi-Free-API)

High-performance reverse-engineered proxy that wraps Kimi AI into a standard OpenAI-compatible API interface (`/v1/chat/completions`), allowing third-party coding agents, Cursor, and IDE extensions to connect to Kimi.

**How to use:**
Deploy locally via Docker: `docker run -d -p 8000:8000 xiaoy233/kimi-free-api:latest`. Point your IDE's OpenAI Base URL to `http://localhost:8000/v1` and supply your Kimi refresh token.

</td>
<td width="50%" valign="top">

### [kimi-web-search-mcp](https://github.com/MoonshotAI)

Real-time web search and live documentation retrieval tool for Kimi Code, querying fresh web APIs, release notes, and documentation pages with anti-hallucination source verification.

**How to use:**
Enable in Kimi Code via `/mcp-config add web-search` or configure as a standard stdio MCP server for agentic browsing.

</td>
</tr>
</table>

<img src="assets/logos/gemini.png" alt="Gemini" height="70">

## Gemini (Extensions)

### Google Workspace & Core Web Extensions

<table>
<tr>
<td width="50%" valign="top">

### [Google Workspace Extension](https://gemini.google.com)

Connects Gemini directly to your Google Workspace account (Gmail, Google Drive, Docs, Sheets, Slides, and Google Calendar). Allows users to summarize email threads, extract actionable items from Drive PDFs/spreadsheets, schedule events, and cross-reference documents directly in chat.

**How to use:**
Enable the Workspace extension in Gemini Settings (`Extensions` toggle). In your prompt, reference your data using `@Google Workspace`, `@Gmail`, or `@Google Drive` (e.g., `@Gmail find invoices from last week and summarize total spend`, `@Google Drive review design-spec.pdf and list architectural requirements`).

</td>
<td width="50%" valign="top">

### [YouTube Extension](https://gemini.google.com)

Enables real-time video understanding, chapter breakdown, transcript search, and multi-hour lecture summarization across any public YouTube URL without downloading media files.

**How to use:**
In Gemini, activate using `@YouTube` with the video link (e.g., `@YouTube https://www.youtube.com/watch?v=... What are the key takeaways from the system architecture section?`).

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Google Maps & Local Intelligence Extension](https://gemini.google.com)

Integrates Google Maps geospatial data, real-time routing, business information, and location-based discovery directly into Gemini conversational reasoning.

**How to use:**
Reference `@Google Maps` in your prompt (e.g., `@Google Maps find coffee shops within walking distance of Union Square with quiet seating and Wi-Fi`).

</td>
<td width="50%" valign="top">

### [Google Flights & Hotels Extension](https://gemini.google.com)

Direct access to live flight schedules, pricing comparisons, hotel availability, and itinerary planning powered by Google Travel infrastructure.

**How to use:**
Reference `@Google Flights` or `@Google Hotels` in your prompt (e.g., `@Google Flights find non-stop flights from SFO to JFK departing next Thursday returning Sunday`).

</td>
</tr>
</table>

### Gemini CLI Developer Extensions & MCP

<table>
<tr>
<td width="50%" valign="top">

### [@google/gemini-cli](https://github.com/google-gemini/gemini-cli)

Official open-source terminal interface for Gemini models with native streaming, automated shell command execution, file system exploration, session history, and slash command extensibility.

**How to use:**
Install globally with `npm install -g @google/gemini-cli`. Export `GEMINI_API_KEY=your_key` and launch with `gemini`. Run `/help` to see available commands or `/extensions` to manage CLI add-ons.

</td>
<td width="50%" valign="top">

### [gemini-cli-extensions](https://github.com/google-gemini)

Extensibility framework for Gemini CLI enabling custom slash commands, contextual project memory (`GEMINI.md`), tool definitions, and modular workflow plugins.

**How to use:**
Create `.gemini/extensions/` in your repository or global config. Define executable workflows and slash commands in Markdown or JavaScript/TypeScript.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [gemini-mcp-bridge](https://github.com/google-gemini)

Model Context Protocol bridge and adapter enabling Gemini developer tools and CLI sessions to connect directly to standard stdio and SSE MCP servers (PostgreSQL, SQLite, GitHub, Playwright).

**How to use:**
Add MCP server configurations into `~/.gemini/mcp.json` or run `gemini mcp add <server-name> -- <command>`. Gemini will discover and invoke tools dynamically during development sessions.

</td>
<td width="50%" valign="top">

### [gemini-cli-security](https://github.com/google-gemini)

Security analysis and vulnerability scanning extension for Gemini CLI. Scans dependencies, detects hardcoded secrets, checks static code patterns against CVE databases, and generates remediation diffs.

**How to use:**
Run `gemini /security:scan` within any local git repository or configure as a pre-commit check.

</td>
</tr>
</table>

### Code Assist & GitHub Workflow Extensions

<table>
<tr>
<td width="50%" valign="top">

### [Gemini Code Assist for GitHub](https://github.com/marketplace/gemini-code-assist)

Official GitHub App by Google Cloud providing automated pull request summaries, intelligent semantic code review, test case generation, and conversational code exploration on GitHub repos.

**How to use:**
Install the GitHub App from GitHub Marketplace on your repositories. Mention `@gemini-code-assist` in PR comments or issues to trigger reviews, ask explanations, or request refactoring suggestions (e.g., `@gemini-code-assist review this PR for concurrency bugs`).

</td>
<td width="50%" valign="top">

### [Gemini Code Assist IDE Extension](https://cloud.google.com/gemini/docs/code-assist/overview)

Official IDE plugin for Visual Studio Code, JetBrains IDEs (IntelliJ IDEA, PyCharm, WebStorm), and Android Studio. Provides inline full-file code completion, chat-assisted debugging, license citation tracking, and enterprise code customization.

**How to use:**
Install "Gemini Code Assist" from the VS Code Marketplace or JetBrains Plugins Marketplace. Sign in with your Google Cloud account or Vertex AI project to begin inline completions and side-panel chat.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [google/skills](https://github.com/google)

Official repository of Google Agent Skills formatted as modular `SKILL.md` instructions for Google Cloud Run, Firebase, Android Jetpack Compose, and Vertex AI development workflows.

**How to use:**
Copy the relevant skill directory into your project's `.skills/` or `.gemini/skills/` directory, or load with `npx skills add google/<skill-name>`.

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

### Cloud, BigQuery & Data Intelligence

<table>
<tr>
<td width="50%" valign="top">

### [bigquery-mcp-server](https://github.com/google-cloud/bigquery-mcp-server)

Model Context Protocol server connecting Gemini and AI agents directly to Google Cloud BigQuery. Enables schema inspection, SQL generation, dry-run cost estimation, query execution, and data visualization.

**How to use:**
Register in your agent's MCP config: `npx -y @google-cloud/bigquery-mcp-server --project $GCP_PROJECT_ID`. Ask Gemini: "Analyze user churn patterns from the analytics dataset and show top retention factors."

</td>
<td width="50%" valign="top">

### [vertex-ai-search-mcp](https://github.com/google-cloud/vertex-search-mcp)

Grounding and search connector exposing Google Vertex AI Search & Conversation datastores over MCP. Allows Gemini agents to query enterprise documents, PDFs, Intranet wikis, and structured databases with citations.

**How to use:**
Configure via MCP JSON: `{"command": "npx", "args": ["-y", "@google-cloud/vertex-search-mcp", "--datastore", "DATASTORE_ID"]}`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [google-cloud-mcp](https://github.com/google-cloud/cloud-mcp)

Infrastructure management and observability MCP server for Google Cloud Platform. Empowers Gemini agents to inspect Cloud Run logs, Cloud Monitoring metrics, compute instances, and IAM permissions directly from chat or terminal.

**How to use:**
Start with `npx @google-cloud/cloud-mcp --project $GCP_PROJECT_ID`. Use prompts like "Check the health and error rates of our production Cloud Run service for the last hour."

</td>
<td width="50%" valign="top">&nbsp;</td>
</tr>
</table>

---

# AGENTS.md

> AGENTS.md is an open Markdown file standard placed at the root of a code repository to give AI coding agents project‑specific instructions, conventions, and commands, used by over 60,000 open‑source projects as of 2026.

Consider copying this file into your own codebase as `AGENTS.md`. It is general-purpose and a good starter file.

```md
# AGENTS.md

## Project Purpose

[Provide a 1-2 sentence description of what this software does so the agent understands the business context. e.g., A multi-tenant web application for managing inventory.]

## Stack & Tech

- **Language:** [e.g., TypeScript / Python 3.10+]
- **Framework:** [e.g., Next.js / FastAPI / Django]
- **Database:** [e.g., PostgreSQL with Prisma / MongoDB]
- **Styling:** [e.g., Tailwind CSS / SCSS]

## Commands

- **Install:** `[e.g., npm install / pip install -r requirements.txt]`
- **Run dev server:** `[e.g., npm run dev]`
- **Run tests:** `[e.g., npm test]`
- **Lint code:** `[e.g., npm run lint]`
- **Build:** `[e.g., npm run build]`

## Repository Structure

- `src/components/`: Reusable interface components.
- `src/features/`: Feature-specific UI and application logic.
- `src/lib/`: Reusable infrastructure and external integrations.
- `src/services/`: Core business logic and database interactions.
- `tests/`: Unit and integration test suites.

## Coding Conventions

- Read the surrounding code before writing new code to match the existing style.
- Use explicit typing for all new functions, variables, and parameters.
- Prefer functional programming patterns where possible; avoid mutating state unexpectedly.
- Keep functions small, testable, and focused on a single responsibility.
- Do not introduce new state-management libraries or major dependencies without explicit permission.

## Architecture Rules

- Keep route handlers/controllers thin; delegate heavy logic to the `services/` layer.
- Validate all external input at the system boundaries.
- Never call the database directly from reusable UI components.
- Reuse existing domain services and helper functions before creating new ones.

## Testing

- Add or update tests for any changed public behavior.
- Prefer behavior-based assertions over testing private implementation details.
- Run affected tests to ensure they pass before completing a task.
- Do not weaken validation, types, or tests just to make a failing test pass.

## Security & Boundaries

- Never log user IDs, access tokens, API keys, passwords, or PII.
- Enforce resource ownership and authorization on the backend for all protected routes.
- Use the existing secret-management/environment-variable system.
- Do not run destructive database migrations without explicit approval.

> **To Agent**: If this `AGENTS.md` file is _not_ filled in yet, consider filling it in yourself as you analyze the codebase.
```

# Tooling Suggestions

> This is a list of tools you should consider using, organized by type of tool (IDE, code review, et cetera).

## Vibe Coding IDEs & App Builders

### AI-Native IDEs & Agentic Workspaces

<table>
<tr>
<td width="50%" valign="top">

### [Google Antigravity](https://antigravity.google/)

Google's advanced agentic coding platform and AI IDE built for deep pair programming and autonomous task execution. Powered by Gemini reasoning models, Antigravity features parallel subagent swarms, asynchronous background execution, interactive rich markdown artifacts, generative UI widgets, Model Context Protocol (MCP) tool integration, extensible skills/rules architectures, and the official `agy` CLI for seamless terminal-to-IDE workflows.

**Key Capabilities:**
Multi-agent orchestration, interactive artifacts, subagent delegation, background task management, and native `agy` CLI integration.

</td>
<td width="50%" valign="top">

### [Cursor](https://cursor.com/)

Cursor combines AI-first development, intelligent automation, and enterprise scalability to enhance coding efficiency. Its unique combination of multi-model support (Claude 3.5 Sonnet, GPT-4o), parallel agent workflows via Composer, semantic codebase indexing, and shadow workspace linting makes it a transformative tool for individual developers and teams.

**Key Capabilities:**
Composer multi-file editing, custom `.cursorrules` prompt guidance, semantic symbol indexing, and instant shadow linting.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Windsurf](https://windsurf.com/)

Codeium's next-generation AI IDE built around the Cascade collaborative agent. Features real-time deep codebase awareness, predictive edits via Supercomplete, multi-file refactoring, and enterprise-grade security, making it a strong choice for teams and large codebases.

**Key Capabilities:**
Cascade collaborative agent, real-time multi-repo indexing, predictive next-action flow, and VS Code extension compatibility.

</td>
<td width="50%" valign="top">

### [Trae](https://www.trae.ai/)

An adaptive, AI-native IDE built on VS Code with the Claude 3.5 Sonnet and GPT-4o powered 'Builder' multi-agent mode. Features workspace-wide contextual indexing, multimodal chat, and automated terminal execution for rapid full-stack prototyping.

**Key Capabilities:**
Builder multi-agent mode, multimodal workspace chat, project-wide symbol indexing, and free tier model access.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Zed](https://zed.dev/)

An ultra-fast, GPU-accelerated code editor written in Rust with built-in multi-model AI assistant workflows. Features inline prompt transformations, model switching (Claude, OpenAI, Ollama), native Model Context Protocol (MCP) support, and real-time multiplayer pair programming.

**Key Capabilities:**
Sub-millisecond latency, GPU rendering, native MCP support, inline transformations, and collaborative multiplayer editing.

</td>
<td width="50%" valign="top">

### [Void](https://voideditor.com/)

An open-source, privacy-first Cursor alternative that gives developers full control over their code and telemetry. Connects directly to local models (Ollama, vLLM) or private API keys with support for multi-file editing, chat, and custom agent tools.

**Key Capabilities:**
Zero telemetry, local model execution (Ollama/vLLM), private API keys, and open-source customizable architecture.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [PearAI](https://trypear.ai/)

An open-source AI code editor (backed by Y Combinator) designed as a community-driven, transparent alternative to proprietary AI IDEs. Integrates vetted open-source AI extensions, conversational chat, inline refactoring, and multi-model support into a unified distribution.

**Key Capabilities:**
Curated open-source agent integration, transparent ecosystem, multi-model flexibility, and community-driven development.

</td>
<td width="50%" valign="top">

### [Melty](https://melty.dev/)

The first open-source AI code editor that observes your programming workflow from compiler output to terminal commands and git commits, anticipating your next steps and generating clean, context-aware commit messages and diffs.

**Key Capabilities:**
Compiler-aware feedback loops, automated semantic commit drafting, state-of-flow tracking, and self-hosted privacy.

</td>
</tr>
</table>

### Autonomous Software Engineers & Cloud Agents

<table>
<tr>
<td width="50%" valign="top">

### [Devin](https://devin.ai/)

The first autonomous AI software engineer by Cognition Labs. Operates inside a secure, sandboxed cloud environment with a full browser, terminal, code editor, and planner, enabling it to build complex features, debug code, and resolve GitHub issues end-to-end.

**Key Capabilities:**
End-to-end autonomous task execution, sandboxed browser/terminal environment, SWE-bench performance, and automated PR submission.

</td>
<td width="50%" valign="top">

### [OpenHands](https://all-hands.dev/)

The premier open-source autonomous AI software developer platform (formerly OpenDevin) with community-leading SWE-bench scores. Operates within an isolated Docker sandbox with access to a terminal, web browser, and file editor to resolve GitHub issues and build software packages.

**Key Capabilities:**
Open-source autonomous runtime, Docker sandboxing, extensible agent architectures, and community-driven benchmark leadership.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Replit Agent](https://replit.com/)

An autonomous cloud software builder that takes high-level project descriptions and manages the entire development lifecycle: setting up PostgreSQL databases, installing dependencies, writing backend and frontend logic, and deploying live production applications with zero local configuration.

**Key Capabilities:**
Zero-config cloud deployments, automatic database provisioning, live app hosting, and autonomous multi-file scaffolding.

</td>
<td width="50%" valign="top">

### [GitHub Copilot Workspace](https://github.com/features/copilot)

A task-centric development environment that bridges GitHub Issues and Pull Requests. Synthesizes a specification, devises a multi-step plan, edits files across the repository, and submits refined pull requests directly from GitHub.

**Key Capabilities:**
Issue-to-PR automated workflow, multi-file specification planning, native GitHub integration, and team collaboration.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Goose](https://block.github.io/goose/)

An open-source, autonomous AI developer agent created by Block. Runs locally on your machine, interacts directly through the terminal to execute shell commands, navigates project directories, and connects to external services and developer tools via MCP.

**Key Capabilities:**
Local CLI execution, autonomous tool calling, extensible Model Context Protocol (MCP) integrations, and enterprise open-source backing.

</td>
<td width="50%" valign="top">

### [Pythagora (GPT Pilot)](https://github.com/Pythagora-io/gpt-pilot)

A step-by-step autonomous software development agent that builds production applications from the ground up. Interviews the developer about architecture requirements, scaffolds files, runs tests, inspects runtime logs, and debugs errors collaboratively.

**Key Capabilities:**
Interactive developer onboarding, step-by-step verified code synthesis, runtime log debugging, and full-stack scaffolding.

</td>
</tr>
</table>

### Prompt-to-App & Full-Stack Prototyping Platforms

<table>
<tr>
<td width="50%" valign="top">

### [Lovable](https://lovable.dev/)

An AI-powered full-stack development platform that acts like an IDE where you build web applications by describing them in natural language. It generates production-ready frontend, backend, Supabase database schemas, and external API integrations with instant visual previews.

**Key Capabilities:**
Rapid conversational app building, Supabase backend integration, GitHub bidirectional synchronization, and live web preview.

</td>
<td width="50%" valign="top">

### [Bolt.new](https://bolt.new/)

StackBlitz's in-browser full-stack development environment powered by WebContainers. Turns natural-language prompts into running full-stack applications directly in the browser, complete with Node.js package execution, live reload, instant hosting, and database connectivity.

**Key Capabilities:**
In-browser WebContainer execution, zero-install npm package support, instant hosting, and rapid prototype sharing.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [v0 by Vercel](https://v0.dev/)

Vercel's generative UI and full-stack web application builder. Crafts production-ready React, Next.js, and Tailwind CSS interfaces from natural language or Figma designs, featuring real-time visual iteration, component-level prompting, and one-click Vercel deployments.

**Key Capabilities:**
Generative React/Tailwind UI, Figma-to-code import, component-level prompt iteration, and 1-click Vercel deployments.

</td>
<td width="50%" valign="top">

### [Marblism](https://marblism.com/)

A specialized prompt-to-app platform designed for building SaaS products. Generates complete, deployable codebases featuring Next.js, Prisma ORM, PostgreSQL, Stripe payments, authentication, and Tailwind UI from natural-language specifications.

**Key Capabilities:**
Production-ready SaaS scaffolding, pre-configured Stripe monetization, Prisma ORM database models, and authentication.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Tempo Labs](https://tempolabs.ai/)

A generative visual React workspace that lets developers build, style, and edit production React and Tailwind CSS components either visually or through natural-language prompts, with instant bidirectional synchronization to GitHub repositories.

**Key Capabilities:**
Bidirectional visual canvas and code sync, production React/Tailwind output, component design system alignment, and GitHub sync.

</td>
<td width="50%" valign="top">

### [Create.xyz](https://www.create.xyz/)

A prompt-driven visual app development platform that converts natural language into live, full-stack React components, tools, and web apps with integrated backend state, databases, and serverless functions.

**Key Capabilities:**
Instant functional prototyping, built-in serverless backends, universal component generation, and rapid embed capabilities.

</td>
</tr>
</table>

### Terminal Coding Agents & CLI Workflows

<table>
<tr>
<td width="50%" valign="top">

### [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview)

Anthropic's official agentic terminal interface that navigates entire codebases, runs commands, executes test suites, diagnoses errors, and commits git changes autonomously with deep reasoning powered by Claude 3.7 Sonnet.

**Key Capabilities:**
Codebase-wide semantic search, autonomous test-driven repair loops, terminal command execution, and git workflow integration.

</td>
<td width="50%" valign="top">

### [Aider](https://aider.chat/)

The leading terminal-based AI pair programming tool. Automatically constructs a tree-sitter AST map of your entire git repository to understand symbol relationships, edits code across multiple files, and crafts clean, conventional git commit messages with diffs.

**Key Capabilities:**
Tree-sitter repository map AST indexing, multi-model support, voice prompt input, and automated git commit generation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Cline](https://cline.bot/ide)

The original surface for the Cline agent: an open-source chat sidebar for VS Code that reads files, executes terminal commands, edits code, interacts with browser sessions, and requires explicit user approvals before applying changes.

**Key Capabilities:**
Human-in-the-loop tool approvals, browser testing integration, MCP tool support, and multi-file code editing.

</td>
<td width="50%" valign="top">

### [Roo Code](https://roocode.com/)

An advanced autonomous AI coding assistant extension for VS Code (fork of Cline) featuring customizable agent modes (Architect, Code, Ask, Debugger), fine-grained token usage tracking, Model Context Protocol (MCP) tool support, and interactive diff approvals.

**Key Capabilities:**
Specialized agent role personas (Architect/Coder/Debugger), token cost analytics, MCP server integration, and custom rules.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Continue](https://continue.dev/)

The leading open-source AI code assistant extension for VS Code and JetBrains IDEs. Offers modular connectivity to any local (Ollama, LM Studio) or cloud model, custom `@` context providers (codebase, git diffs, docs), slash commands, and native Model Context Protocol (MCP) tools.

**Key Capabilities:**
Modular model backend (local & cloud), `@` context providers, slash commands, custom system prompts, and native MCP support.

</td>
<td width="50%" valign="top">

### [Plandex](https://plandex.ai/)

An open-source, terminal-based AI engine built specifically for large, complex multi-file engineering tasks. Uses git branch sandboxing, persistent conversation graphs, and structured plan-review workflows that let developers inspect and approve diffs before committing them.

**Key Capabilities:**
Isolated git branch sandboxing, long-running persistent task context, multi-file diff inspection, and plan-first execution.

</td>
</tr>
</table>

### Enterprise Code Intelligence & Code Graph Assistants

<table>
<tr>
<td width="50%" valign="top">

### [Sourcegraph Cody](https://sourcegraph.com/cody)

An enterprise-grade AI coding assistant powered by Sourcegraph's comprehensive code graph and multi-repo semantic search, enabling accurate codebase-wide context retrieval, multi-file code generation, and automated documentation.

**Key Capabilities:**
Enterprise multi-repo code graph search, precise context retrieval, SOC 2 compliance, and guardrails against hallucinations.

</td>
<td width="50%" valign="top">

### [Amazon Q Developer](https://aws.amazon.com/q/developer/)

AWS's generative AI coding companion designed for software development, cloud infrastructure, and enterprise legacy modernization. Features autonomous feature development agents, security vulnerability scanning, automated Java version upgrades, and AWS service diagnostics.

**Key Capabilities:**
Autonomous software development agents, automated legacy Java migrations, AWS resource diagnostics, and security remediation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Tabnine](https://www.tabnine.com/)

An enterprise-focused, privacy-first AI code assistant that guarantees zero code retention and offers full on-premises or VPC deployments, trained strictly on permissively licensed open-source code or your organization's private codebase.

**Key Capabilities:**
Zero data retention guarantee, air-gapped on-premise deployment, proprietary codebase fine-tuning, and IP indemnification.

</td>
<td width="50%" valign="top">

### [Potpie](https://potpie.ai/)

An open-source platform for creating codebase-specific AI agents that understand complex software architectures for automated debugging, integration testing, system design analysis, and code review.

**Key Capabilities:**
Codebase knowledge graphs, custom agent creation, automated regression testing, and architectural verification.

</td>
</tr>
</table>

## Model Context Protocol (MCP) Servers

### Core Developer, Version Control & Local Workspaces

<table>
<tr>
<td width="50%" valign="top">

### [GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github)

The official GitHub MCP server enabling agents to search repositories, inspect file contents, analyze pull requests, review commits, create issues, and manage GitHub Actions CI workflows.

**Key Capabilities:**
Repository search, pull request creation/reviews, issue triage, branch management, and GitHub Actions monitoring.

</td>
<td width="50%" valign="top">

### [Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)

The reference Model Context Protocol server that provides AI agents with strictly scoped, secure read, write, move, and search access across local project directories with sandboxed directory path boundaries.

**Key Capabilities:**
Scoped directory access, recursive file search, fast text/binary reads, write approvals, and file tree inspection.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git)

Direct MCP tool integration for local git repositories. Enables agents to inspect commit histories, read uncommitted working tree diffs, stage files, switch branches, and view git blame annotations.

**Key Capabilities:**
Local commit inspection, diff generation, branch switching, status checks, and staging operations.

</td>
<td width="50%" valign="top">

### [GitLab MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab)

Full enterprise GitLab integration for MCP. Allows AI assistants to inspect merge requests, triage issues, trigger and monitor CI/CD pipelines, and interact with GitLab repository branches via the REST API.

**Key Capabilities:**
Merge request reviews, pipeline status tracking, issue management, project repository browsing, and API access.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Memory MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)

A graph-based persistent memory server for agents. Uses a knowledge graph structure to persist entities, relations, observations, and user preferences across distinct coding sessions without context loss.

**Key Capabilities:**
Persistent knowledge graph storage, entity creation, relationship linking, contextual recall, and session persistence.

</td>
<td width="50%" valign="top">

### [Terminal / Bash MCP](https://github.com/modelcontextprotocol/servers)

A secure shell execution server that provides agents with controlled, configurable terminal access for running build tools, test suites, package managers, and formatters with captured stdout and stderr.

**Key Capabilities:**
Command execution, build tool automation, test suite verification, background process management, and output capture.

</td>
</tr>
</table>

### Databases, Data Warehouses & Cache

<table>
<tr>
<td width="50%" valign="top">

### [PostgreSQL MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)

The official PostgreSQL server providing read-only or read-write database connectivity. Allows agents to discover schemas, inspect table structures, analyze indexes, explain query plans, and execute analytical SQL queries.

**Key Capabilities:**
Schema discovery, SQL query execution, EXPLAIN query plan analysis, table column introspection, and index tuning.

</td>
<td width="50%" valign="top">

### [SQLite MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)

Lightweight, zero-config local database connector allowing agents to query tables, inspect schemas, parse relationships, and run analytical queries over local `.sqlite` or `.db` files.

**Key Capabilities:**
Local database querying, schema introspection, automated SQL generation, and embedded analytics.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Redis MCP](https://github.com/redis/mcp-redis)

Official Redis integration for MCP. Provides agents with real-time access to key-value stores, allowing key inspection, data type queries (strings, hashes, lists, sets, streams), cache TTL verification, and pub/sub monitoring.

**Key Capabilities:**
Cache key inspection, key TTL management, data structure querying, pub/sub testing, and cache optimization.

</td>
<td width="50%" valign="top">

### [BigQuery MCP](https://github.com/google-cloud/bigquery-mcp-server)

Direct Google Cloud BigQuery connector exposing enterprise data warehouse datasets. Enables schema discovery, query generation, dry-run cost estimation, and large-scale data analytics over standard SQL.

**Key Capabilities:**
Data warehouse schema inspection, cost estimation dry-runs, SQL query execution, and analytical dataset synthesis.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Snowflake MCP](https://github.com/Snowflake-Labs/mcp-server-snowflake)

Official Snowflake MCP server for enterprise cloud data platforms. Enables agents to discover database schemas, inspect table schemas, execute SQL queries, and manage data governance pipelines.

**Key Capabilities:**
Data warehouse exploration, analytical SQL querying, role-based access management, and dataset discovery.

</td>
<td width="50%" valign="top">

### [Qdrant Vector MCP](https://github.com/qdrant/mcp-server-qdrant)

Vector search engine MCP server that gives agents semantic retrieval capabilities over embedding databases. Enables similarity searches, document clustering, and retrieval-augmented generation (RAG) over vector collections.

**Key Capabilities:**
Vector similarity search, payload filtering, collection management, and semantic document grounding.

</td>
</tr>
</table>

### Web Browsing, Search & Content Extraction

<table>
<tr>
<td width="50%" valign="top">

### [Playwright MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/playwright)

Official browser automation server allowing agents to drive real Chromium, Firefox, and WebKit browsers. Executes clicks, form submissions, navigation, console log capturing, and structured accessibility snapshot inspections.

**Key Capabilities:**
End-to-end browser automation, accessibility tree snapshots, form interactions, visual screenshot capture, and UI testing.

</td>
<td width="50%" valign="top">

### [Puppeteer MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)

Headless Chrome automation tool enabling agents to navigate web pages, execute client-side JavaScript, capture full-page screenshots, generate PDFs, and scrape dynamic client-rendered web content.

**Key Capabilities:**
Headless Chrome execution, client-side JS evaluation, screenshot/PDF rendering, and dynamic DOM extraction.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Firecrawl MCP](https://github.com/mendableai/firecrawl-mcp-server)

Direct MCP bridge to the Firecrawl engine. Crawls complex, dynamic websites, bypasses anti-bot obstacles, and returns clean, LLM-ready markdown optimized for developer agent ingestion.

**Key Capabilities:**
Deep subpage web crawling, JavaScript-rendered scraping, clean markdown conversion, and anti-bot mitigation.

</td>
<td width="50%" valign="top">

### [Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)

Official web search and local business intelligence connector powered by Brave's independent, privacy-focused search index. Provides fresh web search results, news queries, and URL discovery.

**Key Capabilities:**
Independent web search indexing, real-time news retrieval, localized business queries, and clean link extraction.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Tavily MCP](https://github.com/tavily-ai/tavily-mcp)

An AI-native search engine designed specifically for LLMs and autonomous research agents. Delivers hallucination-resistant, factually grounded web search summaries with direct source citations.

**Key Capabilities:**
Autonomous research search, factual source grounding, concise answer extraction, and developer API search.

</td>
<td width="50%" valign="top">

### [Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)

A lightweight, efficient HTTP resource fetcher that downloads web pages, parses raw HTML, strips boilerplate headers and scripts, and converts content into clean, readable markdown for agent reasoning.

**Key Capabilities:**
Fast URL fetching, HTML-to-Markdown conversion, boilerplate stripping, and structured content extraction.

</td>
</tr>
</table>

### DevOps, Cloud Infrastructure & Observability

<table>
<tr>
<td width="50%" valign="top">

### [Docker MCP](https://github.com/ckreiling/mcp-server-docker)

Comprehensive Docker engine management server. Enables agents to inspect running containers, view container logs, start/stop services, build images from Dockerfiles, and audit network configurations.

**Key Capabilities:**
Container lifecycle management, real-time log streaming, image inspection, and Docker Compose orchestration.

</td>
<td width="50%" valign="top">

### [Kubernetes MCP](https://github.com/strowk/mcp-k8s)

Direct cluster management server for Kubernetes environments. Empowers agents to query pods, inspect deployment manifests, stream container logs, review cluster events, and debug infrastructure failures.

**Key Capabilities:**
Pod inspection, log streaming, deployment status checks, namespace management, and cluster event auditing.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Sentry MCP](https://github.com/getsentry/sentry-mcp)

Official Sentry integration for real-time application monitoring. Allows agents to query production issues, examine stack traces, inspect error breadcrumbs, analyze release regressions, and suggest code fixes.

**Key Capabilities:**
Production issue triage, stack trace analysis, error tag filtering, release tracking, and automated patch suggestions.

</td>
<td width="50%" valign="top">

### [Google Cloud MCP](https://github.com/google-cloud/cloud-mcp)

Official infrastructure management and observability server for Google Cloud Platform. Enables agents to inspect Cloud Run logs, check Cloud Monitoring metrics, view compute instances, and audit IAM permissions.

**Key Capabilities:**
Cloud Run log analysis, Cloud Monitoring metrics, compute resource inspection, and GCP IAM diagnostics.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AWS MCP](https://github.com/awslabs/mcp-server-aws)

Official AWS resource management MCP server. Allows agents to query CloudWatch logs, inspect S3 buckets, check Lambda function executions, review ECS clusters, and diagnose cloud infrastructure configurations.

**Key Capabilities:**
CloudWatch log querying, S3 object inspection, Lambda function monitoring, and AWS resource management.

</td>
<td width="50%" valign="top">

### [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare)

Official Cloudflare server for edge infrastructure management. Enables agents to inspect and update DNS records, deploy Workers, manage KV namespaces, and execute queries against D1 SQL databases.

**Key Capabilities:**
DNS record management, Cloudflare Workers deployment, KV store operations, and D1 database queries.

</td>
</tr>
</table>

### Team Collaboration, Project Management & Docs

<table>
<tr>
<td width="50%" valign="top">

### [Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)

Official Slack integration for team communication. Allows AI agents to read public channels, search team chat histories, post status updates, create messages, and summarize threaded technical discussions.

**Key Capabilities:**
Channel message reading, conversational thread summarization, broadcast updates, and team collaboration.

</td>
<td width="50%" valign="top">

### [Linear MCP](https://github.com/jerhadf/linear-mcp-server)

High-speed project and issue tracking tool for engineering teams. Enables agents to search issues, create tickets, update project roadmaps, assign cycles, and manage sprint backlogs on Linear.

**Key Capabilities:**
Issue creation/updating, sprint cycle management, team roadmap tracking, and workflow automation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Atlassian Jira & Confluence MCP](https://github.com/atlassian/mcp-atlassian)

Official Atlassian integration connecting agents directly to Jira and Confluence. Enables agents to search enterprise project tickets, update sprint boards, and read/write engineering documentation.

**Key Capabilities:**
Jira issue tracking, sprint board updates, Confluence page search, and technical documentation drafting.

</td>
<td width="50%" valign="top">

### [Notion MCP](https://github.com/suekou/mcp-notion-server)

Direct Notion workspace integration. Allows agents to query databases, search workspace pages, read and append rich text blocks, and extract product requirements and specifications directly into code.

**Key Capabilities:**
Workspace database search, page block reading/writing, rich text formatting, and spec extraction.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Google Drive & Workspace MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)

Official Google Drive integration for MCP. Enables agents to search files across corporate Drives, extract text from PDFs, read Google Docs and Sheets, and synthesize cross-document insights.

**Key Capabilities:**
Drive file search, Google Docs/Sheets ingestion, PDF text extraction, and enterprise document grounding.

</td>
<td width="50%" valign="top">

### [Figma MCP](https://github.com/modelcontextprotocol/servers)

Design context integration allowing agents to inspect Figma design files, extract component trees, retrieve color/typography tokens, and translate visual layouts into production frontend code.

**Key Capabilities:**
Design token extraction, component hierarchy inspection, visual layout translation, and design-to-code pipelines.

</td>
</tr>
</table>

## Core Agent Frameworks

### Graph-Based & Stateful Multi-Agent Orchestrators

<table>
<tr>
<td width="50%" valign="top">

### [LangGraph](https://www.langchain.com/langgraph)

Leading open-source graph-based framework for designing precise, stateful, and cyclic multi-agent workflows. Enables complex multi-agent coordination with built-in persistence, human-in-the-loop approvals, time-travel debugging, and streaming architectures.

**Key Capabilities:**
Cyclic graph state machines, persistent memory checkpointers, human-in-the-loop approval gates, streaming execution, and multi-agent subgraphs.

</td>
<td width="50%" valign="top">

### [CrewAI](https://www.crewai.com/)

Premier role-based multi-agent orchestration framework for Python. Empowers autonomous agents to assume specialized personas, collaborate in structured crews, share memory, and delegate tasks sequentially or hierarchically.

**Key Capabilities:**
Role-based agent personas, autonomous task delegation, hierarchical and sequential processes, cross-agent memory, and rich tool integrations.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Microsoft Agent Framework](https://github.com/microsoft/autogen)

The unified enterprise multi-agent orchestrator for the .NET and Python ecosystems, succeeding AutoGen and Semantic Kernel agents. Provides production-grade multi-agent coordination, event-driven messaging, enterprise observability, and declarative workflow execution.

**Key Capabilities:**
Unified .NET & Python runtime, event-driven multi-agent messaging, distributed agent state, OpenTelemetry observability, and enterprise cloud connectors.

</td>
<td width="50%" valign="top">

### [OpenAI Agents SDK](https://platform.openai.com/docs/guides/agents)

OpenAI's official lightweight, ergonomic framework optimized for building tightly scoped assistants, clean function execution, and multi-agent delegation. Features declarative agent definitions, stateful sessions, and seamless agent handoffs.

**Key Capabilities:**
Lightweight agent handoffs, guardrails validation, stateful session handling, built-in function calling, and native OpenAI model optimization.

</td>
</tr>
</table>

### Code-First & Type-Safe Agent Frameworks

<table>
<tr>
<td width="50%" valign="top">

### [Google Agent Development Kit (ADK)](https://github.com/google/agents)

Google's official agentic framework and SDK for building production AI agents with Gemini reasoning models. Features native multimodal streaming, code execution sandboxes, Grounding with Google Search, and seamless Model Context Protocol (MCP) tool integration.

**Key Capabilities:**
Native Gemini 2.0/2.5 multimodal integration, Google Search grounding, code execution sandboxes, Model Context Protocol (MCP) client, and Vertex AI Agent Builder deployment.

</td>
<td width="50%" valign="top">

### [PydanticAI](https://ai.pydantic.dev/)

Production-grade, type-safe Python agent framework created by the Pydantic team. Brings static type checking, runtime schema validation, dependency injection, and ergonomic streaming to generative AI agent workflows.

**Key Capabilities:**
Strict type validation via Pydantic V2, typed dependency injection, structured data extraction, real-time streaming validation, and model-agnostic architecture.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [LlamaIndex Workflows](https://docs.llamaindex.ai/en/stable/module_guides/workflow/)

An event-driven, execution-graph agent framework designed for complex document retrieval, structured data reasoning, and advanced RAG architectures. Coordinates independent async steps through typed events with full observability.

**Key Capabilities:**
Event-driven step orchestration, typed event propagation, advanced multi-modal RAG routing, async concurrency, and OpenInference tracing.

</td>
<td width="50%" valign="top">

### [Smolagents](https://github.com/huggingface/smolagents)

Hugging Face's lightweight, code-first agent framework. Rather than forcing agents through verbose JSON tool calling, agents formulate actions by writing and executing raw Python code blocks, drastically reducing token consumption and latency.

**Key Capabilities:**
Code-agent execution loops, secure Python sandboxing, Hugging Face Hub integration, minimal dependency footprint, and multi-model support.

</td>
</tr>
</table>

### Optimization, Evaluation & Production Runtimes

<table>
<tr>
<td width="50%" valign="top">

### [DSPy](https://github.com/stanfordnlp/dspy)

Stanford NLP's groundbreaking framework for programming rather than prompting foundation models. Replaces brittle prompt engineering with declarative modules and self-improving teleprompters/compilers that optimize prompts and few-shot examples automatically.

**Key Capabilities:**
Declarative LM programming, automated prompt compilers/optimizers, multi-stage pipeline verification, metric-driven self-tuning, and deterministic assertions.

</td>
<td width="50%" valign="top">

### [Agno](https://github.com/agno-agi/agno)

High-performance, lightweight multi-modal agent framework (formerly Phidata). Built for ultra-fast execution speed and low latency, featuring built-in vector memory, structured outputs, multi-agent teams, and visual UI monitoring.

**Key Capabilities:**
Ultra-low latency execution, native multi-modal memory, structured JSON generation, agent team routing, and real-time reasoning visualization.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Haystack](https://haystack.deepset.ai/)

Modular, enterprise-grade open-source framework by deepset for building customized LLM pipelines, autonomous agents, and search applications. Features composable nodes, document store integrations, and production scalability.

**Key Capabilities:**
Composable pipeline graph architecture, diverse document store integrations, conditional branching, tool-augmented agent loops, and evaluation metrics.

</td>
<td width="50%" valign="top">

### [Dify](https://dify.ai/)

Leading open-source LLM application and multi-agent development platform. Combines a visual workflow canvas, prompt IDE, RAG pipeline orchestrator, and agent runtime with production monitoring and API access.

**Key Capabilities:**
Visual drag-and-drop workflow canvas, multi-agent orchestration, enterprise RAG pipelines, API-first architecture, and comprehensive observability.

</td>
</tr>
</table>
