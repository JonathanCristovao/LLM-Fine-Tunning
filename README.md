# LLM Fine Tunning Projects 🚀

Welcome to the LLM Fine-Tuning project repository!

![](assets/cover.png)

## Fine Tuning Notebook Table 📑

| Notebook Title                                               | Description                                                  | Colab Code                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **1. Fine-tuning LLM with LoRA** | Details and code for efficient training of large language models using LLaMA 3. | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O71t8u4FgEyzx2VBDxDnS5PgE4U5fNJo?usp=sharing) |
| **2. Fine-tuning LLM with Custom dataset** | ... | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com) |



## Datasets to fine-tuning 🔎


Sentiment and Text Classification Datasets:


| **Dataset Name** | **Description** | **How to Use** |
|-------------------|-----------------|----------------|
| **imdb**          | One of the most popular datasets for sentiment classification. Contains 50,000 movie reviews labeled as positive or negative. | `from datasets import load_dataset`<br>`dataset = load_dataset("imdb")` |
| **yelp_polarity** | Derived from Yelp reviews, labeled as positive or negative. Great for sentiment analysis in business contexts. | `from datasets import load_dataset`<br>`dataset = load_dataset("yelp_polarity")` |
| **amazon_polarity** | Reviews of products on Amazon, labeled as positive or negative. | `from datasets import load_dataset`<br>`dataset = load_dataset("amazon_polarity")` |
| **tweet_eval**    | Dataset for sentiment classification in tweets with multiple categories (positive, negative, neutral). Recommended for tasks related to social media. | `from datasets import load_dataset`<br>`dataset = load_dataset("tweet_eval", "sentiment")` |
| **emotion**       | Text dataset with emotional labels such as joy, anger, sadness, etc. Excellent for tasks beyond binary sentiment. | `from datasets import load_dataset`<br>`dataset = load_dataset("emotion")` |
| **ag_news**       | News dataset categorized into 4 classes: world, sports, business, and science/technology. Useful for general text classification tasks. | `from datasets import load_dataset`<br>`dataset = load_dataset("ag_news")` |



## Models to fine-tuning 🖥

Models for fine-tuning: 

| **Model name**                | **Computational Resources Required** | **Description**                                                                                      | **How to Use**                                                                                   |
|---------------------------|-----------------------|--------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| **distilbert-base-uncased** | Low                | Compact version of BERT with fewer parameters, suitable for resource-constrained environments.    | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("distilbert-base-uncased")` |
| **distilroberta-base**     | Low                | Compact version of RoBERTa, ideal for tasks where RoBERTa performs well.                          | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("distilroberta-base")` |
| **albert-base-v2**         | Low                | A smaller and memory-efficient model derived from BERT.                                           | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("albert-base-v2")` |
| **mobilebert-uncased**     | Low                | Highly optimized for mobile devices.                                                             | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("mobilebert-uncased")` |
| **bert-base-uncased**      | medium                | The original BERT model with 12 layers and 110M parameters. Recommended for higher accuracy.      | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("bert-base-uncased")` |
| **roberta-base**           | medium                | Pre-trained with more data than BERT, excellent for text classification tasks.                    | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("roberta-base")` |
| **deberta-v3-base**        | medium                | A recent model, more optimized than BERT and RoBERTa.                                             | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("deberta-v3-base")` |
| **electra-base-discriminator** | medium            | Efficiently trained model to distinguish real from generated text.                                | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("electra-base-discriminator")` |
| **finbert**                | medium                | BERT fine-tuned for financial tasks.                                                             | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("finbert")` |
| **bertweet-base**          | medium                | BERT fine-tuned for Twitter data.                                                                | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("bertweet-base")` |
| **biobert-base-cased-v1.1**| medium                | BERT fine-tuned for biomedical data.                                                             | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("biobert-base-cased-v1.1")` |
| **bert-large-uncased**     | High                 | A larger version of BERT with 24 layers and 340M parameters.                                      | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("bert-large-uncased")` |
| **roberta-large**          | High                 | A larger version of RoBERTa, highly effective for NLP tasks.                                      | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("roberta-large")` |
| **deberta-v3-large**       | High                 | Delivers better performance but requires more computational resources.                            | `from transformers import AutoModel`<br>`model = AutoModel.from_pretrained("deberta-v3-large")` |



## Contributing 🤝

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License 📝

This project is licensed under the [MIT License](LICENSE).

---

Created with ❤️ by [Jonathan](https://github.com/JonathanCristovao)
