# n8n Automation Projects

This repository contains automation workflows I built using **n8n** for various AI and automation tasks.  
Each workflow is exported as a `.json` file, which can be directly imported into any n8n instance.

---

## 🚀 Workflows Included

### 1. Gmail Responder (`Gmail_responder.json`)
- Automatically responds to incoming Gmail messages based on predefined rules.  
- Can be extended with AI for smart replies.

### 2. RAG using n8n (`RAG_using_n8n.json`)
- A Retrieval-Augmented Generation (RAG) pipeline.  
- Upload a PDF, vectorize the content, store it in Pinecone, and query with LLMs for contextual Q&A.

### 3. File Upload for RAG (`file_upload_RAG.json`)
- Helper workflow for uploading and processing PDF files for RAG pipelines.  
- Handles file input and sends processed chunks to Pinecone.

### 4. Inventory Handler (`inventory_handler.json`)
- Automates inventory updates and tracking.  
- Can be integrated with e-commerce platforms or databases.

---

## 📂 Project Structure
n8n-automation-projects/
│-- Gmail_responder.json
│-- RAG_using_n8n.json
│-- file_upload_RAG.json
│-- inventory_handler.json
│-- README.md


---

## 🔧 How to Use

1. **Install n8n**  
   Follow the [official installation guide](https://docs.n8n.io/getting-started/installation/).

2. **Open your n8n instance**  

3. **Import a workflow**  
   - Go to **Workflows → Import from File**  
   - Select the `.json` file from this repository  

4. **Update credentials**  
   - Configure Gmail, Pinecone, API keys, and any other integrations required.  

---

## 📸 Screenshots 
<img width="934" height="479" alt="image" src="https://github.com/user-attachments/assets/010febb2-0bc4-47b4-83e4-8c36794878d1" />

<img width="815" height="536" alt="image" src="https://github.com/user-attachments/assets/7a5ab2f5-d236-42a5-9250-a521273de46c" />


---

## 📜 License
This project is for educational and portfolio purposes.  
You are free to use, modify, and extend these workflows.
