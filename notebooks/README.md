<h1 align="center">
Hugging Face Ecosystem: NoteBooks Objectives
</h1>

<p align="center" width="100%">
    <img width="100%" height="100%" src="https://github.com/datafyresearcher/datafy-huggingface/blob/main/data/7.jpg">
</p>

# **Objectives: GPT2 Small QLoRA Fine-Tuning**
<a href="https://colab.research.google.com/github/datafyresearcher/datafy-huggingface/blob/main/notebooks/1_GPT2_Small_Qlora_FineTuning.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Here are some possible objectives that can be design for the *GPT2 Small QLoRA Fine-Tuning* description:

1. Install and set up necessary packages and dependencies, including nvidia-smi command and updates with pip.
2. Load and process data from the "ecommerce-faq.json" file, including printing the first question and dumping the data in a new file ("dataset.json").
3. Create a DataFrame from the questions key of the data.
4. Implement the GPT-2 language model and tokenizer, and count the number of trainable parameters in the model.
5. Enable gradient checkpointing for the model and prepare it for k-bit training.
6. Add the LoRA (Low-Rank Adaptive) configuration to the model.
7. Add a prompt for creating an account.
8. Adjust the generation configurations for the model.
9. Enhance prompt generation with Torch's inference mode.
10. Build a HuggingFace model and dataset by loading the dataset from a JSON file, generating and tokenizing prompts for causal language modeling, shuffling and mapping train data for prompt generation and tokenization, and implementing a training loop for fine-tuning the GPT2 model on the custom dataset.
11. Load the TensorBoard extension and display the runs directory.
12. Save the pretrained GPT-2 model and push it to the Hugging Face Model Hub.
13. Update the PEFT model and tokenizer.
14. Update the generation configuration parameters for the model.
15. Add the ability to create an account through the chatbot interface.
16. Refactor the generate_response function to improve readability and maintainability.
17. Improve the customer service FAQ responses.

# **Objectives: Deploy GPT2 Inference API and Endpoints**

<a href="https://colab.research.google.com/github/datafyresearcher/datafy-huggingface/blob/main/notebooks/2_Deploy_GPT2_Inference_Endpoints.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Here are some possible objectives that can be design for the *Deploy GPT2 Inference API and Endpoints* description:

1. Install and set up the necessary packages and dependencies for the project, including but not limited to:
    * NVIDIA smi command for checking GPU usage
	* Python packages required for HuggingFace models and Peft framework
	* Dependencies for running the GPT-2 model on GPUs with compute capability >= 8
2. Integrate the QLoRA adapter into the project
3. Update the model and tokenizer to use bfloat16 precision on GPUs with compute capability >= 8
4. Merge the GPT-2 model and tokenizer and push them to HuggingFace Hub
5. Add support for pushing the GPT-2 model and tokenizer to HuggingFace Hub
6. Implement a text generation pipeline using the GPT-2 model and tokenizer
7. Create a handler function for generating text using the Transformers library
8. Develop an endpoint for handling user requests for text generation
9. Create a new file named `handler.py` in the "File and versions" directory and insert the appropriate code into it
10. Create a new file named `requirements.txt` in the "File and versions" directory and include the necessary dependencies in it
11. Set up the Inference API for hosting the GPT-2 model and update the read key as needed
12. Configure the inference endpoints for the GPT-2 model
