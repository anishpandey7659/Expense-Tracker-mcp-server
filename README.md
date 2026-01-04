# Expense Tracker MCP

## Expense Tracker MCP is a Python-based application to help users track and manage their daily expenses efficiently. It uses FastMCP for running the server and aiosqlite for database management.

## Features

* Track daily expenses easily.

* Store expense data locally using SQLite.

* Fast and lightweight using FastMCP.

* Easy to run on Windows with Python 3.10.

## rerequisites

* Before running the project, make sure you have:

* Python 3.10 installed

* pip for installing dependencies

* Git (if cloning the repo)

## Installation

1. Clone the repository:
   ```python
   git clone https://github.com/your-username/Expense-Tracker-mcp-server.git
   cd Expense-Tracker-mcp-server

2. Create a virtual environment (recommended):
   ```python
   python -m venv .venv

3.Activate the virtual environment:
 * Windows Command Prompt:
    ```python
    venv\Scripts\activate
 * Windows PowerShell:
    ```python
    .venv\Scripts\Activate.ps1
    
4. Install dependencies:
     ```python
     pip install fastmcp aiosqlite

## Running the Application

Run the Expense Tracker MCP server using the following command:
Here is the configuration for running ExpenseTracker:

```json
{
  "mcpServers": {
      "ExpenseTracker": {
        "command": "uv-path", => In command ,If windows search where uv for path, If macbook search which uv
        "args": [
          "run",
          "--with",
          "fastmcp",
          "--with",
          "aiosqlite",
          "fastmcp",
          "run",
          "file-path" =>add the path of main.py file
        ],
        "env": {},
        "transport": "stdio"
      }
    }
}
    
