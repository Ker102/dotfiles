# dotfiles

Personal dotfiles repository for GitHub Codespaces with preconfigured VS Code settings, extensions, and MCP servers.

## Features

- **GitHub MCP Server**: Provides GitHub integration for Copilot Chat
- **Playwright MCP Server**: Enables browser automation capabilities for Copilot Chat
- **VS Code Extensions**: Pre-configured with GitHub Copilot and Copilot Chat

## Configuration

### MCP Servers (`.vscode/mcp.json`)

The repository includes preconfigured MCP (Model Context Protocol) servers:

- **GitHub MCP Server**: Uses the official GitHub MCP server Docker image to provide GitHub API access
- **Playwright MCP Server**: Provides browser automation capabilities using the Playwright MCP package

### VS Code Settings (`.vscode/settings.json`)

- MCP chat integration is enabled by default

### Extensions (`.vscode/extensions.json`)

Recommended extensions:
- GitHub Copilot
- GitHub Copilot Chat

## Usage

1. Link this repository as your dotfiles repository in GitHub Codespaces settings
2. When you create a new Codespace, these configurations will be automatically applied
3. The MCP servers will be available in VS Code Copilot Chat

## Requirements

- GitHub Codespaces
- GitHub Copilot and Copilot Chat extensions
- Docker (for GitHub MCP server)
- Node.js/npx (for Playwright MCP server)