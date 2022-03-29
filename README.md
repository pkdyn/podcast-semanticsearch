# Semantic search on podcast transcripts using Weaviate
  
Podcast transcripts: [`Changelog`](https://github.com/thechangelog/transcripts)  
[Vectorization module](https://weaviate.io/developers/weaviate/current/retriever-vectorizer-modules/text2vec-transformers.html#pre-built-images): [`sentence-transformers/msmarco-distilroberta-base-v2`](https://huggingface.co/sentence-transformers/msmarco-distilroberta-base-v2)

# Set-up Guide  
1. Set-up  Weaviate: `docker-compose up -d`*
2. Install Weaviate client: `pip install weaviate_client==3.2.2`
3. Import data: `python3 import.py`
4. Query data: Go to [console.semi.technology](https://console.semi.technology/) on a non-chromium-based browser (like Edge or Safari) and connect to http://localhost:8881. Click on Query Module to start Querying.
 
*Change port `8881` in `docker-compose.yml`  and `import.py` to a different value (like 9999), if not able to connect.  
<br>
# Example Queries:

<img width="850" alt="image" src="https://user-images.githubusercontent.com/72981484/160333947-88c5b1d4-bc12-43da-b36a-06ea635b9739.png">

<img width="804" alt="image" src="https://user-images.githubusercontent.com/72981484/160334057-f70d9a2d-8d4b-447b-b49d-1e65ff90b7ac.png">

<img width="823" alt="image" src="https://user-images.githubusercontent.com/72981484/160334158-d59c924b-7630-46b7-8d13-47a259c19469.png">



