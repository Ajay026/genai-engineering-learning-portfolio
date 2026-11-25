# GenAI Engineering Projects

Project notes based on the [ProjectPro GenAI Engineer career path](https://www.projectpro.io/learning-paths/genai-engineer). The descriptions explain each course project's scope; they do not claim employer delivery or production deployments. Estimated effort is for an independent build and test, not a project date.

## NLP Project for Beginners on Text Processing and Classification

Classify app reviews as positive or negative using a Python text-processing pipeline.

**Key Takeaways**

- Clean and tokenize reviews, then compare bag-of-words, n-grams and TF-IDF features.
- Train a logistic regression classifier and test predictions on new reviews.

**Tech Stack:** Python, NLTK, scikit-learn, TF-IDF, logistic regression

**Estimated build effort:** 1 month · [ProjectPro reference](https://www.projectpro.io/project-use-case/nlp-text-processing-classification-python)

## Multi-Class Text Classification with Deep Learning using BERT

Use a BERT-based model for multiclass text classification and trace how it differs from earlier NLP approaches.

**Key Takeaways**

- Compare Word2Vec, GloVe and FastText representations.
- Study recurrent models and attention, then apply a BERT classifier to a multiclass dataset.

**Tech Stack:** Python, BERT, Transformers, Word2Vec, GloVe, FastText, LSTM

**Estimated build effort:** 1 month · [ProjectPro reference](https://www.projectpro.io/project-use-case/multi-class-text-classification-using-bert)

## LLM Project to Build and Fine Tune a Large Language Model

Compare approaches for adapting a language model to dialogue summarization.

**Key Takeaways**

- Prepare tokenized inputs and compare prompting with fine-tuning.
- Use parameter-efficient fine-tuning and evaluate summaries with ROUGE.

**Tech Stack:** Python, Transformers, PEFT, ROUGE

**Estimated build effort:** 1–2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/llm-project-for-beginners-to-build-and-fine-tune-an-llm)

## Build a Langchain Streamlit Chatbot for EDA using LLMs

Turn dataset questions into SQL or Python through a Streamlit interface for exploratory data analysis.

**Key Takeaways**

- Connect the app to its data source and give the model schema context.
- Use LangChain prompt templates and agents to generate analysis and visualizations.

**Tech Stack:** Python, Streamlit, LangChain, MySQL, SQL

**Estimated build effort:** 1 month · [ProjectPro reference](https://www.projectpro.io/project-use-case/streamlit-langchain-chatbot)

## Langchain Project for Customer Support App in Python

Model a support conversation as a sequence of steps, from customer authentication to information retrieval and a final summary.

**Key Takeaways**

- Use LangChain to connect the steps and retrieve relevant information.
- Handle voice input with Whisper speech-to-text.

**Tech Stack:** Python, LangChain, ReAct, Whisper

**Estimated build effort:** 1 month · [ProjectPro reference](https://www.projectpro.io/project-use-case/langchain-project-for-customer-support-app-in-python)

## Build and Deploy Text-2-SQL LLM Using OpenAI and AWS

Translate natural-language questions into SQL and surface query results in Streamlit.

**Key Takeaways**

- Use OpenAI and LangChain to generate SQL with data-platform context.
- Include query error handling and a correction loop; review the AWS EC2 deployment workflow.

**Tech Stack:** Python, OpenAI API, LangChain, Databricks, Snowflake, Streamlit, AWS EC2

**Estimated build effort:** 2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/text-2-sql-llm)

## Build a Customer Support Agent using OpenAI and AzureML

Use a retrieval-augmented generation pipeline to ground a support assistant in customer support documents.

**Key Takeaways**

- Embed and index documents, then retrieve context for answer generation.
- Connect the pipeline to Azure ML and review how feedback is collected.

**Tech Stack:** Python, Azure ML, OpenAI embeddings, vector search, RAG

**Estimated build effort:** 2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/customer-support-agent-using-azureml-and-openai)

## Build a Multimodal RAG System using AWS Bedrock and FAISS

Recommend food items using information from text and images.

**Key Takeaways**

- Store inputs in S3 and use a model to describe the images.
- Embed descriptions and related text, then retrieve relevant items through FAISS.

**Tech Stack:** Python, AWS Bedrock, Amazon S3, Amazon Titan Embeddings, FAISS, LangChain

**Estimated build effort:** 2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/multimodal-rag-recommender-system)

## Llama2 Project for MetaData Generation using FAISS and RAGs

Generate metadata using a local Llama 2 model and a searchable index of source text.

**Key Takeaways**

- Extract and embed passages into a FAISS index.
- Retrieve supporting passages and pass them to a local model for generation.

**Tech Stack:** Python, Llama 2, FAISS, open-source embeddings

**Estimated build effort:** 1 month · [ProjectPro reference](https://www.projectpro.io/project-use-case/llama2-project-for-metadata-generation-model)

## Build a Medical AI Assistant using Unsloth and QLoRA

Use an educational medical dataset to study domain adaptation through parameter-efficient fine-tuning. Not intended for clinical use.

**Key Takeaways**

- Prepare the training data and compare base-model and fine-tuned responses.
- Configure QLoRA using Unsloth and review the inference workflow.

**Tech Stack:** Python, Unsloth, LoRA, QLoRA, Streamlit

**Estimated build effort:** 2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/medical-ai-chatbot-and-assistant)

## Autogen Project to Build an Intelligent AI Personal Assistant

Coordinate specialized agents in a personal assistant with a Slack interface.

**Key Takeaways**

- Separate email, calendar and search tasks into tool-backed workflows.
- Review OAuth integration and how the agents coordinate requests.

**Tech Stack:** Python, AutoGen, GPT-4o, Google APIs, OAuth2, Slack

**Estimated build effort:** 2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/agentic-ai-project-to-build-ai-personal-assistant)

## Build an Intelligent AI Assistant with FastMCP and LangGraph

Connect an assistant to tools exposed over the Model Context Protocol.

**Key Takeaways**

- Build a FastMCP server and discover its tools from the client.
- Use LangGraph to select tools and process their outputs in an assistant workflow.

**Tech Stack:** Python, FastMCP, LangGraph, MCP, ReAct

**Estimated build effort:** 1–2 months · [ProjectPro reference](https://www.projectpro.io/project-use-case/mcp-project-to-build-an-ai-assistant-with-fastmcp)
