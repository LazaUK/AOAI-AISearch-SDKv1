# Retrieval-Augmented Generation (RAG) with Azure OpenAI and Azure AI Search

This repo demonstrates how to setup RAG solution in Azure, using Azure OpenAI on "own data" in tandem with Azure AI Search.

> [!NOTE]
> Data file used in this repo was borrowed from the [Microsoft's Azure OpenAI + Azure AI Search open-source solution](https://github.com/Azure-Samples/azure-search-openai-demo)

## Table of contents:
- [Pre-requisites](https://github.com/LazaUK/AOAI-AISearch-SDKv1#pre-requisites)
- [Scenario 1: Authenticating with API Key]()
- [Scenario 2: Authenticating with Entra ID]()

## Pre-requisites
1. Upgrade openai Python package to its latest supported version:
``` PowerShell
pip install --upgrade openai
```
2. Set the following 7 environment variables before running the notebooks:

| Environment Variable | Description |
| --- | --- |
| _AZURE_OPENAI_API_BASE_ | Base URL of the AOAI endpoint |
| _AZURE_OPENAI_API_VERSION_ | API version of the AOAI endpoint |
| _AZURE_OPENAI_API_KEY_ | API key of the AOAI endpoint (_required for Scenario 1 only_) |
| _AZURE_OPENAI_API_DEPLOY_ | Name of the AOAI deployment |
| _AZURE_SEARCH_API_BASE_ | Base URL of the AI Search endpoint |
| _AZURE_SEARCH_API_KEY_ | API key of the AI Search endpoint (_required for Scenario 1 only_) |
| _AZURE_SEARCH_API_INDEX_ | Name of the AI Search index |

## Scenario 1: Authenticating with API Key

## Scenario 2: Authenticating with Entra ID
