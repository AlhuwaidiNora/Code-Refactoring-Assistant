# Code Refactoring Assistant

A Python-based tool that analyzes codebases and suggests improvements for better code quality. This tool helps identify potential issues and provides refactoring suggestions.

## Features

- Analyzes Python code for common issues
- Checks function length and complexity
- Verifies naming conventions
- Generates detailed reports in Markdown format
- Recursive directory scanning
- Multiple severity levels for issues

## Usage

```python
from main import CodeRefactor

refactor = CodeRefactor()
results = refactor.refactor_directory("path/to/your/code")
report = refactor.generate_report(results)
