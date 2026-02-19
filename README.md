# Focus Skills

A collection of Claude Code skills for Focus.AI development workflows.

## Installation

### Via Focus Marketplace (Recommended)

```bash
# Add the Focus marketplace (if not already added)
/plugin marketplace add The-Focus-AI/claude-marketplace

# Install the plugin
/plugin install focus-skills@focus-marketplace
```

Then restart Claude Code.

### Manual Installation

Install this plugin in Claude Code by adding it to your `.claude/plugins` directory.

## Available Skills

### 1. Distill Backend Service

Build Distill microservices that collect, process, and summarize content from platforms (Twitter/X, Email, GitHub, YouTube).

**Use when:**
- Creating a new Distill service for a content platform
- Implementing watch/unwatch user lifecycle management
- Building AI-powered content summaries and feeds
- Adding standard API endpoints for service discovery
- Implementing JWT-based authentication with Clerk
- Setting up sync scheduling and rate limiting

**Skill path:** `skills/distill-backend-service/SKILL.md`
**Reference:** `skills/distill-backend-service/references/REFERENCE.md`

### 2. Focus Account Integration

Integrate applications with Focus API for authentication, wallet/credits, and job management.

**Use when:**
- Integrating a new app with Focus authentication
- Implementing device-code flow for CLI tools
- Managing user credits and wallet operations
- Creating, completing, or failing jobs with cost tracking
- Setting up shared sign-in via account.thefocus.ai

**Skill path:** `skills/focus-account-integration/SKILL.md`
**Reference:** `skills/focus-account-integration/references/REFERENCE.md`

### 3. Twitter OAuth CLI Tool

Build CLI tools that authenticate with Twitter/X OAuth 2.0 using PKCE flow.

**Use when:**
- Creating CLI tools that need Twitter API access
- Building automation scripts that post tweets
- Implementing OAuth 2.0 PKCE for terminal applications
- Storing Twitter tokens for offline/automated use
- Building tweet schedulers or social media tools

**Skill path:** `skills/twitter-oauth-cli/SKILL.md`

## Usage

In Claude Code, these skills will be automatically suggested based on your context and needs. You can also invoke them explicitly by asking Claude to use a specific skill.

## Skill Structure

Each skill follows the universal [Agent Skills](https://agentskills.io) format:

```
skills/
  skill-name/
    SKILL.md              # Core instructions with YAML frontmatter (required)
    references/           # Detailed reference documentation (optional)
    scripts/              # Executable automation scripts (optional)
    assets/               # Templates and resources (optional)
```

This format is portable across Claude Code, OpenAI Codex, VS Code Copilot, Cursor, Gemini CLI, and other platforms that support the Agent Skills standard.

## License

Copyright The Focus AI. All rights reserved.
