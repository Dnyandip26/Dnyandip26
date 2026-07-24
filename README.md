## 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dnyandip26&show_icons=true&theme=tokyonight&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dnyandip26&layout=compact&theme=tokyonight)


![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=Dnyandip26&theme=tokyo-night)

## 💡 Featured Code

### RAG Pipeline Implementation
\`\`\`python
from langchain.vectorstores import FAISS
from langchain.embeddings import HuggingFaceEmbeddings

def create_rag_pipeline(documents):
    embeddings = HuggingFaceEmbeddings()
    vectorstore = FAISS.from_documents(documents, embeddings)
    return vectorstore.as_retriever()
\`\`\`


