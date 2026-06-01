# MCP Project

This repository is a practical MCP project that walks through real implementation patterns for the Model Context Protocol (MCP).

The project is organized into self-contained modules, each containing a notebook and working code for a specific MCP capability.

## Project Structure

- `chatbot_tool_use/`
  - Example notebook and paper data for a chatbot tool workflow.
- `creating_mcp_server/`
  - Notebook and server files showing how to build a local MCP server using `FastMCP`.
- `creating_mcp_client/`
  - Notebook and project files for connecting a chatbot to an MCP server via an MCP client.
- `connecting_the_mcp_chatbot_to_reference_servers/`
  - Notebook and project files for integrating the chatbot with official MCP reference servers.
- `adding_prompt_and_resource_features/`
  - Notebook and project files demonstrating prompt templates and resource support on the MCP server.
- `creating_and_deploying_remote_servers/`
  - Notebook and project files explaining remote MCP servers, SSE transport, and deployment notes.

## Description

This is a practical MCP project focused on implementing and testing real MCP workflows.

It includes hands-on modules that demonstrate:

- defining and exposing tools from an MCP server,
- building an MCP-compatible chatbot client,
- connecting the chatbot to multiple MCP servers,
- adding prompt templates and read-only resource endpoints,
- and deploying remote MCP servers using SSE transport.

Each project folder contains a Jupyter notebook plus a `mcp_project` subfolder with working code and configuration files.
