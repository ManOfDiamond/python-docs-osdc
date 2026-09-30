# Python Docs for OSDC

Learning material for OSDC's full-stack workshop.

The guide builds Python fundamentals first and then connects them to backend development with FastAPI and a frontend-friendly API workflow.

## Learning Path

### Python Foundations

1. [Introduction](docs/Introduction.md)
2. [Data Types](docs/data_types.md)
3. [Taking Input](docs/input.md)
4. [If-Else and Menu-Driven Programs](docs/if_else_menu_driven.md)
5. [Loops](docs/Loops.md)
6. [User-Defined Functions](docs/functions.md)
7. [Object-Oriented Programming](docs/oops.md)
8. [File Handling](docs/file_handling.md)

### Backend Development

9. [FastAPI](docs/fastapi.md)
10. [Demo API Walkthrough](docs/demo.md)
11. [Frontend Integration](docs/frontend_integration.md)

The [Demo API Walkthrough](docs/demo.md) uses the `demo-api` project to show how a Python client communicates with a FastAPI backend through HTTP requests and JSON responses.

The [Frontend Integration](docs/frontend_integration.md) module connects FastAPI to an HTML, CSS, and JavaScript frontend using CORS, `fetch()`, JSON, and DOM updates.

## Repository Structure

```text
python-docs-osdc/
|-- README.md
|-- docs/
|   |-- Introduction.md
|   |-- data_types.md
|   |-- input.md
|   |-- if_else_menu_driven.md
|   |-- Loops.md
|   |-- functions.md
|   |-- oops.md
|   |-- file_handling.md
|   |-- fastapi.md
|   |-- demo.md
|   |-- frontend_integration.md
```

Each topic is written as a standalone Markdown module with explanations and runnable examples.