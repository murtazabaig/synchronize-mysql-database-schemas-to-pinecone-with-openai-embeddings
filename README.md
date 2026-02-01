# Synchronize MySQL database schemas to Pinecone with OpenAI embeddings

Advanced n8n automation for Synchronize MySQL database schemas to Pinecone with OpenAI embeddings.

## Overview
- Category: Document Extraction, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Idempotently sync MySQL table schemas to Pineconeone schema per vector, no duplicates. Auto-detects changes via hashes and re-indexes only when needed.

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## License
MIT License. See `LICENSE`.
