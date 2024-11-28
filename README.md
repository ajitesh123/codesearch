# CodeSearch 🔍

A fast and efficient code search tool powered by Tantivy, allowing you to search through your codebase with lightning speed ⚡

## ✨ Features

- 🚀 Fast full-text search in your codebase
- 🎯 Language-aware code tokenization using Pygments
- 📁 Support for multiple file extensions
- 👀 Preview of search results
- ⚙️ Configurable search options
- 🔄 Automatic retry mechanism for robust indexing
- 🚦 Concurrent processing for better performance

## 🛠️ Installation

### Using pip
```bash
pip install codesearch
```

### Using uv (recommended)
1. Install uv first:
```bash
curl -fsSL https://get.uvm.dev | bash
# or
brew install uv
```

2. Create and activate a virtual environment:
```bash
uv venv
source .venv/bin/activate  # On Unix
# or
.venv\Scripts\activate     # On Windows
```

3. Install the package:
```bash
uv pip install codesearch
```

## 🚀 Usage

Index your code:
```bash
codesearch --index /path/to/your/code --extensions py,js,ts
```

Search in your indexed code:
```bash
codesearch --search "your search query"
```

## 📋 Requirements

- Python 3.11+
- Tantivy
- Loguru

## 📄 License

MIT License
