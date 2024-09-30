# GenAI based RAG Application by Pathway & IIT Roorkee
Develop a real-time or static RAG-based LLM application completely using Pathway LLM App templates or Pathway with Llamaindex / Pathway with Langchain.
This demo shows how to create a RAG application using Pathway that provides always up-to-date knowledge to your LLM without the need for a separate ETL.
This demo allows you to:
- 📂 **Set up a vector store** for real-time indexing of documents from Google Drive, Microsoft 365 SharePoint, or local directories.
- 🤖 **Integrate an OpenAI LLM** with your knowledge base for seamless access to intelligent responses.
- 🎯 **Receive accurate and precise answers** to your queries with high-quality information.
- 🗂️ **Easily ask questions** about specific folders, files, or all documents using powerful filtering options.
- ✍️ **Use LLMs via API** to automatically summarize large texts.
- 👁️‍🗨️ **Get an executive summary** from multiple files, giving you a quick overview of all relevant knowledge.

  ## How it works (Understanding RAG pipeline)
- 📄 **app.py**: The main application code, written in Python, using Pathway.
- 🛠️ **app.yaml**: Configuration file for data sources, OpenAI LLM model, and the web server. Customize this to modify the LLM model, use Google Drive data, or adjust filesystem directories for indexing.
- 📋 **requirements.txt**: Contains dependencies for the pipeline. Use with `pip install -r` to set up the environment locally.
- 🐋 **Dockerfile**: Docker configuration for running the pipeline inside a container.
- 🗝️ **.env**: Environment variables configuration file where the OpenAI key is stored.
- 📁 **data/**: A folder with example files for running test cases.
  
- 📄 **app.py**: 
  ![llm_01_new](https://github.com/user-attachments/assets/1f48b8d6-13de-4651-8e4d-ed046cf539a8)
  ![llm_02_new](https://github.com/user-attachments/assets/956c7ebf-35ba-4536-9193-25c5331a9830)
  ![llm_03_new](https://github.com/user-attachments/assets/bcf6250c-50ff-4a63-b19a-6f0b027817c7)

- 🛠️ **app.yaml**:
- ![llm_04_new](https://github.com/user-attachments/assets/4989d07c-a84e-46e8-852e-7e72286e277d)



  




