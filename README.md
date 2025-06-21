# ML_projects
# Adnan Nasir’s GitHub Portfolio

Welcome to my GitHub portfolio! Here you’ll find a comprehensive collection of my projects spanning network engineering, automation, data science, machine learning, generative AI, and more. Each project includes a brief overview, key technologies used, and links to the corresponding repository.

---

## Table of Contents

1. [Network Automation & Monitoring](#network-automation--monitoring)
2. [Network Configuration & Simulation](#network-configuration--simulation)
3. [Power Automate Workflows](#power-automate-workflows)
4. [Python Automation & Scripting](#python-automation--scripting)
5. [Data Science & Machine Learning Projects](#data-science--machine-learning-projects)
6. [Generative AI & NLP Projects](#generative-ai--nlp-projects)

---

## Network Automation & Monitoring

- **NTP Data Extraction & Excel Highlighting**  
  Parse NTP log files, extract timing data, and highlight anomalies in Excel for quick analysis.  
  *Technologies*: Python, pandas, openpyxl

- **Log-On Script Failure Detection**  
  Monitor LastWrite Time values in email alerts and trigger notifications if deviations occur.  
  *Technologies*: Power Automate, Outlook, Email Triggers

- **vRealize Operations Alert Monitor**  
  Automated flow to detect `[vRealize Operations Manager]` alerts and send actionable email notifications.  
  *Technologies*: Power Automate, ServiceNow integration

## Network Configuration & Simulation

- **Router-on-a-Stick (ROAS) with VLANs**  
  Cisco Packet Tracer network using an ISR4331 router and 3560/2960 switches to configure VLANs 10 & 20 with inter-VLAN routing.  
  *Technologies*: Cisco Packet Tracer, IOS

- **DHCP Snooping & Rapid PVSTP**  
  Implemented DHCP snooping, queue-rate limit, EtherChannel, and Rapid PVSTP on a multi-tier switch design.  
  *Technologies*: Cisco Packet Tracer, IOS

- **Dual-Stack (IPv4 & IPv6) ROAS**  
  Configured inter-VLAN routing for both IPv4 (10.10.10.0/26, 10.20.99.0/20) and IPv6 (EUI-64) networks.  
  *Technologies*: Cisco Packet Tracer, IOS

## Power Automate Workflows

- **Email-Based Monitoring Flows**  
  Collection of flows that process incoming emails to perform automated checks and dispatch notifications:  
  - vRealize Alerts  
  - LastWrite Time Script Checks  
  - Active Directory Health Reports  
  *Technologies*: Power Automate, SMTP, Outlook, Azure Functions

## Python Automation & Scripting

- **Outlook Email Processing**  
  Extract data from Outlook emails, generate Excel reports, and send follow-up notifications.  
  *Technologies*: Python, Microsoft Graph API, pandas, openpyxl

- **Network Monitoring Scripts**  
  Automated periodic checks and root-cause analyses for network performance metrics.  
  *Technologies*: Python, REST APIs, Grafana

## Data Science & Machine Learning Projects

- **Healthcare Diagnosis RAG Model**  
  Retrieval-Augmented Generation LLM solution using the Merck Manual for medical diagnosis assistance.  
  *Technologies*: Google Colab, LangChain, OpenAI API, prompt engineering

- **Fraud Detection Pipeline**  
  End-to-end predictive model: data ingestion (SQL/REST), EDA, modeling, Azure ML deployment, and Power BI monitoring.  
  *Technologies*: Python, scikit-learn, Azure ML SDK, Power BI

- **Bank Churn Prediction**  
  Neural network classifier to predict customer churn over a 6-month horizon with feature importance analysis.  
  *Technologies*: Python, TensorFlow, pandas, matplotlib

- **Loan Approval Prediction**  
  Decision tree classifier with post-pruning, extensive EDA, and business recommendation generation.  
  *Technologies*: Python, scikit-learn

- **Visa Approval Classifier**  
  Classification model to predict visa application outcomes leveraging EDA and performance comparison visualizations.  
  *Technologies*: Python, scikit-learn, matplotlib

## Generative AI & NLP Projects

- **GenAI in Healthcare Research Statement**  
  Polished research statement on agentic AI and GenAI applications in healthcare and academia.  
  *Technologies*: LaTeX, Markdown

- **NLP Alert Monitoring System**  
  Natural language processing workflow to categorize and respond to network alert messages.  
  *Technologies*: Python, spaCy, Hugging Face Transformers

- **LLM Fine-Tuning & Optimization**  
  Framework for fine-tuning LLMs, applying quantization, pruning, and distillation methods for inference efficiency.  
  *Technologies*: PyTorch, TensorRT, ONNX

- **Network Operations RAG Chatbot**  
  Creation of a RAG-based chatbot in a production pipeline on Azure for the network operations department.  
  *Technologies*: RAG, LangChain, FAISS vector DB, chunking, tokenization, Llama2, text & vector embeddings, Fine-tuning, Drift Monitoring, RLHF feedback loop
  

---

> _"Turning data into insights, networks into intelligence, and ideas into impact."_  
> — Adnan Nasir
