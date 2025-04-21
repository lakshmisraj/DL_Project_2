# DL_Project_2
Deep Learning Spring 2025: Finetuning with LoRA Parameter. Efficient Finetuning of LLMs with Low-Rank Adaption (LoRA) for News Data
# LoRA Fine-Tuning with Hugging Face Transformers

This project explores **Low-Rank Adaptation (LoRA)** for parameter-efficient fine-tuning of large language models using Hugging Face's `transformers` and `peft` libraries. The notebook provides a complete pipeline for adapting a base model (such as GPT or LLaMA) using minimal additional parameters while preserving efficiency and performance.

## 📌 Objectives

- Understand and apply the LoRA technique for efficient fine-tuning
- Leverage Hugging Face's `peft` and `transformers` libraries
- Load a pre-trained language model and apply LoRA adaptation
- Train on a sample dataset
- Save and test the adapted model

---

## 📁 Project Structure

├── 2_Lora_Project_2_(1).ipynb   # Main notebook with code and explanation

├── README.md                    # Project description (this file)

---

## 🔧 Requirements

Install the following Python libraries:

<pre>
pip install transformers datasets peft accelerate
</pre>

How to Run

	1.	Clone this repository or download the .ipynb file.
 
	2.	Install the dependencies listed above.
 
	3.	Open the notebook in Jupyter Notebook or JupyterLab:

<pre>
jupyter notebook 2_Lora_Project_2_(1).ipynb
</pre>


4.	Follow each cell sequentially to:
 
	•	Load the base model
	•	Apply LoRA
	•	Prepare dataset
	•	Train the model
	•	Evaluate results
