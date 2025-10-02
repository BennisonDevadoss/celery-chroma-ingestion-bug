# celery-chroma-ingestion-bug
Minimal reproducible example showing an issue where document ingestion into ChromaDB (with Google Generative AI embeddings) works when called directly in FastAPI but fails silently when executed inside a Celery task.
