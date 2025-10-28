**## Set up steps**

**1. Google Cloud Project and Vertex AI API:**
- Create a Google Cloud project.
- Enable the Vertex AI API for your project.
  
**2. Google AI API Key:**
- Obtain a Google AI API key from Google AI Studio.
  
**3. Pinecone Account:**
- Create a free account on the Pinecone website.
- Obtain your API key from your Pinecone dashboard.
- Create an index named company-files in your Pinecone project.
  
**4. Google Drive:**
- Create a dedicated folder in your Google Drive where company documents will be stored.
  
**5. Credentials in n8n:**
- Configure credentials in your n8n environment for:
- Google Drive OAuth2
- Google Gemini(PaLM) Api (using your Google AI API key)
- Pinecone API (using your Pinecone API key)
  
**5. Import the Workflow:**
- Import this workflow into your n8n instance.
  
**6. Configure the Workflow:**
- Update both Google Drive Trigger nodes to watch the specific folder you created in your Google Drive.
- Configure the Pinecone Vector Store nodes to use your company-files index.
