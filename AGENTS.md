# Autter documentation instructions

## About this project

- This is the Mintlify documentation site for Autter.
- Autter is an AI code review platform and an open source CLI for tracking AI-authored code.
- Pages are MDX files with YAML frontmatter.
- Site configuration and navigation live in `docs.json`.
- Run `mint dev` to preview locally.
- Run `mint broken-links` and `mint validate` before publishing.
- Use the installed Mintlify skill in `.agents/skills/mintlify` when changing navigation, components, or site configuration.

## Sources of truth

- Use [autter.dev](https://autter.dev) for product positioning and visual identity.
- Use [Autter-dev/autter-cli](https://github.com/Autter-dev/autter-cli) for CLI commands, behavior, configuration, and data handling.
- Use the CLI repository's `data-privacy.md` for local, cloud, team, and enterprise storage claims.
- Do not invent commands, pricing, retention periods, security controls, or platform behavior.
- Add an MDX TODO comment when a product detail still needs confirmation.

## Terminology

- Use “Autter platform” for the hosted product.
- Use “Autter CLI” or `autter` for the open source command-line tool.
- Use “connected mode” and “local-only mode” for CLI operating modes.
- Use “AI authorship” and “line-level attribution,” not “AI detection.”
- Use “coding agent” for tools such as Codex, Claude Code, Cursor, and GitHub Copilot.
- Use “organization,” “repository,” “pull request,” and “merge request” where appropriate.

## Style preferences

- Use active voice and second person (“you”).
- Keep sentences concise. Give each sentence one main idea.
- Use sentence case for headings.
- Bold UI labels: Click **Settings**.
- Use code formatting for file names, commands, paths, configuration keys, and code references.
- Lead with what the reader can accomplish, then explain how it works.
- Prefer concrete examples over marketing claims.
- Use Mintlify components only when they improve scanning or comprehension.
- Give every image descriptive alt text.
- Use root-relative links without file extensions for internal pages.

## Brand

- Use the official Autter wordmarks from `autter.dev`.
- Use the navy wordmark in light mode and the white wordmark in dark mode.
- Core colors are navy `#1E2D4A`, mint `#2EFFD1`, accessible teal `#00A88A`, ink `#0D1219`, and warm white `#F1ECE0`.
- Use Quattrocento for headings, Quattrocento Sans for body copy, and a monospace font for CLI output.
- Keep layouts editorial, restrained, and technical. Avoid gradients and decorative effects.

## Content boundaries

- Document public product and open source behavior only.
- Never expose internal endpoints, credentials, signed database URLs, or implementation secrets.
- Explain what data is local, what enters Git, what uploads in connected mode, and how to opt out.
- State that source-code diffs used for platform analysis are processed but not stored only where supported by the current privacy source.
- Do not promise a retention period unless Autter publishes one.
