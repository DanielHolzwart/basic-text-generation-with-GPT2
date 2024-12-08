# Basic-text-generation-with-GPT2

In this workbook we will download GPT2 from huggingface and create our own custom made greedy search, top_k and top_p functions. It turns out that the output from model.generate() is different than our custom top_p and top_k functions. This is probably due to the way sampling is done.
