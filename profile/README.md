## Xano: one platform to build, run and govern AI-built software

**Enterprise grade from day one.** Build with AI or in XanoScript. Govern, test, deploy, and observe everything AI ships.

[Website](https://www.xano.com/) · [Docs](https://docs.xano.com/) · [Community](https://community.xano.com/) · [Blog](https://www.xano.com/blog/) · [YouTube](https://www.youtube.com/@XanoHQ) · [X](https://x.com/xanohq)

---

### What is Xano?

Xano is the backend platform where your team builds with AI, in XanoScript, or in the Xano editor, then tests, deploys, and observes it all in one place.

- **One platform.** Database, APIs, environments, releases, logs and a picture of what got built, as one system. Everything in one place, with nothing to assemble.
- **One set of rules for the whole team.** Rules set once apply to every person and every AI agent, with a path to production that Xano runs.
- **One shared picture of what got built,** drawn from the software that's actually running. A business stakeholder can read how the system works without reading code.
- **Standard foundations.** PostgreSQL and Kubernetes, in our cloud or yours.

---

### Build with your tools

Your agent, your editor and your terminal all work against the same backend and the same rules. Our public developer tools live in [xano-inc](https://github.com/xano-inc).

| Repo | What it does | Install |
| --- | --- | --- |
| [**xano-developer-mcp**](https://github.com/xano-inc/xano-developer-mcp) | MCP server that gives AI coding agents XanoScript docs, code validation, Metadata API and CLI references, and workflow guides | `claude mcp add xano -- npx -y @xano/developer-mcp` |
| [**cli**](https://github.com/xano-inc/cli) | Work with Xano from your terminal: pull and push workspaces, branches, functions, releases, tests, tenants and static hosts | `npm install -g @xano/cli` |
| [**js-sdk**](https://github.com/xano-inc/js-sdk) | TypeScript SDK for calling your Xano APIs from the browser or Node.js | `npm install @xano/js-sdk` |
| [**static_template**](https://github.com/xano-inc/static_template) | Static React starter frontend wired to your Xano auth and APIs, ready for Xano static hosting | [Use the template](https://github.com/xano-inc/static_template) |
| [**n8n-nodes-xano**](https://github.com/xano-inc/n8n-nodes-xano) | n8n community node for reading and writing Xano data in your workflows | [n8n community nodes](https://docs.n8n.io/integrations/community-nodes/installation/) |
| [**standalone**](https://github.com/xano-labs/standalone) | Self-hosted editions: Enterprise in your own Kubernetes cluster, or a single Docker image for a proof of concept on your own infrastructure | [Self-hosted docs](https://go.xano.co/enterprise-self-hosted) |

---

### Get started

1. [Create a free account](https://app.xano.com/signup). Building is free.
2. Connect your AI agent with the [Developer MCP](https://github.com/xano-inc/xano-developer-mcp), or install the [CLI](https://github.com/xano-inc/cli) and run `xano auth`.
3. Read the [docs](https://docs.xano.com/) or ask the [community](https://community.xano.com/).
