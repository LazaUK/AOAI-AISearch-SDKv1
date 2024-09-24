# Retrieval-Augmented Generation (RAG) with Azure OpenAI and Azure AI Search

By default, blobs and containers on Azure Storage account are not accessible by anonymous accounts.

This repo explains how to authenticate with an Azure Storage account, download a target blob (using the **_Microsoft logo_** as an example), convert it into Base64 format and then feed it to an Azure OpenAI model for further processing.


> **Note:** Data file used in this repo was borrowed from [Microsoft's Azure OpenAI + Azure AI Search open-source solution](https://github.com/Azure-Samples/azure-search-openai-demo)

## Table of contents:
- [Pre-requisites]()
- [Step 1: Authenticating with Azure Storage account]()
- [Step 2: Downloading source image and converting it into Base64]()

## Pre-requisites
1.
