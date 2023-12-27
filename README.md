<h1 align="center">
A Workshop on HuggingFace Echo System (Text Generation)
</h1>

Hugging Face is a powerful open-source platform that has gained widespread recognition in the AI and ML communities for its flexibility, robustness, and community-driven approach. Founded in 2017 as a chatbot application aimed at teenagers, Hugging Face has since transformed into a cutting-edge platform that provides a wide range of tools and services for AI development, training, and collaboration. With its user-friendly interface and extensive capabilities, Hugging Face is revolutionizing the way AI models are created and shared. Whether you're a seasoned expert or just starting out in the field, Hugging Face offers something for everyone. In this article, we'll take a closer look at the platform's offerings and explore how it's transforming the AI ecosystem.

# Contents

Following are the contents of the workshop on the Hugging Face Echo System.

## Introduction Hugging Face Echo System 

The Hugging Face Ecosystem offers a comprehensive set of features:

### Account Profile Setup:
Quickly set up your account profile [Sign Up](https://huggingface.co/join)

Access Tokens GenerationGenerate Read/Write access tokens for enhanced functionality [Access Tokens](https://huggingface.co/settings/tokens).

### Hugging Face Docs Overview:

Navigate documentation on Transformers, Datasets, PEFT, Tokenizers, Inference API, and Gradio. See the [Hugging Face Docs](https://huggingface.co/docs).
### Hugging Face Models and Datasets:
Explore NLP tasks, models like [gpt2](https://huggingface.co/gpt2), [Llama-2-7b-chat-hf](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf), and more [Text Generation](https://huggingface.co/models?pipeline_tag=text-generation&sort=trending). Dive into discussions on Model Cards, Files and Versions, Training, Deployment, and Usage in Transformers. Access tutorials, including deploying LLM in the Hugging Face Inference Endpoint [Notebooks](https://github.com/datafyresearcher/datafy-huggingface/tree/main/notebooks).
### Hugging Face Spaces:

Engage with AI applications like [Gemini Playground](https://huggingface.co/spaces/Roboflow/Gemini) and [GPT4 UI](https://huggingface.co/spaces/ngoctuanai/gpt4ui). Learn to create a new space with a demonstration of a [Streamlit Application](https://huggingface.co/new-space).
### Hugging Face Tasks

Get a brief overview of NLP tasks, especially [Text Generation](https://huggingface.co/tasks/text-generation).
### Hugging Face Chat
Access top AI chat platforms, including [Llama-2-7b-chat-hf](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf), [falcon-180B-chat](https://huggingface.co/tiiuae/falcon-180B-chat), and [CodeLlama-34b-Instruct-hf](https://huggingface.co/codellama/CodeLlama-34b-Instruct-hf). See the [Hugging Chat](https://huggingface.co/chat/).
### Hugging Face Community Overview

Explore educational resources like the [NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1), stay updated through the [NLP blog](https://huggingface.co/blog?tag=nlp), and collaborate on GitHub through the [Hugging Face repository](https://github.com/huggingface).

## Finetuning a Model and Deploying on Huggingface
In this section, we will have a hands-on overview of finetuning an LLM model with Custom dataset and deploying on huggingface Hub.

### Model Download and Finetune

This notebook will give participants a hands-on overview of finetuning the GPT2 model with custom data using PEFT techniques.

<a href="https://colab.research.google.com/github/datafyresearcher/datafy-huggingface/blob/main/notebooks/1_GPT2_Small_Qlora_FineTuning.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Deploy Model for Inference

Once the model is finetuned, we create the Model Inference using Hugging Face Inference API.

<a href="https://colab.research.google.com/github/datafyresearcher/datafy-huggingface/blob/main/notebooks/2_Deploy_GPT2_Inference_Endpoints.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>



