---
layout: default
modal-id: 2
date: 2025-01-19
img: seinfeld_monologue_generator_01.png
alt: image-alt
project-date: Aug 2025
client: Personal Project
category: LLM Training/ Fine Tuning
description: This Large Language Model can generate a Seinfeld style monologue if one enters a keyword. Click <a href="https://huggingface.co/spaces/alligatorlee/seinfeld-monologue-llm" target="blank"><b>here</b></a> to check it out. (It may take a minute for the model to load.) <br></br><h1><b>Overview</b></h1><br></br><p><b>Goal:</b> Train (fine-tune) a Llama-3.1-8B model on existing Seinfeld monologues to make an LLM app which can output a Seinfeld style monologue by inputing a keyword.</p><p><b>Process:</b> The training text was obtained by scraping, extracting, and cleaning scripts from https://www.seinfeldscripts.com. Then, the training text was transformed into a dictionary with 'instruction','input','output' as keys in Python. Finally the transformed text was fed into the Llama-3.1-8B model for training. Hugging Face was used to host the trained LLM. Gradio was used to build the LLM UI. </p><p><b>Tools:</b>  Python, Torch, Llama-3.1-8B model, Unsloth, LoRA Adapters (for efficient training), Gradio (for the LLM UI), Hugging Face (LLM hosting).</p>



---
