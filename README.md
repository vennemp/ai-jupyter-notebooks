# AI Jupyter Notebooks

This repository contains a collection of Jupyter notebooks demonstrating various AI concepts and implementations.

## Notebooks

Here is a list of the notebooks included in this repository:

1. [`agents-bedrock-chain-lab.ipynb`](agents-bedrock-chain-lab.ipynb): This lab runs through chaining agent output together. NOT COMPLETE
2. [`agents-bedrock-lab.ipynb`](agents-bedrock-lab.ipynb): This lab runs through building custom tools for LLM to invoke. 
3. [`klarna-plugin-chatgpt-lab.ipynb`](klarna-plugin-chatgpt-lab.ipynb): This lab runs through using a custom third party API to enhance your LLM performance. This lab uses ChatGPT due to token size which could cause $ issues with Bedrock.  I'm including this bc it is a good reference for understanding how the API Schema use in Agents for Bedrock works.  
4. [`bedrock-streaming-output.ipynb`](bedrock-streaming-output.ipynb): This lab goes through streaming output back to a user.
5. [`bedrock-chaining-outputs.ipynb`](bedrock-chaining-outputs.ipynb): This lab we will explore chaining outputs together.

## Installation

To run these notebooks, you'll need to install Jupyter, boto3, and langchain. You can do this with pip:

```bash
pip install jupyter langchain boto3
```

To use, just clone the repo and open a ipynb file in VScode. All of notebooks are in python - so make sure you select your currently installed python package as the kernel after opening.  

