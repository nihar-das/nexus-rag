# Nexus RAG

This project is a research assistant intended to answer questions using evidence spread across multiple research papers. The first planned module is ingestion for curated, text-based PDF and HTML sources.

The repository is currently a scaffold. Ingestion and the command-line entry point are not implemented yet.

## Layout

- `src/ingestion/` loading, chunking, document records, and the ingestion workflow.
- `data/raw/` is for curated source files.
- `data/processed/` is for generated ingestion output and is ignored by Git.
- `requirements.txt` lists the initial PDF and HTML parsing dependencies.
