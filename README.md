# End-to-end-LLM System for Question Answering
A Retrieval-Augmented Generation System for Question Answering Focused on Pittsburgh.

'extract-wiki.py' and 'extract-web.py' scrape the web for context files pertaining to Pittsburgh and CMU. These are annotated using AI (GPT-4) and manual review. The annotated files are combined with preexisting annotated files available on the internet.

'model_gpt2.ipynb' merges these files and uses open source models available through the HuggingFace library to prompt questions along with the context files to generate retrieval-augmented answers about Pittsburgh/CMU. 
