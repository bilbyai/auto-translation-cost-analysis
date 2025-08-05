# Auto translation project

This project uses a Jupyter notebook to translate a large number of Chinese texts to English through API calls to LLMs, it then calculates the average price per document, using input and output tokens to calculate.


#### Optional: Create a conda environment

To create a conda environment for this repo, just run

```bash
conda create --name auto_translate python=3.13
conda activate auto_translate
```
## How to Use

1. Install dependencies (see below).
2. Set up your API keys in a `.env` file.
3. Run the notebook with Jupyter.

```bash
jupyter notebook auto_translation_cost_analysis.ipynb
```

## Installation

install the required Python packages:
```bash
pip install -r requirements.txt
```

## Environment variables
this project requires API keys for LLM services copy example_env to a new file .env
provide your API keys in .env as shown:

OPENAI_API_KEY=your_openai_api_key_here
ANTHROPIC_API_KEY=your_anthropic_key_here
# Add others as needed



