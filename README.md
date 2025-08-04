# Log-Classification-Pipeline-Using-Regex-Sentence-Transformers-and-LLMs


Python | FastAPI | Regex | Sentence Transformers | Logistic Regression | LLMs

Developed a scalable log classification pipeline that integrates rule-based, machine learning, and large language model (LLM) techniques to handle diverse log message patterns with varying complexity and labeling quality.

Designed a modular system combining:

Regex-based classification for highly structured and predictable log formats.

Sentence Transformer embeddings with Logistic Regression for supervised classification of semi-structured logs.

LLM-based classification to manage complex, low-label scenarios by leveraging generative language understanding.

Built a RESTful API using FastAPI for real-time log file uploads and processing.

Enabled users to submit CSV files containing log entries (source, log_message) and receive classified output with target_label.

Implemented interactive API documentation with Swagger (/docs) and ReDoc (/redoc) for easy testing and integration.

Organized the project with a clean folder structure supporting training, models, and reusable resource files.

Outcome:
Delivered a hybrid, extensible log classification solution suitable for production environments, supporting intelligent log analysis even in cases of low-quality or missing labels.
