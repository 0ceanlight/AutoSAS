# AutoSAS 🚀

**AutoSAS** is an AI-powered prototype that generates complete websites from natural language prompts.  
The system asks the user to describe their website idea and automatically produces the corresponding **HTML/CSS/JavaScript** files, packaged and ready to download.  

Built during a hackathon challenge, AutoSAS demonstrates how **large language models (LLMs)** can be orchestrated in a **multi-agent workflow** to automate software creation beyond boilerplate code.


## 🔑 Key Features

- **Natural Language to Code** – Users describe a website, and AutoSAS generates a functional template.  
- **Multi-Agent LLM Pipeline** –  
  - **Developer Agent**: generates draft website code (HTML/CSS/JS).  
  - **Debugger Agent**: analyzes errors and regenerates corrected code.  
- **Automated Error Handling** – Code is compiled, diagnosed, and iteratively refined for robustness.  
- **Extensible Architecture** – While demonstrated for websites, the pipeline can generalize to other software domains.  
- **Hackathon-Built** – Created in a fast-paced team setting, where I served as **tech lead**.  


## ⭐️ Why It Matters

Traditional website development starts with repetitive setup work. AutoSAS showcases how **AI-assisted coding** can:  
- Accelerate development by automating scaffolding.  
- Improve reliability with **iterative debugging loops**.  
- Serve as a proof of concept for **AI-driven SaaS applications**.  

This project highlights skills in **generative AI, prompt engineering, LLM orchestration, error diagnosis, and full-stack development** - areas with direct relevance to modern ML/AI engineering roles.


## ⚙️ Setup

This project requires the following Python packages:

- Flask

Install dependencies using:

```bash
pip install -r requirements.txt
```


## ▶️ Usage

1. Add your OpenAI key as an environment variable:

   * macOS/Linux:

     ```bash
     export OPENAI_API_KEY="your_api_key_here"
     ```
   * Windows (PowerShell):

     ```powershell
     setx OPENAI_API_KEY "your_api_key_here"
     ```
2. Run the app:

   ```bash
   python main.py
   ```
3. Open the provided local URL in your browser.
4. Enter a description of your website idea → receive a downloadable `.zip` file with the generated code.


## 🛠️ Technology

* **Python Flask** backend for UI and API handling.
* **OpenAI API** for LLM-driven code generation and debugging.
* Multi-step **pipeline design** for reliability and extensibility.


## 📌 Future Directions

* Expand beyond websites to generate **end-to-end SaaS applications**.
* Integrate deployment workflows for one-click publishing.
* Explore reinforcement mechanisms for improving LLM code quality.

