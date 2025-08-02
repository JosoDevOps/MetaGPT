# Contributing to MetaGPT

Thank you for your interest in improving MetaGPT! This guide will help you get set up for development, run code quality checks, and execute the test suite.

## Setup

1. Fork the repository and clone your fork:
   ```bash
   git clone https://github.com/<your-username>/MetaGPT.git
   cd MetaGPT
   ```
2. Create and activate a Python 3.9+ (but <3.12) virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -e .
   ```

## Pre-commit

This project uses [pre-commit](https://pre-commit.com/) for linting and formatting.

1. Install the pre-commit hooks:
   ```bash
   pre-commit install
   ```
2. Run pre-commit on changed files before committing:
   ```bash
   pre-commit run --files <file1> <file2>
   ```
   To check the whole project, use `pre-commit run --all-files`.

## Tests

Run the test suite with [pytest](https://pytest.org/):

```bash
pytest
```

Please ensure all tests pass before submitting a pull request.

---
Happy hacking!
