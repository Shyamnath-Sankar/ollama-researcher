# Ollama Researcher

This project is an AI-powered research tool that helps you quickly gather and synthesize information from the web. Simply enter a topic, and the assistant will generate a comprehensive article summarizing the latest news and insights.

  
## Introduction

This project is an internet research assistant built using Python, Streamlit, and Swarm AI. It allows users to enter a search query and receive a polished, publication-ready article based on the latest web search results.

## Why Ollama Researcher
  * Objective conclusions for manual research can take weeks, requiring vast resources and time.
  *  LLMs trained on outdated information can hallucinate, becoming irrelevant for current research tasks.
  * Current LLMs have token limitations, insufficient for generating long research reports.
  * Limited web sources in existing services lead to misinformation and shallow results.
  * Selective web sources can introduce bias into research tasks.
  * It runs everythings locally keeping the user data private.



## Features

* **Web Search:** Uses DuckDuckGo to search the web for the latest news and information on a given topic.
* **Research Analysis:** Analyzes and synthesizes the search results, removing duplicates, identifying related themes, and verifying information consistency.
* **Article Generation:** Transforms the analyzed research results into a well-formatted and engaging article.
* **Streamlit UI:** Provides a user-friendly interface for entering search queries and viewing the generated articles.


## Installation

1.Create a virtual environment
```
python -m venv env
```
2.Activate the environment
```
env\Scripts\activate
```
3.Install Ollama

[install Ollama](https://ollama.com/)

4.Clone this repository:
```
 git clone https://github.com/Shyamnath-Sankar/ollama-researcher.git
```
5.Install the necessary libraries:
```
pip install -r requirement.txt
```
6.Download model from ollama set the model name in .env
 ``` 
 llm = <modelname>
 ```
4.To run
```
streamlit run app.py
```

## Demo


https://github.com/user-attachments/assets/d481428a-2f8e-421c-ae15-35d362080557



## Contributing

Contributions are welcome! Please feel free to submit pull requests or issues.

## License

# Genrec Community License

## License Terms

1. **Use of the Repository**  
   You are free to use, copy, modify, and distribute this repository for both commercial and private purposes, provided that you give appropriate credit to the Genrec Community.

2. **Attribution**  
   Any public use of the repository (including but not limited to derivative works, distribution, and publications) must include a clear acknowledgment of the Genrec Community as the original provider of this work.

3. **No Warranty**  
   The repository is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

4. **Limitation of Liability**  
   In no event shall the Genrec Community be liable for any damages arising from the use of this repository.

5. **Acceptance**  
   By using this repository, you agree to comply with these terms.

---

**Genrec Community**  
[ai.genrec@gmail.com]  
[02-11-2024]
