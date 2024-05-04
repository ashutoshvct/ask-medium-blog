# medium-analyzer

---Ingestion
- Loading the medium blog (TextLoader)
- Splitting the blog into smaller chunks (TextSplitter)
- Embed the chunks and get vectors (OpenAIEmbeddings)
- Store the embeddings in Pinecone Vectorstore (PineconeVectorstore)

---Retrival
- Get the embeddings from Pinecone Vectorstore, Embedding User Query
- Semantic Search (Relevant Vectors)
- Prompt Augmentation
- Generation