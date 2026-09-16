# SocialHive Social Publishing — Claude Plugin

Official Claude Code plugin and Model Context Protocol (MCP) connector for [SocialHive](https://socialhive.pro).

Manage your complete social media workflow directly within Claude Code and Claude Desktop. Draft, schedule, automate, and publish content across **LinkedIn, X (Twitter), YouTube, Instagram, Facebook, TikTok, and Pinterest**, while analyzing performance and generating on-brand content.

---

## Features

- **Multi-Platform Publishing**: Create drafts, schedule posts, or publish immediately across 7+ networks.
- **Channel Management**: Inspect connected social accounts, follower metrics, and posting permissions.
- **Analytics & Reporting**: Query engagement statistics, impressions, clicks, and top-performing posts.
- **AI Content Studio**: Generate platform-tailored copy, hashtags, and social imagery aligned with your brand voice.
- **Workflow Studio Integration**: Propose automated social campaigns and recurring posting schedules.

---

## Installation

### In Claude Code

Add the plugin to Claude Code:

```bash
claude plugin install socialhive-social-publishing
```

Or run directly with the plugin:

```bash
claude --plugin-dir ./socialhive-claude-plugin
```

### In Claude Desktop (`claude_desktop_config.json`)

Add the following to your Claude Desktop configuration file:

```json
{
  "mcpServers": {
    "socialhive": {
      "type": "http",
      "url": "https://platform.socialhive.pro/api/mcp"
    }
  }
}
```

---

## Authentication

1. Sign in to your [SocialHive Account](https://platform.socialhive.pro).
2. Go to **Settings > API Keys** to generate an API key (`shp_...`).
3. Set your key when prompted by Claude Code or via environment variable.

---

## Links

- **Website**: [https://socialhive.pro](https://socialhive.pro)
- **Web App**: [https://platform.socialhive.pro](https://platform.socialhive.pro)
- **API Documentation**: [https://platform.socialhive.pro/settings/api](https://platform.socialhive.pro/settings/api)
- **Support**: [support@socialhive.pro](mailto:support@socialhive.pro)

---

## License

MIT © [SocialHive](https://socialhive.pro)
