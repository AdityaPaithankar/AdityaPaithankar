from pathlib import Path

readme = r'''<div align="center">

# 👋 Hey, I'm Aditya Paithankar

### Data Science • Machine Learning • Deep Learning • AI

*Turning data into insights and building practical AI solutions.*

<p>
  <a href="https://github.com/AdityaPaithankar">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github" alt="GitHub Profile"/>
  </a>
  <a href="https://www.linkedin.com/in/adityapaithankar0316/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

</div>

---

## 🧑‍💻 About Me

- 🎓 Computer Science engineering student focused on **Data Science and Machine Learning**.
- 🔍 Interested in extracting insights from data and developing useful ML/DL applications.
- 🧠 Learning and building with **machine learning, neural networks, computer vision, and Generative AI**.
- 🛠️ Enjoy working across the project lifecycle: data preparation, model development, evaluation, APIs, and deployment.
- 🤝 Open to collaborating on meaningful data science and AI projects.

## 🧰 Tech Stack

### Languages & Data Analysis
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn"/>
</p>

### Machine Learning & Deep Learning
<p>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
</p>

### Apps, APIs & Tools
<p>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="VS Code"/>
</p>

## 🚀 Featured Projects

### 🏠 House Price Prediction
A machine learning application that estimates house prices using regression models and presents predictions through an interactive Streamlit interface.

**Focus:** Data preprocessing · Regression · Model evaluation · Streamlit

### 👤 Gender & Age Detection
A computer vision project exploring face detection and multi-output deep learning to estimate age and predict gender from images or webcam input.

**Focus:** CNNs · TensorFlow/Keras · OpenCV · Model inference

### 💸 SmartPocket — Personal Finance Assistant
A fintech concept for organizing transactions into spending pockets, with the goal of adding AI-powered insights based on categorized financial data.

**Focus:** Fintech · Data categorization · AI-assisted financial insights

### 🚌 College Bus Tracking System
A college transport solution designed around GPS-based bus location, estimated arrival times, and map-based tracking.

**Focus:** GPS · Maps · Real-time tracking

### 🧾 TripSplit
A group-expense management application focused on recording shared expenses and calculating settlements between trip members.

**Focus:** FastAPI · PostgreSQL · SQLAlchemy · Redis · Docker

> Explore my repositories for source code, implementation details, and project updates.

## 📚 Currently Learning

- Exploratory Data Analysis (EDA) and feature engineering
- Model evaluation, validation, and practical ML workflows
- CNNs and computer vision with OpenCV
- Transformers, LLM applications, and Retrieval-Augmented Generation (RAG)
- Building and deploying ML applications with APIs and Docker

## 🏅 Certifications & Highlights

- **NPTEL / SWAYAM:** Python for Data Science — Elite Certification
- **IBM:** Machine Learning with Python
- **IBM:** Generative AI
- **IIT Indore:** Incubate Certificate

## 📊 GitHub Overview

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AdityaPaithankar&show_icons=true&hide_border=true&rank_icon=github" alt="GitHub statistics"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AdityaPaithankar&layout=compact&hide_border=true" alt="Most-used languages"/>

<img src="https://streak-stats.demolab.com?user=AdityaPaithankar&hide_border=true" alt="GitHub contribution streak"/>

</div>

## 🤝 Let's Connect

I'm interested in connecting with people working on **Data Science, Machine Learning, Deep Learning, and AI engineering**.

- 💼 [LinkedIn](https://www.linkedin.com/in/adityapaithankar0316/)
- 🧑‍💻 [GitHub Repositories](https://github.com/AdityaPaithankar?tab=repositories)

---

<div align="center">

*“Learn continuously. Build thoughtfully. Improve with every iteration.”*

</div>
'''
path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({len(readme.splitlines())} lines)")
