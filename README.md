# 💬 Dify E-commerce AI Agent 

This repository contains the configuration, prompt, and knowledge base for a chatbot built using [Dify Cloud](https://cloud.dify.ai).

---
## 📌 Project Overview

This chatbot:
- Uses **OpenAI GPT-3.5 turbo**
- E-commerce chatbot agent for fictional PC store who Answers product FAQs and guides users through support issues
- Leverages a **knowledge base** with CSV files
- Built using [Dify Cloud](https://cloud.dify.ai)
- Here is the direct link for the chatbot https://udify.app/chat/I9cimnSuSZFXPmdO
  
## 📦 Project Structure

```bash
dify-chatbot/
├── prompt.md                  # Main user-facing prompt
├── system_instructions.txt    # System-level behavior rules
├── chatflow.yaml              # Combined configuration file (YAML format)
├── knowledge_base/            # Documents used as knowledge base
│   ├── computer_software_products.csv
│   └── computer_hardware_products.csv
└── README.md

🚀 How to Use
Option 1: Manual Upload to Dify Cloud
1.Go to https://cloud.dify.ai
2.Create a new app
3.Paste:
        system_instructions.txt into Instructions 
4.Upload the KB files under Knowledge Base

5.In Debug and preview you can preview your bot and also can enable some more fetures 
6.After expected preview click on Publish 
7.Click on Run App
8.Now your Chatbot is ready to Answer!!

Option 2: Direct Upload to Dify Cloud
1.Go to https://cloud.dify.ai
2. Click on Chatflow
3. Import DSL File
4. Upload the Chatbot.yaml  ##Note: you Can download the file from the repo
                
