# IMF Report Analysis — Latvia

Student ID: 24143552

This notebook analyses Latvia’s 2026 IMF Article IV report using Python, Groq language models, local sentence embeddings and FAISS.

## Running the notebook

1. Open the notebook in Google Colab.
2. Upload the source PDF as latvia_country_2026.pdf.
3. Add your Groq API key to Colab Secrets as GROQ_API.
4. Run the cells in order. API access and sufficient quota are required.

## Outputs

- Section summaries and executive findings
- Economic indicators with source references and null fallbacks
- Thematic counts and qualitative findings
- Retrieval-grounded answers and evaluation results
- A four-panel dashboard saved at 300 dpi

Results are saved in latvia_project/results. Cached responses reduce repeated API requests. Flagged claims require source verification; judge scores are not verified accuracy measures.

## Source and licence

Source: IMF Country Report No. 26/248, Latvia, 2026.
Code: MIT License; see LICENSE. The IMF report retains its original rights.
