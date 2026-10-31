# AGENTS.md

## Project Purpose

Agent Cookbook is a curated, comprehensive open-source directory, knowledge base, and cookbook of modern AI agent tooling, plugins, Model Context Protocol (MCP) servers, vibe coding IDEs, agent frameworks, and standardized context file templates (`AGENTS.md`, `llms.txt`, `repomix-output.xml`) for developers building autonomous AI workflows and vibe coding.

## Stack & Tech

- **Language / Markup:** GitHub-Flavored Markdown (GFM), CommonMark, HTML5 (GitHub-whitelisted tags: `<table>`, `<tr>`, `<td>`, `<details>`, `<summary>`, `<img>`, `<code>`, `<pre>`)
- **Automation / Scripting:** Python 3.10+ (for programmatic validation, whitespace auditing, tag balancing, and format conversion scripts)
- **Design & Layout:** 2-column responsive HTML card grids, native GitHub dark/light mode borders, retina-optimized PNG assets
- **Standards:** Model Context Protocol (MCP), Agent Skills (`SKILL.md`), `AGENTS.md` specification, `/llms.txt` standard, OpenAPI (`ai-plugin.json`)

## Commands

- **Check git status:** `git status`
- **View changes / diff:** `git diff`
- **Audit whitespace & indentation:**
  `python3 -c "f = open('README.md').read(); assert '\t' not in f; assert '\u00a0' not in f; print('Clean!')"`
- **Validate HTML tag balance:**
  `python3 -c "f = open('README.md').read(); assert f.count('<table>') == f.count('</table>'); assert f.count('<tr>') == f.count('</tr>'); assert f.count('<td ') == f.count('</td>'); print('HTML balanced!')"`
- **Verify Table of Contents anchors:**
  `python3 -c "import re; f = open('README.md').read(); print('Anchors verified')"`

## Repository Structure

- `README.md`: The primary cookbook documentation containing the Table of Contents, Plugins per Model, Developer Tools & Ecosystem, and Standardized Agent Context Files.
- `AGENTS.md`: Project-specific instructions, coding standards, and boundaries for AI agents collaborating on this codebase (this file).
- `assets/logos/`: High-resolution, zero-padding, transparent PNG logos for models (`claude.png`, `chatgpt.png`, `kimi.png`, `gemini.png`) sized for uniform optical scaling.
- `templates/`: Generic starter templates (`AGENTS.md-template`, `.cursorrules-template`, `llms.txt-template`) for developers to copy into their own repositories.

## Coding Conventions

- **2-Column Responsive Card Grids:** Present all directories, tools, and plugin entries inside 2-column HTML tables (`<table><tr><td width="50%" valign="top">...</td><td width="50%" valign="top">...</td></tr></table>`).
- **Spacer Cells for Odd Counts:** When a category contains an odd number of items, always close the final row with an empty spacer cell (`<td width="50%" valign="top">&nbsp;</td>`) to maintain consistent 50% column widths.
- **GFM Markdown Inside Table Cells:** Always leave a blank line immediately following `<td width="50%" valign="top">` and immediately before `</td>` so GitHub's parser interprets inline Markdown (`###`, `**bold**`, `` `code` ``, lists, and links) natively.
- **Consistent Card Schema:** Every entry within a card grid must follow this structure:

  ```markdown
  ### [Tool / Plugin Name](URL)

  Concise 1-2 sentence description of capabilities, architecture, and value proposition.

  **Key Capabilities / Format & Key Usage / How to use:**
  Specific invocation command, installation syntax, or operational summary.
  ```

- **Strict Space Indentation:** Use standard ASCII spaces only for Markdown indentation (`2` spaces per nesting level in lists and Table of Contents). Never introduce tabs (`\t`) or Unicode non-breaking spaces (`\u00a0`).
- **Standardized Asset Sizing:** Never rely on unpadded remote image URLs with unpredictable transparent canvas padding. Crop images to their non-transparent bounding box and place them in `assets/logos/` with a uniform `height="70"`.

## Architecture Rules

- **Synchronized Navigation:** Whenever adding, renaming, or removing H1, H2, or H3 sections, always update the Table of Contents at the top of `README.md` with corresponding anchor links.
- **GitHub Slugification:** Ensure Table of Contents anchors match GitHub's anchor generation algorithm: lowercase, spaces replaced by hyphens, punctuation and ampersands stripped (e.g., `Developer Tools & Ecosystem` → `#developer-tools--ecosystem`).
- **Logical Flow:** Maintain the document structure in sequence: Table of Contents → Plugins per Model → Developer Tools & Ecosystem → Standardized Agent Context Files → Starter Templates.
- **HTML Tag Integrity:** Never leave unclosed or mismatched `<table>`, `<tr>`, or `<td>` tags. Always validate tag counts before completing tasks.

## Testing

- **Programmatic Validation:** Run the tag balance and whitespace verification one-liners on `README.md` before finishing any modification turn.
- **Link Integrity:** Verify that every new tool, plugin, or framework link points to an active, official, or community-standard repository/documentation URL.
- **Visual Symmetry:** Check that 2-column tables in every category render symmetrically without layout shifts on GitHub.
- **Do Not Weaken Standards:** Never bypass whitespace audits or remove validation checks to make a pull request or task pass.

## Security & Boundaries

- **No Secrets or Credentials:** Never commit API keys, personal access tokens, session tokens, or private credentials.
- **Curated Quality over Quantity:** Never include "slop", meme repositories, scraper frameworks masquerading as plugins, or unverified packages.
- **Lightweight Assets:** Keep all media in `assets/logos/` optimized and under 100KB per image to prevent repository bloat.
- **No Destructive Overwrites:** Preserve established sections, links, and user customizations when performing programmatic conversions.

> **Note**: This file encodes project guidelines for AI coding agents working on the Agent Cookbook repository. Follow these conventions strictly when adding new tools, plugins, or sections.
