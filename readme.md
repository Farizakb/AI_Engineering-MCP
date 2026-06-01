# MCP Project

This repository contains a hands-on course for learning the Model Context Protocol (MCP) through server and client examples.

The lessons are organized as separate notebooks and project folders, with each folder focused on a specific MCP concept and implementation step.

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

The MCP course walks through:

- how to define and expose tools from an MCP server,
- how to make an MCP-compatible chatbot client,
- how to connect the chatbot to multiple MCP servers,
- how to add prompt templates and read-only resources,
- and how to create remote MCP servers with SSE transport.

Each lesson folder contains a Jupyter notebook plus a `mcp_project` subfolder with the relevant code and configuration files.
