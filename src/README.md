# RAG from Scratch - Source Library

This directory contains the reusable library code for the RAG from Scratch project, currently maintained by Aryan Khokhar.

## Structure

- **embeddings/** - Text-to-vector conversion and caching
- **vector-stores/** - Vector storage and similarity search implementations
- **loaders/** - Document loading from various sources (PDF, text, etc.)
- **text-splitters/** - Strategies for chunking documents
- **retrievers/** - Document retrieval strategies
- **chains/** - RAG pipeline orchestration
- **prompts/** - Prompt template management
- **utils/** - Shared utilities and helpers

## Usage

```javascript
import {
  EmbeddingModel,
  InMemoryVectorStore,
  PDFLoader,
  RecursiveCharacterTextSplitter,
  VectorStoreRetriever,
  RAGChain
} from './src/index.js';

// Build your RAG pipeline...
```

## Development

Each module follows these principles:
1. Single responsibility
2. Abstract base classes where appropriate
3. Consistent interfaces
4. Comprehensive error handling
5. Full JSDoc documentation

## Testing

Tests are located in the /tests directory and mirror this structure.

## Maintainer

Aryan Khokhar is a Marketing Analyst with nearly 4 years of experience in data analysis, campaign performance, and technical reporting. With a strong background in SQL and data-driven decision-making, he maintains this repository to support structured and efficient RAG implementations.

Contact: khokhar.aryan13@gmail.com