# Akasha Documentation

Documentation for [Akasha](https://github.com/Akasha-os/akasha) — the self-hosted second brain.

Built with [Astro Starlight](https://starlight.astro.build).

> Documentation is being written alongside the platform. Check back as development progresses.

---

## Structure

```
src/content/docs/
  getting-started/
    installation.md
    setup-wizard.md
    first-document.md
    configuration.md
  connectors/
    overview.md
    mail.md
    slack.md
    calendar.md
    obsidian.md
    notion.md
    watch.md
    location.md
  agents/
    overview.md
    built-in-agents.md
  rituals/
    overview.md
    triggers.md
    steps.md
    examples.md
  mcp/
    overview.md
    claude-desktop.md
  developer/
    architecture.md
    connector-authoring.md
    schema-versioning.md
    contributing.md
```

---

## Contributing to docs

Documentation improvements are always welcome. To run locally:

```bash
git clone https://github.com/Akasha-os/docs
cd docs
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

---

## Links

- [Akasha](https://github.com/Akasha-os/akasha)
- [Connector SDK](https://github.com/Akasha-os/connector-sdk)
- [MCP Server](https://github.com/Akasha-os/mcp)