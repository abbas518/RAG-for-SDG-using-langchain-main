# RAG-for-SDG-using-langchain
## Introduction 
Analyze Literature to understand how progress on SDG 16 affects SDG 1 and SDG 10 just by uploading PDF documents and ask questions.
workflow: 
- Loads the Uploaded the PDF documents
- The documents are then splitted into smaller chunks
- A vector database is created by embedding the chunks
- User questions are first passed throught the vector database similarity and semantic prompt generation
- Response are generated based on the context of the documents provided

## Instructions
 To use this application :
 - Clone the repository
 - Install dependencies
   ```
   pip install -r requirements.txt
   
- Run the app by the command
  ```
  streamlit run app.py

- The application will run on your browser
- Now you upload PDFs then ask questions 
