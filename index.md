---
layout: home
title: Aryan Raj | Portfolio & Blog
---

### 👨‍💻 About Me

Data Scientist | AI Explorer | Blogger

Hey Guys! I'm Aryan, a data scientist passionate about combining machine learning and storytelling. Welcome to my portfolio and blog!

---

### 🛠 My Projects

- **[Fraud Detection (Kaggle Dataset)](https://github.com/aryn920/Fraud-Detection-Program)**  
  Used logistic regression and EDA to identify fraudulent transactions in a dataset of 6.3 million rows.

- **[RockyBot – News Research Assistant](https://github.com/aryn920/LLM)**  
  A Streamlit app using LangChain and OpenAI to pull insights from news articles using vector stores and retrieval QA.

- **[Stock Market Analysis](https://github.com/aryn920/Stock_Data-Analysis)**  
  Analyzed stock market trends using web-scraping and pandas on financial news data.

---

### ✍️ Latest Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})  
  *{{ post.date | date: "%b %-d, %Y" }}*
{% endfor %}

---

### 📬 Contact Me

- **Email:** [araj7@wisc.edu](mailto:araj7@wisc.edu)  
- **LinkedIn:** [linkedin.com/in/aryan-raj-a742bb203](https://www.linkedin.com/in/aryan-raj-a742bb203)
