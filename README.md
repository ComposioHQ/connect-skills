# Composio Connect

Connect and execute actions over 1000+ apps using Composio.

## Summary

Use this when authenticating, fetching data, or making changes in external applications (Slack, GitHub, Gmail, etc.).

**Quick start:**
1. Install: `curl -fsSL https://composio.dev/install | bash`
2. Login: `composio login`
3. Search tools: `composio tools search "your use case"`
4. Execute: `composio tools execute "TOOL_SLUG" -d '{ ... }'`
5. Link accounts if needed: `composio connected-accounts link "app_name"`

**Best practices:** Pipe JSON to `jq`, limit output, run independent actions in parallel, avoid unnecessary cache files.

For the full guide with prerequisites, step-by-step instructions, and best practices, see [skills/composio/SKILL.md](skills/composio/SKILL.md).
