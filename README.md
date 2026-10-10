# Tiger Cloud + Cursor MCP Integration

A hands-on setup of Tiger Cloud using the Tiger CLI and Model Context Protocol (MCP), with Cursor as the AI coding assistant.

## Overview

This project documents the setup of Tiger Cloud, authentication through the Tiger CLI, and configuration of the Tiger MCP server in Cursor.

The goal is to let an AI coding assistant interact with Tiger Cloud services through natural-language prompts.

## Tech Stack

- Tiger Cloud
- Tiger CLI
- Model Context Protocol (MCP)
- Cursor
- PostgreSQL

## Setup Process

### 1. Install Tiger CLI

Installed the Tiger CLI and verified the installation using:

```bash
tiger --help
```

### 2. Authenticate with Tiger Cloud

Authenticated using:

```bash
tiger auth login
```

Verified the authentication status using:

```bash
tiger auth status
```

### 3. Configure Tiger MCP in Cursor

Installed the MCP server configuration for Cursor using:

```bash
tiger mcp install
```

Selected Cursor from the available AI client options and restarted Cursor to load the configuration.

### 4. Create a Tiger Cloud Database Service

Created a PostgreSQL database service in Tiger Cloud and confirmed that the service reached the `Ready` state.

### 5. Verify the MCP Connection

The next verification step is to resolve an authentication error encountered during a service-list query in Cursor and confirm that the AI assistant can successfully access the database service through Tiger MCP.

## Screenshots

Screenshots documenting the Tiger Cloud service and Cursor MCP setup are included in the `screenshots/` directory.

## Outcome

Tiger CLI installation, Tiger Cloud authentication, and Cursor MCP configuration were completed. The database service is running in Tiger Cloud. Successful end-to-end MCP access remains to be verified.

## Resources

- [Tiger Cloud](https://www.tigerdata.com/cloud)
- [Tiger CLI and MCP documentation](https://docs.tigerdata.com/)


