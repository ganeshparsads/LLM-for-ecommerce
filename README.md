# LLM-for-ecommerce
Using Flan-T5 for e-commerce text classification.

This GitHub project is aimed at fine-tuning the flan t5 model for a text classification task using an E-commerce text dataset for 4 categories - "Electronics", "Household", "Books" and "Clothing & Accessories".

The dataset is a classification-based E-commerce text dataset, which almost covers 80% of any E-commerce website. The dataset consists of product and description data for 4 categories. The dataset can be found [here](https://doi.org/10.5281/zenodo.3355823).

The project employs the tokenizer of flan-t5 by Hugging Face, which helps in splitting the input text into a format that is understandable by the model.

An evaluation function has been implemented for post-processing the labels and predictions, which will also handle sequence length adjustments.
