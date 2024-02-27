# LLM Text Summarization Tool

- Using LLMs as a tool to summarize news article

- Dataset link: Hugging Face CNN_News_Articles_2011-2022

- Model: bart-large-cnn 406 billion Params

- Boosted Infrence speed creating a custom dataset from huggingface (48 mins on single GPU)

- For the test dataset ~7K news text, LLM was able to summarize them on average just using 20% of words present in news articles

- Note: Large news articles edited to mimic the training config of 1024 token length
