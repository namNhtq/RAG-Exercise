# Introduction to Retrieval Augmented Generation (RAG)

## About This Repository

Welcome to the **Introduction to Retrieval Augmented Generation (RAG)** excercise repository! This repository contains materials and exercises designed for students enrolled in the **Artificial Intelligence: Generative AI, Cloud, and MLOps (online)** course.

## Course Information

- **Course:** Artificial Intelligence: Generative AI, Cloud, and MLOps (online)
- **Topic:** Retrieval Augmented Generation (RAG)
- **Instructor:** Abhinav Kimothi
- **Date:** 01 March 2025

## What is RAG?

Retrieval Augmented Generation (RAG) is a technique that enhances the capabilities of Large Language Models (LLMs) by incorporating external knowledge retrieval. While LLMs have vast parametric memory, they are limited in terms of accuracy, recency, and factual consistency. RAG improves their performance by enabling dynamic access to non-parametric memory (e.g., external documents, knowledge bases, or databases) and integrating relevant information into responses.

### Topics Covered in this repository:

- Indexing Pipeline
    - Data Loading
    - Chunking (or Data Splitting)
    - Embeddings (or Data Transformation)
    - Storage (Vector Databases)

- Generation Pipeline
    - Search & Retrieval
    - Prompt Augmentation
    - LLM Generation

- RAG Evaluation using RAGAs Framework
    - Synthetic Dataset Generation
    - Calculation of Evaluation Metrics

## Repository Structure

```
📂 RAG-EXERCISE/
 ├── 📂 Assets/            # Logos, icons, and reference images
 ├── 📂 Data/              
 │   ├── EmployeeLeavePolicy.pdf #S ample document for RAG Exercise
 ├── 📂 Images/            # Visualization assets
 │   ├── ...
 ├── 📂 Memory/            # Folder to store the vector index locally
 ├── 📜 .env               # Environment variables (e.g., OpenAI API Key) that you should create
 ├── 📜 .gitignore         # Git ignore file
 ├── 📜 .gitattributes     # Git attributes file
 ├── 📜 Exercise_Intro_to_RAG.ipynb  # Main Jupyter notebook for RAG exercises
 ├── 📜 LICENSE            # License file
 ├── 📜 README.md          # This file
 ├── 📜 requirements.txt   # List of dependencies
```

## Getting Started

### Prerequisites

To run the code and exercises, ensure you have the following installed:

- Python 3.13.2+
- Jupyter Notebook
- Required libraries (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abhinav-kimothi/RAG-Exercise.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RAG Exercise
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Store your OpenAI API key in a `.env` file:
   - Create a `.env` file in the root directory:
     ```bash
     touch .env
     ```
   - Add your API key inside `.env`:
     ```
     OPENAI_API_KEY=your_openai_api_key_here
     ```
   - Ensure your scripts load the environment variables using `dotenv`:
     ```python
     from dotenv import load_dotenv
     import os
     load_dotenv()
     openai_api_key = os.getenv("OPENAI_API_KEY")
     ```
7. Open the notebook:
   ```bash
   jupyter notebook
   ```

## How to Use This Repository

- **Read the notebooks**: Start with the introductory notebook to understand RAG.
- **Run the code**: Experiment with provided examples and modify them to test different scenarios.
- **Complete the exercises**: Each notebook contains exercises to reinforce learning.
- **Engage with discussions**: Share insights, questions, and learnings.


## Contributions

If you would like to contribute or suggest improvements, feel free to submit a pull request or open an issue.

Happy learning and coding! 🚀

About me
---
Hi! I'm Abhinav! I am an entrepreneur and Vice President of Artificial Intelligence at Yarnit. I have spent over 15 years consulting and leadership roles in data science, machine learning and AI. My current focus is in the applied Generative AI domain focussing on solving enterprise needs through contextual intelligence. I'm passionate about AI advancements constantly exploring emerging technologies to push the boundaries and create positive impacts in the world. Let’s build the future, together!

#### If you'd like to chat, I'd be very happy to connect

[![GitHub followers](https://img.shields.io/badge/Github-000000?style=for-the-badge&logo=github&logoColor=black&color=orange)](https://github.com/abhinav-kimothi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=orange&color=black)](https://www.linkedin.com/comm/mynetwork/discovery-see-all?usecase=PEOPLE_FOLLOWS&followMember=abhinav-kimothi)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=black&color=orange)](https://medium.com/@abhinavkimothi)
[![Insta](https://img.shields.io/badge/Instagram-000000?style=for-the-badge&logo=instagram&logoColor=orange&color=black)](https://www.instagram.com/akaiworks/)
[![Mail](https://img.shields.io/badge/email-000000?style=for-the-badge&logo=gmail&logoColor=black&color=orange)](mailto:abhinav.kimothi.ds@gmail.com)
[![X](https://img.shields.io/badge/Follow-000000?style=for-the-badge&logo=X&logoColor=orange&color=black)](https://twitter.com/abhinav_kimothi)
[![Linktree](https://img.shields.io/badge/Linktree-000000?style=for-the-badge&logo=linktree&logoColor=black&color=orange)](https://linktr.ee/abhinavkimothi)
[![Gumroad](https://img.shields.io/badge/Gumroad-000000?style=for-the-badge&logo=gumroad&logoColor=orange&color=black)](https://abhinavkimothi.gumroad.com/)


[If you haven't already, please subscribe to the MEAP of A Simple Guide to Retrieval Augmented Generation here](https://mng.bz/8wdg)

<a href="https://mng.bz/8wdg" target="_blank">
    <img src="./Assets/Images/NewMEAPFooter.png" alt="New MEAP" style="width: 100%;" />
</a>

---















