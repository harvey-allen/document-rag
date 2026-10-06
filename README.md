# Document-RAG Starter

This repository now contains only the reusable `pageindex` library code and the packaging files needed to install it.

## Kept

- `pageindex/` package
- `pyproject.toml`
- `requirements.txt`
- `LICENSE`

## Removed

- Demo notebooks in `cookbook/`
- Sample PDFs and generated outputs in `examples/`
- Test suite in `tests/`
- Marketing/docs-heavy static assets
- The old demo CLI in `run_pageindex.py`

## Next step

Build your own S3-backed ingestion and retrieval flow on top of the `pageindex` package, or replace it with your own RAG implementation if you want a completely blank slate.
