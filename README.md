# RAG-Driven-Chatbot
### Advanced Document Query System with Local LLMs

#### Overview  
This web application integrates advanced Retrieval-Augmented Generation (RAG) with locally hosted Large Language Models (LLMs) to deliver precise and context-aware responses based on uploaded PDF documents. The app emphasizes user privacy and efficient data processing, leveraging cutting-edge tools for seamless interaction and retrieval.
![image](https://github.com/user-attachments/assets/776d709f-313b-4a4f-8c38-af9b9f65f8d6)


#### Core Functionality  
- **PDF Upload & Processing**: Users can upload PDF files, which are processed into manageable chunks for accurate information retrieval.  
- **Enhanced RAG Workflow**: Combines FAISS for fast similarity searches with context injection, ensuring factually grounded responses from uploaded documents.  
- **Local LLM Integration**: Utilizes models like Llama 3.1, Mistral, Gemma 2, and LLaVA through Ollama for all computations, maintaining data privacy.  
- **Efficient Embedding with FAISS**: Stores and retrieves document embeddings efficiently using **nomic-embed-text** for rapid and accurate query results.  
- **Context-Aware Chat History**: Users can maintain conversation context, allowing for continuous discussions without losing relevance.  

#### Technology Stack  
- **Front End**: Interactive interface built using Streamlit.  
- **LLMs**: Locally hosted models like Llama 3.1, Mistral, Gemma 2, and LLaVA via Ollama.  
- **Embeddings**: Generated using nomic-embed-text.  
- **Document Retrieval**: Powered by FAISS for high-performance similarity searches.

#### How It Works  
1. **Upload a PDF**: The user uploads a PDF document, which is split into smaller sections for efficient processing.  
2. **Generate Embeddings**: The content chunks are embedded using nomic-embed-text and stored in the FAISS database.  
3. **Ask a Question**: The user queries the app, triggering retrieval of relevant document sections to provide context for the LLM’s response.  
4. **Maintain Chat History**: Ensures that conversation continuity is preserved.  

#### System Requirements  
- **Python Environment**: Python 3.10.0 or later.  
- **Dependencies**: Install required Python libraries from `requirements.txt`.  
- **Ollama Setup**: Download one or more LLM models (e.g., Llama 3.1) and **nomic-embed-text** for embeddings. Adjust the code to reflect your model configuration.

#### Running the Application  
1. **Set Up Environment**:  
   - Create a virtual environment using `virtualenv`.  
   - Activate the environment and install dependencies from `requirements.txt`.  

2. **Configure Ollama**:  
   - Install Ollama and download necessary models.  
   - Ensure **nomic-embed-text** is installed for embeddings.

3. **Start the Application**:  
   - Navigate to the directory containing `app.py`.  
   - Run the app with the command:  
     ```bash
     streamlit run app.py
     ```  

This system offers a streamlined and secure way to query documents using the latest advancements in LLMs and retrieval mechanisms.
## References:
1. Krish Naik's Updated langchain Playlist:https://youtube.com/playlist?list=PLZoTAELRMXVOQPRG7VAuHL--y97opD5GQ&feature=shared
2. Pavan Belagatti Linkedin profile: https://www.linkedin.com/in/pavan-belagatti/


