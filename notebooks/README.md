# Notebooks

Course notebooks, grouped by topic. File names follow the lecture numbering of the course.

## Topics

- Environment setup and the OpenAI API: `Environment Setup`, `The OpenAI API`, `Chat OpenAI`
- LangChain model I/O and output parsers: `Model IO v1` to `v5`, `Model v5`, `Output Parsers`
- LangChain Expression Language (LCEL): `08 LCEL 01` to `10`
- Retrieval-augmented generation (RAG): `09 RAG 06` to `18`
- LangGraph: `03-02 First Graph`, `03-03` and `03-04 Conditional Edges`, `04-01` to `04-06` on reducers, `MessagesState`, removing, trimming and summarizing messages
- Transformers for NLP: `QA Models with BERT`, `Text classification with XLNET`

## Running the notebooks

1. Create a virtual environment and install Jupyter plus the packages imported at the top of each notebook.
2. Put API keys in a local `.env` file. It is listed in `.gitignore` and is never committed.
3. Start Jupyter from the repository root so relative paths such as `datasets/` resolve.
