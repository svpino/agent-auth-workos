# Sample Agent with Authentication

This is a sample project that demonstrates how to use the Google ADK to build an agent.

## Setup

Create a `.env` file inside the `/mcp_agent` directory with the following environment variables:

```bash
OAUTH_CLIENT_ID=[YOUR_OAUTH_CLIENT_ID]
OAUTH_CLIENT_SECRET=[YOUR_OAUTH_CLIENT_SECRET]
```

To install the dependencies, run the following command:

```bash
uv sync
```

## Running the project

```bash
uv run adk web
```