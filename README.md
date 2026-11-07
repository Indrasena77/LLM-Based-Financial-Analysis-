# LLM-Based Financial Analysis of Poland

## Project Overview
This project analyses Poland's 2023 IMF Article IV Consultation report using large language models and natural language processing. It extracts financial indicators, summarises economic findings, identifies risks and presents the results in a four-panel dashboard.

## Models and Tools
- **Qwen3-14B:** Summarisation, financial extraction and RAG responses
- **Qwen3-8B:** Output evaluation
- **BGE-base-en-v1.5:** Semantic embeddings
- **FAISS:** Vector similarity search
- **Python and Google Colab:** Data processing and visualisation

## Key Results
- 87 PDF pages processed
- 182 text chunks generated
- 7 section summaries
- 6 financial indicators extracted
- 7 financial themes identified
- 4 RAG questions evaluated
- 4-panel financial dashboard

## How to Run
1. Open the notebook in Google Colab.
2. Select an NVIDIA A100 GPU runtime.
3. Run the cells sequentially and upload the Poland IMF 2023 PDF when prompted.
4. Find the generated JSON, CSV and dashboard files in `/content/poland_llm_outputs/`.

No API keys are required.

## Reference
International Monetary Fund (2023). *Republic of Poland: 2023 Article IV Consultation*. IMF Country Report No. 23/189.
