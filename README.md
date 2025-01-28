Here’s a detailed and engaging README file for your project:

---

# **Chat with PDF Files Using DeepSeek-R1 LLM**

## **Overview**
This project is a **Retrieval-Augmented Generation (RAG) System** designed to enable interactive conversations with PDF files. Upload PDF documents, process their text, and ask questions to get precise and context-aware answers using the **DeepSeek-R1 LLM** powered by **Groq Mixtral-8x7b**. The app combines the power of **LangChain**, **FAISS**, and **OpenAI Embeddings** to deliver fast and accurate responses.

---

## **Key Features**
- **PDF Upload & Processing**: Extract and process text from multiple PDF files.
- **RAG Workflow**: Combines information retrieval and generative capabilities for accurate answers.
- **Context-Aware Responses**: The DeepSeek-R1 model provides detailed answers or informs if the context is unavailable.
- **Streamlit Interface**: A user-friendly, interactive interface for smooth functionality.

---

## **Technology Stack**

### **Backend**
- **LangChain**: Workflow orchestration for LLM-powered applications.
- **FAISS**: High-performance vector database for similarity search.
- **OpenAI Embeddings**: Robust text embeddings for vectorization.
- **Groq LLM (DeepSeek-R1)**: Advanced conversational model.

### **Frontend**
- **Streamlit**: Clean and intuitive user interface for interacting with PDFs.

---

## **Installation**

### **Prerequisites**
- Python 3.9+
- Pip
- Groq API key (obtainable from [Groq](https://www.groq.com/))

### **Steps to Install and Run**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the `.env` file:
   - Create a `.env` file in the root directory.
   - Add your Groq API key:
     ```env
     GROQ_API_KEY=your-groq-api-key
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## **How It Works**

### **Uploading and Processing PDFs**
1. Use the **sidebar** to upload one or more PDF files.
2. Click **Submit & Process** to extract text and create a searchable FAISS vector database.
3. Wait for the **success message** confirming the PDFs have been indexed.

### **Asking Questions**
1. Enter your question in the input field on the main page.
2. The app retrieves relevant information from the vector database.
3. The **DeepSeek-R1 model** generates an accurate, context-aware response.

---

## **File Structure**
```
.
├── app.py                     # Main Streamlit app
├── requirements.txt           # Required Python libraries
├── .env                       # Environment variables (Groq API key)
├── faiss_index/               # Folder containing the FAISS vector store
└── README.md                  # Project documentation
```

---

## **Example Scenarios**

### **Use Case 1: Academic Research**
Upload research papers and ask detailed questions about their content.

> **Example Question:** “What are the key findings on page 5?”

### **Use Case 2: Legal Document Analysis**
Extract specific clauses or terms from contracts.

> **Example Question:** “What is the termination clause in this agreement?”

### **Use Case 3: Educational Support**
Quickly retrieve explanations or summaries from textbooks.

> **Example Question:** “Explain the concept of retrieval-augmented generation.”

---

## **Future Enhancements**
1. **Support for Additional File Formats**: Enable processing of Word, Excel, and plain text files.
2. **Custom Chunking**: Allow users to adjust chunking size for optimized performance.
3. **Cloud Storage**: Integrate cloud solutions for handling larger datasets.
4. **Multimodal Queries**: Add support for querying images and diagrams embedded in PDFs.

---

## **Acknowledgments**
- **Groq**:  (DeepSeek-R1) model.
- **LangChain**: For seamless integration of LLM workflows.
- **FAISS**: For efficient vector search and retrieval.

---

## **License**
This project is licensed under the MIT License.

---

## **Contact**
For queries or feedback, feel free to reach out:
- **Name**: Siddharth Kharche
- **Email**: [siddukharche04@gmail.com](mailto:siddukharche04@gmail.com)
- **GitHub**: [siddharth-Kharche](https://github.com/siddharth-Kharche)

---

### **Start Conversing with Your PDFs Today!**  
:books: **Upload, Ask, and Discover!** :speech_balloon:
