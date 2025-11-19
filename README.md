# Small projects with LLM and websites

## *llm_model_ai_ml_lab*
- A simple academic project that aims to sugest recipes based in users queries.
- This algorithm uses:

  - The dataset used was embedded from a *csv* using *sentence transformer* (with a model locally installed). The model is saved locally in a *pickle* format.
    - The use of an embedding model was made by the fact that context is important in a user query.

  - The user query is embedded with the same model used to embed the dataset.

  - Using the *cosine similarity* the model compares the query with the recipes and it sorts the 100 recipes that are most similar to the user query.

## *summarization_openai*
- Made when I was learning about LLM. I am very fan of *Souls* series (Dark Souls I, II and III, Sekiro and Elden Ring).
- It's a *webpage summarization algorithm* that retrieves information from [Elden Ring fandom wiki](https://eldenring.wiki.fextralife.com/) based in what the users type.
  - It's a simple python code. 
