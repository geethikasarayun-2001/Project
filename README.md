# Self-Reflective Large Language Models for Hallucination Reduction

This repository contains a research notebook that evaluates different approaches for reducing hallucinations in Large Language Models (LLMs). The study compares four methods under the same experimental settings using benchmark datasets.

## Methods Evaluated

- Standard Generation
- Retrieval-Augmented Generation (RAG)
- Multi-Agent Verification
- Self-Reflection

## Datasets

- TruthfulQA
- HaluEval

## Model

- Microsoft Phi-3-mini-4k-instruct (4-bit quantized)

## Evaluation Metrics

- TruthfulQA Accuracy
- Hallucination Rate
- Precision
- Recall
- F1 Score
- Average Latency
- Consistency Score

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- FAISS
- Sentence Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Running the Notebook

1. Install the required Python packages.
2. Restart the runtime after installation.
3. Execute the notebook cells sequentially.
4. The notebook will evaluate all four methods, generate visualisations, and save the results as CSV files.

## Output Files

- `final_comparison.csv`
- `baseline_results.csv`
- `rag_results.csv`
- `self_reflection_results.csv`
- `error_analysis.csv`

## Author

Geethika Sarayu Neelam  
MSc in Artificial Intelligence  
National College of Ireland
