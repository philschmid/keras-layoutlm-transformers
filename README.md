# Fine-tuning LayoutLM for document-understanding using Keras & Hugging Face Transformers 

In this blog, you will learn how to fine-tune [LayoutLM (v1)](https://huggingface.co/docs/transformers/model_doc/layoutlm) for document-understand using Hugging Face Transformers. LayoutLM is a document image understanding and information extraction transformers. LayoutLM (v1) is the only model in the LayoutLM family with an MIT-license, which allows it to be used for commercial purposes compared to other LayoutLMv2/LayoutLMv3. 

We will use the [FUNSD](https://guillaumejaume.github.io/FUNSD/) dataset a collection of 199 fully annotated forms. More information for the dataset can be found at the [dataset page](https://guillaumejaume.github.io/FUNSD/).

You will learn how to:


1. [Setup Development Environment](#1-setup-development-environment)
2. [Load and prepare FUNSD dataset](#2-load-sroie-dataset)
3. [Fine-tune and evaluate LayoutLM](#4-fine-tune-and-evaluate-donut-model)

Before we can start, make sure you have a [Hugging Face Account](https://huggingface.co/join) to save artifacts and experiments. 
