# About This Example
This example demonstrates how to use the LabVIEW LLM libraries to build a simple Retrieval-Augmented Generation (RAG) QA chat agent.

# Usage Instructions
1. **Enter OpenAI Key:** In the block diagram of `simple_rag_qa_chat_agent.vi`, enter your OpenAI API key.
2. **Verify Qdrant Vector Store:** Ensure that your Qdrant vector store is running and that the `host_url` is properly configured in the VI’s block diagram.
3. **Run the Example `1_vectorizing_text_data`:** This step creates the vector data store with the necessary collection for performing RAG.
4. **Ensure Node.js Installation:** Confirm that Node.js (version 18.20.4 or higher) is installed on your system. This example temporarily uses Node.js to host services for displaying conversations on the UI. Future versions will remove this dependency.
5. **Run the VI:** Execute `simple_rag_qa_chat_agent.vi` to start the chat application. You can ask questions such as *What models do you support?* to retrieve information from the vectorized data stored in your Qdrant vector store.