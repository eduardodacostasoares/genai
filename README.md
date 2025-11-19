# Small projects with LLM and websites

## *llm_model_ai_ml_lab*
- A simple academic project that aims to sugest recipes based in users queries.
- This algorithm uses:

  - The dataset used was embedded from a *csv* using *sentence transformer* (with a model locally installed). The model is saved locally in a *pickle* format.
    - The use of an embedding model was made by the fact that context is important in a user query.

  - The user query is embedded with the same model used to embed the dataset.

  - Using the *cosine similarity* the model compares the query with the recipes and it sorts the 100 recipes that are most similar to the user query.
