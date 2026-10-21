# Model Registry

## Model 1: SentenceTransformer

- Model ID: sentence-transformers/all-MiniLM-L6-v2
- Library: sentence-transformers
- Library Version: 6.1.0
- Model Revision: Not pinned (default revision)
- Device: CPU
- Purpose: Environment verification and text embedding generation
- Input: Two English sentences
- Output Shape: (2, 384)
- Test Status: Passed
- Test Notebook: notebooks/00_environment_check.ipynb
- Dataset: Two manually written test sentences
- Result Location: Notebook Cell 7

## Notes
- The model successfully downloaded and generated embeddings.
- The model is used for environment testing only.
- It has not been selected as the final model for grading or Arabic text processing.
- OCR model evaluation is pending.