# RAG Learning

### Common Commands
```bash
uv init --no-package
uv add <packages>
uv sync
uv pip list

uv run <python-script>
```

### Keywords
- Indexing
  - Document Loading
    - TextLoader
    - PyPDFLoader
    - CSVLoader
    - JSONLoader
    - DirectoryLoader
    - WebBaseLoader
    - BSHtmlLoader
    - FirecrawlLoader
  - Chunking
    - Fixed-Size Chunking
    - Recursive Character Chunking
    - Semantic Chunking
    - Late Chunking
    - Document-Based (Structure-Aware) Chunking
    - Sliding Window Chunking
    - Code Splitter
    - MD Splitter
  - Embeding
  - Store
- Retrieval
- RAG Chain

### RAG Failures
- Bad Chunking
- Embeding Mismatch
- Retrieval Noise
- Context Overflow
- Hallucination