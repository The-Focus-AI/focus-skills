# Focus Skills

A collection of Claude Code skills for Focus.AI development workflows.

## Installation

Install this plugin in Claude Code by adding it to your `.claude/plugins` directory or installing from the marketplace.

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

**Reference:** [distill-backend-service.md](references/distill-backend-service.md)

### 2. Focus Account Integration

Integrate applications with Focus API for authentication, wallet/credits, and job management.

**Use when:**
- Integrating a new app with Focus authentication
- Implementing device-code flow for CLI tools
- Managing user credits and wallet operations
- Creating, completing, or failing jobs with cost tracking
- Setting up shared sign-in via account.thefocus.ai

**Reference:** [focus-account-integration.md](references/focus-account-integration.md)

### 3. Twitter OAuth CLI Tool

Build CLI tools that authenticate with Twitter/X OAuth 2.0 using PKCE flow.

**Use when:**
- Creating CLI tools that need Twitter API access
- Building automation scripts that post tweets
- Implementing OAuth 2.0 PKCE for terminal applications
- Storing Twitter tokens for offline/automated use
- Building tweet schedulers or social media tools

## Usage

In Claude Code, these skills will be automatically suggested based on your context and needs. You can also invoke them explicitly by asking Claude to use a specific skill.

## Development

To modify or extend these skills, edit the markdown files in the `skills/` directory. Each skill is defined by:

- **Frontmatter**: Name, description, and trigger conditions
- **Content**: Step-by-step guidance, code examples, and best practices
- **References**: Optional detailed reference documentation in `references/`

## License

Copyright The Focus AI. All rights reserved.
