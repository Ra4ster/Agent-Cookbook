# Contributing to the Agent Cookbook

First off, thank you for considering contributing to the Agent Cookbook! This repository relies on the community to stay up-to-date with the rapidly moving AI agent and vibecoding ecosystem.

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

## 🛠️ How to Add a New Tool or Plugin

To keep the cookbook clean, scannable, and highly useful, all tool additions **must** follow a strict formatting structure.

### The Required Format

When adding a tool to any list, use the following Markdown format exactly:

```markdown
- **[Tool Name](URL)** - _[Open Source / Paid / Freemium]_ - [One concise sentence explaining what it does].
  - _Why it's useful:_ [One sentence explaining how a developer practically uses this in vibecoding or agent building].
```

```

**Example:**

- **[LangGraph](https://langchain-ai.github.io/langgraph/)** - _Open Source_ - A library for building stateful, multi-actor applications with LLMs.
- _Why it's useful:_ Allows developers to define cyclic graphs for agents that need memory and looping autonomous capabilities.

### Rules for Submission

1. **Alphabetical Order:** Please insert your tool alphabetically within its category.
2. **No Marketing Fluff:** Keep descriptions factual, technical, and objective. Do not use words like "revolutionary," "magical," or "best-in-class." Let the tool's utility speak for itself.
3. **No Duplicates:** Use `Ctrl+F` or `Cmd+F` to search the README before submitting to ensure the tool isn't already listed.

## 📂 Proposing New Categories

The agent ecosystem is growing fast, and new categories will be needed. However, to avoid clutter:

- **Do not create a new category (H3) for a single tool.**
- Propose a new category only if you have **at least 3 tools** to populate it.
- If your tool doesn't fit neatly into an existing category and you don't have 3 to make a new one, place it in the closest logical existing category or under a "Miscellaneous" header.

## 🚀 Pull Request Process

1. **Fork** the repository and clone it to your local machine.
2. **Create a branch** for your edits: `git checkout -b add/my-awesome-tool`.
3. **Edit** the `README.md` (or other relevant files) following the formatting rules above.
4. **Commit** your changes using [Conventional Commits](https://www.conventionalcommits.org/):

- _Example:_ `docs: add Windsurf to Vibe Coding IDEs section`

5. **Push** your branch: `git push origin add/my-awesome-tool`.
6. **Open a Pull Request** against the `main` branch of this repository.

## 🐛 Found a broken link or typo?

If you spot a dead link, an outdated project, or a simple typo, you don't need to open an issue first. Feel free to just open a Pull Request with the fix!

For larger structural changes, please open an Issue first to discuss it with the maintainers.

---

_By contributing to this repository, you agree that your contributions will be licensed under its MIT License._
```
