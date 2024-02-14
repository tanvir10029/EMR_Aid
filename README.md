# WIP Tool to help medical professionals learn about their patients faster
- Doctors can take up to 45 minutes or more navigating patient EMR
- This tool takes in the records and uses RAG (retrieval augmented generation) to ensure accuracy
- In progress of implementing Graph based data source

Prerecs:
!curl https://ollama.ai/install.sh | sh
!pip install chromadb
!pip install langchain
!pip install BeautifulSoup4
!pip install gpt4all
!pip install langchainhub
!pip install pypdf
!pip install chainlit
!pip install pyngrok

Run to create embedding:
python load_data_vdb.py

Run:
chainlit run RAG.py

References:
https://medium.com/@samschifman/rag-on-fhir-with-knowledge-graphs-04d8e13ee96e
https://medium.com/@vndee.huynh/build-your-own-rag-and-run-it-locally-langchain-ollama-streamlit-181d42805895
https://www.youtube.com/watch?v=7kDaMz3Xnkw
