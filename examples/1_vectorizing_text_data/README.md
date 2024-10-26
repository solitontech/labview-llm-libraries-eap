# About This Example
This example demonstrates how to use the LabVIEW LLM libraries to vectorize text files and store them in a Qdrant vector database.

# Usage Instructions
1. **Enter OpenAI Key:** In the block diagram of "vectorizing_text_data.vi", enter your OpenAI API key.
2. **Verify Qdrant Vector Store:** Ensure that your Qdrant vector store is running and that the host_url is correctly configured in the VI’s block diagram.
3. **Run the VI:** Execute the VI to recursively process all .md files in this repository. The VI will perform chunking, vectorization, and store the resulting vector data in the Qdrant vector database.
