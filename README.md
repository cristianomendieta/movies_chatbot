##### Movies ChatBot

This project is aimed at developing a chatbot for movie queries/recommendations utilizing the TMDb API as its foundation.

### Setup
To get started, ensure you have the following prerequisites installed:

- pipx: `pip install pipx`
- poetry: `pipx install poetry`
- Verify poetry installation: `poetry --version`

Once installed, install the project dependencies using:

```bash
poetry install
```

### Running the Notebook
The code has been developed using Jupyter Notebook, hence it follows a sequential structure. Ensure to define the environment variables `GROQ_API_KEY` and `BEARER_TOKEN_TMDB` in the `.env` file.