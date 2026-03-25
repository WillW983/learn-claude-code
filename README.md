# learn-claude-code

A simple tool-using coding agent built with the Anthropic API.

## Features
- Interactive agent loop
- Bash tool execution
- Environment variable loading with `.env`
- Simple safety filter for dangerous shell commands

## Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install anthropic python-dotenv
