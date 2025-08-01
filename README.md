# Towards a Conceptual Model for AI-Driven Web Accessibility Remediation: A Prompt-Based Approach


<center><img src="code/images/model.jpg" style="margin:auto; width:100%"/></center>

This repository contains the source code and associated files to replicate the experiments described in our submission to *The 13th International Conference on Software Engineering Research and Innovation (CONISOFT 2025)* (Paper ID: 61). 

This README provides an overview of the repository structure, manuscript details, and usage instructions.

## Manuscript Information

**Title:** Towards a Conceptual Model for AI-Driven Web Accessibility Remediation: A Prompt-Based Approach

**Paper ID:** 61

### Authors

**Guillermo Vera-Amaro**  
*Universidad Veracruzana*  
Email: gvera@uv.mx  

**José Rafael Rojano-Cáceres**  
*Universidad Veracruzana*  
Email: rrojano@uv.mx  

## Repository Structure

The repository is organized as follows:

- `conceptual-model.ipynb`: Main notebook to reproduce the experiment.
- `figures/`: This folder contains all figures automatically generated by the notebook.
- ìmages/`: This folder contains explanatory visual assets accompanying the code and article.
- `output/`: This folder stores generated HTML variants produced by each model across different configurations.
- `templates/`: This folder includes the accessibility-aware templates used in the generation prompts.
  
A Python environment capable of running Jupyter Notebooks is required. Supported options include:

- Visual Studio Code (local)
- Jupyter Notebook (local or online)
- Google Colab (online)

## Requirements

To run the experiment successfully, you need the following API keys:

1. **OpenAI API key** – stored in the environment variable `OPENAI_API_KEY`.
2. **Google AI API key** – stored in the environment variable `GOOGLE_API_KEY`.
3. **Jina AI API key** – stored in the environment variable `JINA_API_KEY`.

We recommend creating a `.env` file in the root directory to securely store these keys. The notebook is configured to automatically load the variables from this file at runtime. Use the following format:

```
OPENAI_API_KEY=your_openai_api_key_here
GOOGLE_API_KEY=your_google_api_key_here
JINA_API_KEY=your_jina_api_key_here
```

## Usage Instructions

1. Open `conceptual-model.ipynb` in your chosen notebook environment.
2. Run the notebook sequentially to reproduce the experiment.

## Additional Notes

For full details on the methodology and results, refer to the associated article.
