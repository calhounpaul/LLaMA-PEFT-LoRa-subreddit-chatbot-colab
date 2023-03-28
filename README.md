# LLaMA PEFT LoRa subreddit chatbot
ChatGPT(v4) summary of this notebook: This Jupyter notebook demonstrates how to create a chatbot using Parameter Efficient Fine Tuning (PEFT) on Facebook's LLaMA Large Language Model (LLM) and a public Reddit corpus. The chatbot is fine-tuned using an RTX 3090 GPU. The code extracts subreddit data using the ps_reddit_tool, cleans the text with redditcleaner, and organizes the data into linear conversations for training. It uses a range of months from 2022 as an example and focuses on the "wholesome" subreddit. Finally, the chats are formatted and saved as a dataset for further training. Various packages are installed and important hyperparameters are set. The LLaMA model is trained using a dataset, which is shuffled and tokenized. The PEFT weights are then integrated into the original model for uploading to HuggingFace. Afterward, a HuggingFace-compatible model is created and a rudimentary Gradio chatbot interface is demonstrated.

/r/NewHampshire after ~4 hours of training on one rtx 3090:

![llama](https://user-images.githubusercontent.com/26489865/228280189-8928913b-7ce7-498a-869d-b7414b4dd242.png)
