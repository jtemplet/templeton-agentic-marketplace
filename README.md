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

## Updating

Update plugins:

```bash
/plugin update tadw
/plugin update tabo
```

## License

MIT License
