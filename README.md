# 📘 Mind AI  

Mind AI is an intelligent assistant that allows users to upload PDF research documents and interact with them using AI-powered queries. The system processes, indexes, and retrieves relevant document segments to generate precise responses.  

## 🚀 Features  

- **PDF Upload & Processing**: Users can upload research documents in PDF format.  
- **Document Chunking & Indexing**: Splits the document into manageable chunks and indexes them using embeddings.  
- **AI-Powered Queries**: Retrieves relevant document sections and generates concise answers.  
- **Interactive Chat Interface**: Engaging and intuitive Streamlit UI.  

## 🛠️ Technologies Used  

- **[Streamlit](https://streamlit.io/)** – For creating the interactive UI.  
- **[LangChain](https://python.langchain.com/)** – For document processing, embedding, and retrieval.  
- **[Ollama](https://ollama.com/)** – For AI model inference (deepseek-r1).  
- **[PDFPlumber](https://github.com/jsvine/pdfplumber)** – For extracting text from PDFs.  

## 📂 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/FadyHassanein/RAG-With-Deep-Seek.git
cd RAG-With-Deep-Seek
```
### 2️⃣ Create a Virtual Environment
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```
3️⃣ Install Dependencies
```bash
pip install -r req.txt
```
4️⃣ Run the Application
```bash
streamlit run rag_deep.py
```
🏗️ Project Structure
```bash
📂 your-repo-name
 ┣ 📂 pdfs/               # Folder for storing uploaded PDFs
 ┣ 📜 app.py              # Main application script
 ┣ 📜 requirements.txt    # Dependencies list
 ┣ 📜 README.md           # Project documentation
```

