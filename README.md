# Llama Stack Server

A server implementation for the Llama Stack framework.

## Overview

This server provides a backend for Llama Stack applications.

## Prerequisites

- Python 3.10 or higher
- [uv](https://github.com/astral-sh/uv) package manager
- Git

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/slaterlucas/llama-stack-server.git
   cd llama-stack-server
   ```

2. Set up the Python environment:
   ```bash
   # If using Homebrew Python on macOS
   export UV_PYTHON=/opt/homebrew/bin/python3.10  # Adjust path as needed
   
   # Install dependencies
   pip install -r requirements.txt
   ```

## Building the Stack

Build the Llama Stack environment with the Together AI template:

```bash
uv run --with llama-stack llama stack build --template together --image-type venv
```

## Running the Server

Start the server with:

```bash
python server.py
```



