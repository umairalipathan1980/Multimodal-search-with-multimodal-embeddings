# Multimodal search/retrieval with multimodal embeddings
This code uses Cohere's multimodal model to store the text and image embeddings in the same shared space. It then demonstrates the text-to-text, text-to-image, and image-to-image retrieval tasks for a given query.  
Following libraries may be required to run the entire code.  
```!pip install cohere umap-learn seaborn matplotlib numpy pandas regex altair scikit-learn ipython faiss-cpu```
```!pip install nest-asyncio python-dotenv llama-parse qdrant-client```
The code demonstrates a business case of searching product information from a product catalogue containing both text and images.  
The code requires API keys of OpenAI, Cohere, and Llama Cloud. The free API keys of Cohere and Llama Cloud can be obtained by creating an account at their websites.  
The API keys are loaded from a .env file. Set the API keys in this file as follows:
```OPENAI_API_KEY=sk-xxx...
COHERE_API_KEY=xxx...
LLAMA_CLOUD_API_KEY=xxx...```
