# Templeton Agentic Marketplace

Personal Claude Code marketplace providing access to personal skills and custom agent
skills.

## Installation

Register the marketplace:

```bash
/plugin marketplace add jtemplet/templeton-agentic-marketplace
```

Install plugins:

```bash
# Custom agent skills
/plugin install tadw@templeton-agentic-marketplace

# Marketing operations role
/plugin install tamo@templeton-agentic-marketplace

# Product management
/plugin install tapm@templeton-agentic-marketplace
```

## Plugins

### tadw

Templeton Agentic Dev Workbench. Custom agents, skills, and commands for personal use, all
namespaced under `tadw:` (for example `tadw:fresh-eyes-cr`). See
[jtemplet/templeton-agentic-dev-workbench](https://github.com/jtemplet/templeton-agentic-dev-workbench).

Installed under the old name `templeton-agentic-dev-workbench`? That name was retired in the
plugin's 2.0.0. Uninstall it and install `tadw`; the two cannot coexist.

### tamo

Templeton Agentic Marketing Ops. The shared Marketing role agent and its runbooks, as skills
namespaced under `tamo:` (for example `tamo:user-growth`). A company supplies its own context file;
the plugin holds no company policy. See
[jtemplet/templeton-agentic-marketing-ops](https://github.com/jtemplet/templeton-agentic-marketing-ops).

Installed under the old name `tabo`? Uninstall it and install `tamo`.

### tapm

Templeton Agentic Product Management. Product strategy, research, roadmap, brief, and A/B test
design skills, the product-manager, product-analyst, and product-cartographer agents, and
product-surface documentation, all namespaced under `tapm:` (for example `tapm:product-brief`).
They moved here from `tadw`, whose changelog marks the move as breaking. Some of them name `tadw`
components, and the `tadw` command `/product-surface-docs` runs `tapm:product-surface-docs`, so
install both. See
[jtemplet/templeton-agentic-product-management](https://github.com/jtemplet/templeton-agentic-product-management).

## Updating

Update plugins:

```bash
/plugin update tadw
/plugin update tamo
/plugin update tapm
```

## License

MIT License
