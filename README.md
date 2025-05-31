# Google ADK Sample

This is a sample project that demonstrates how to use the Google ADK to build an agent.

Here is what you'll learn:

1. How to use the [Google ADK](https://github.com/google/agent-dev-kit) to build an agent.
2. How to connect the agent to an MCP server.
3. How to connect the agent to custom tools.
4. How to monitor the agent using [Opik](https://github.com/comet-ml/opik) to gain full observability.

## Setup

Create a `.env` file inside the `/mcp_agent` directory with the following environment variables:

```bash
GOOGLE_API_KEY=[YOUR_GOOGLE_API_KEY]
GOOGLE_MAPS_PLATFORM_API_KEY=[YOUR_GOOGLE_MAPS_API_KEY]
OPIK_API_KEY=[YOUR_OPIK_API_KEY]
OPIK_WORKSPACE=[YOUR_OPIK_WORKSPACE]
OPIK_PROJECT_NAME=[YOUR_OPIK_PROJECT_NAME]
```

Check [Opik's GitHub repository](https://github.com/comet-ml/opik) for more information on how to get the API keys.

To install the dependencies, run the following command:

```bash
uv sync
```

## Running the project

```bash
uv run adk web
```