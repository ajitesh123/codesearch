# CodeSearch

A fast and efficient code search tool powered by Tantivy, allowing you to search through your codebase with ease.

## Installation

```bash
pip install codesearch
```

## Usage

Index your code:
```bash
codesearch --index /path/to/your/code --extensions py,js,ts
```

Search in your indexed code:
```bash
codesearch --search "your search query"
```

## Features

- Fast full-text search in your codebase
- Support for multiple file extensions
- Preview of search results
- Configurable search options

## Requirements

- Python 3.7+
- Tantivy
- Loguru

## License

MIT License 