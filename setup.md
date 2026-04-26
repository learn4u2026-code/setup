🔹Install UV (if not installed)
pip install uv
if you are using MAC: pip3 install uv
🔹 Check UV installed.
uv --version
🔹 Check Installed Packages
optional  command: uv pip list
🔹 Check Available Python Versions
uv python list
Specific version:
if you wanted to install any specific version of the python using the uv then 
use the below command:
uv python install <mention the cpython interpreter version>
🔹 Create Virtual Environment
uv venv <your-env-name> --python <your-python-version>
From requirements file:
1
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny
uv pip install -r requirements.txt
Course Access & Resources Guide
Log in to the platform:
https://krishnaikacademy.com/
Access your course: Navigate to your enrolled course and check all the prerequisites and live class
recordings.
Direct course portal:
https://learn.krishnaikacademy.com/web/courses/
GitHub Repository All Resources + Notion Notes):
GenAIBootcamp-1.0
https://github.com/sunnysavita10/Full-Stack
Notice Board Google Sheet):
https://docs.google.com/spreadsheets/d/1M7Dyr5EjDwu9EHIL5hvSJBmIQXifGH8QavIo_tbh8gk/edit?
usp=sharing
Git & GitHub Setup Guide (Step-by-Step)
✅ 1. Install Required Tools
Make sure you have the following installed:
Visual Studio Code
Git
GitHub account
Check Git installation:
git --version
📁 2. Create a New Project Folder
Method 1 Create locally and link to GitHub
Option A Using VS Code)
Open VS Code
Click File 
→
 Open Folder
Create a new folder (example: 
Option B Using Terminal / CMD
mkdir my-project
cd my-project
code .
my-project 
)
2
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny
�
� 3. Initialize Git in Your Project
Inside the VS Code terminal:
git init
This creates a hidden 
.git
 folder and starts tracking your project.
📄 4. Create Project Files
Example:
main.py
requirements.txt
➕ 5. Add Files to Git
git add .
This tracks all files in the folder.
💾 6. Commit Your Code
git commit -m "Initial commit"
This saves a project snapshot.
🌐 7. Create a Repository on GitHub
Go to GitHub
Click New repository.
Give it a name (usually the same as the folder's).
Click Create repository.
🔗 8. Link Local Project to GitHub
Copy your repository URL (example):
https://github.com/yourname/my-project.git
Then run:
git remote add origin https://github.com/yourname/my-project.git
🚀 9. Push Code to GitHub
3
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny
git branch -M main
git push -u origin main
🔁 Alternative Method Clone First)
Create a new repository on GitHub
Copy the repository URL
Clone the repository
git clone https://github.com/yourname/my-project.git
This downloads the repo into your current directory.
Open the project in VS Code
Make changes (add files, notebooks, folders)
Add changes
git add .
Commit changes
git commit -m "your message"
Push to GitHub
git push
LLM / GenAI Development: Tools & Frameworks
LLM Foundations
Huggingface
PyTorch
Finetuning
Unsloth
LLaMA Factory
Huggingface
Vector Databases & Search (RAG Backbone)
FAISS
4
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny
Chroma
Qdrant
Supabase
pgvector
Milvus
Pinecone
AWS OpenSearch
Azure AI Search
Databases & Storage
Neo4j
MongoDB
PostgreSQL
Redis
SQL Alchemy
LLM Application Building Framework
LangChain
Llama Index
Haystack
Lang Smith
Guardrails, Validation & Safety
Guardrails.ai
Nvidia Nemo
OpenAI Guardrail
Local LLMs & Runtime
Ollama
Experiment Tracking
MLflow
Data Modelling
Pydantic
MCP
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny 5
FastMCP
Document AI & Parsing
Llama Parser
Docling
Google Document AI
Amazon Textract
python-docx
PyMuPDF
pdfplumber
Parsio
Unstructured.io
Azure Document Intelligence
Agentic AI Frameworks
Lang Graph
Deepagent
AutoGen
n8n
Cloud GenAI Platforms
Google ADK
Agent Core
AWS Bedrock
Azure Cloud Foundry
GCP Vertex AI
Evaluation & Observability
RAGAS
TruLens
Llama Index Eval
DeepEval
OpenAI Evals
Prompt Engineering & Prompt Management
LangChain Prompt Hub
Class-02-28-Mar-Intro-GenAI-Tools-UV-Setup-Course-Access-&-Resources-Guide-Git-&-Github-Setup-Guide-by-Sunny 6
PromptLayer
OpenAI Cookbook / Prompt Examples
PromptHub
DSPy Prompt-as-Code approach)
Guidance Microsoft)
Deployment, Infrastructure & CI/CD
ECS  Fargate + EC2
AWS SageMaker
GitHub Actions
Azure Virtual Machines VMs
Azure Kubernetes Service AKS
Azure Container Apps / ACI
Testing
pytest
Pipeline Orchestration
Apache Airflow
