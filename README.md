## Reasoning Engine in Google Cloud Vertex AI

${\textsf{\color{lightgrey}Work in Progress}}$

>**General**: *A reasoning engine is a contrast to a search engine. It is an application or subsystem that makes logical inferences based on a set of axioms (the rules) and input data.*

>**Google**: *Reasoning Engine (LangChain on Vertex AI) is a managed service to help building and deploying an agent reasoning framework. It provides the flexibility to choose the amount of reasoning to be fed to the LLM and how it can be handled with customised code.*

## Main components

1.   **Gemini** - a family of generative AI models developed by *Google DeepMind* designed for multimodal use cases.

2.   **Function Calling in Gemini** allows to create a description of a function in source code and pass the description to a language model in a request. The response from the model includes the name of a function that matches the description and the arguments to call it with.

3.   **Reasoning Engine in Vertex AI**

## Overview

Define python functions used as tools via Gemini Function Calling. Reasoning Engine integrates closely with the Python SDK for the Gemini model in Vertex AI and is able to manage prompts, agents, and examples in a modular way. Reasoning Engine is compatible with *LangChain*, *LlamaIndex*, or other python frameworks.

