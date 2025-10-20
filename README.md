# Banyan AI - Claude Code Plugin Marketplace

Official Claude Code plugin marketplace for Banyan AI development tools and specialized agents.

## 🚀 Installation

Add this marketplace to your Claude Code:

```bash
/plugin marketplace add banyanai/claude-plugins
```

Then browse and install plugins from the Claude Code plugin menu.

## 📦 Available Plugins

### greenfield-agents

**14 specialized agents for Domain-Driven microservices development**

A comprehensive collection of agents for planning, building, testing, and documenting microservices using Domain-Driven Design principles.

#### Quick Install

```bash
/plugin install greenfield-agents
```

#### Agents Included

**Planning & Architecture (3 agents)**
- `planner` - Requirements analysis, roadmap creation, and test planning
- `service-planner` - Microservice architecture design and DDD boundaries
- `service-builder` - TypeScript microservice implementation with message bus

**Domain Modeling (2 agents)**
- `event-storming-analyst` - Event storming facilitation and domain modeling
- `gherkin-business-logic-analyzer` - BDD specifications and acceptance criteria

**Documentation (1 agent)**
- `c4-architecture-documenter` - C4 architecture diagrams (Context, Container, Component, Code)

**Testing & Quality (2 agents)**
- `test-auditor` - Test coverage and quality analysis
- `bug-test-writer` - Regression test creation and bug reproduction

**Debugging (3 agents)**
- `trace-investigator` - Stack trace and error analysis
- `debug-coordinator` - Multi-agent debugging workflows
- `bug-fixer` - Targeted bug fixes with test verification

**Code Quality (2 agents)**
- `reviewer` - Requirements alignment and code review
- `code-auditor` - Code quality patterns and best practices

**Security (1 agent)**
- `security-auditor` - Supply chain security audits (run before npm install/docker build)

#### Usage Examples

```
Use the planner agent to analyze requirements.md and create an implementation roadmap
```

```
Have the security-auditor scan this repository before I run npm install
```

```
Use the event-storming-analyst to model our order processing domain
```

```
Have the service-planner design the microservice architecture for our payment system
```

```
Use the bug-fixer to implement a fix for the authentication timeout issue
```

#### Learn More

- **Repository**: https://github.com/banyanai/greenfield-agents
- **Documentation**: https://github.com/banyanai/greenfield-agents/blob/main/PLUGIN.md
- **License**: MIT

---

## 🤝 Contributing

Have a plugin you'd like to add to this marketplace?

1. Fork this repository
2. Add your plugin to `marketplace.json`
3. Submit a pull request

## 📚 Resources

- [Claude Code Plugin Documentation](https://docs.claude.com/en/docs/claude-code/plugins)
- [Plugin Marketplace Guide](https://docs.claude.com/en/docs/claude-code/plugin-marketplaces)
- [Banyan AI GitHub](https://github.com/banyanai)

## 📝 License

MIT - See individual plugins for their specific licenses.

---

**Built by Banyan AI for Domain-Driven Development**
