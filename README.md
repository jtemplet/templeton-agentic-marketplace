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

# Business operations roles
/plugin install tabo@templeton-agentic-marketplace

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

### tabo

Templeton Agentic Business Ops. The shared product-management and marketing-management role
agents and their procedures, as skills namespaced under `tabo:` (for example `tabo:user-growth`).
A company supplies its own context file; the plugin holds no company policy. See
[jtemplet/templeton-agentic-business-ops](https://github.com/jtemplet/templeton-agentic-business-ops).

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
/plugin update tabo
/plugin update tapm
```

## License

MIT License
