# Granola

Your meetings in your workflow.

Granola gives your agent access to what your team discussed, decided, and committed to in meetings. Instead of context-switching to check your notes or asking teammates to repeat themselves, you get answers where you're already working.

## Setup

In Google Antigravity, open **Customizations → Plugins** and install Granola. The first time you use a Granola tool, you'll be prompted to sign in via your browser. You need a [Granola](https://granola.ai) account with meeting data.

## Granola MCP

The plugin connects to Granola's MCP server at `https://mcp.granola.ai/mcp`. The plugin only installs that connection: the server provides the tools and the instructions for using them, so the plugin can't fall out of date as the server changes.

## Releasing

Once the plugin is published, bump `version` in `.antigravity-plugin/plugin.json` whenever you change the manifest, `mcp_config.json` or `assets/`. Installed clients only update when the version changes.

## License

Apache-2.0. See [LICENSE](LICENSE).

## Feedback

Reach out at hello@granola.ai.
