# MCP Flight Search Client

A client application for the MCP Flight Search service. This client interacts with the [MCP Flight Search](https://github.com/arjunprabhulal/mcp-flight-search) backend.

## Description

This client application provides a user-friendly interface to interact with the Model Context Protocol (MCP) flight search service. It allows users to search for flights between airports with specified dates.

## Files

- `mcp_flight_client.py`: Main client implementation for interacting with the MCP Flight Search service
- `prompt_templates.py`: Contains prompt templates for generating flight search queries

## Installation

Install the required packages for this client:

```
pip install -r requirements.txt
```

Required packages:
- llama-index
- llama-index-llms-ollama
- llama-index-tools-mcp
- langchain-community

## Usage

```
python mcp_flight_client.py
```

## Prerequisites

You need to have the [MCP Flight Search](https://github.com/arjunprabhulal/mcp-flight-search) service running.

### Installing the MCP Flight Search Package

```
# Install from PyPI
pip install mcp-flight-search
```

### Starting the MCP Server

You can start the MCP server using one of the following methods:

```
# Using the command-line entry point
mcp-flight-search --connection_type http

# Or using the Python module approach
python -m mcp_flight_search.server --connection_type http
```

## Author

For more articles on AI/ML and Generative AI, follow me on Medium: [Arjun Prabhulal](https://medium.com/@arjun-prabhulal)

## License

This project is licensed under the MIT License 