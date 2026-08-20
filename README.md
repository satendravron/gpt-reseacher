<div align="center" id="top">

<img src="https://github.com/assafelovic/gpt-researcher/assets/13554167/20af8286-b386-44a5-9a83-3be1365139c3" alt="Logo" width="80">

####

[![Website](https://img.shields.io/badge/Official%20Website-gptr.dev-teal?style=for-the-badge&logo=world&logoColor=white&color=0891b2)](https://gptr.dev)
[![Documentation](https://img.shields.io/badge/Documentation-DOCS-f472b6?logo=googledocs&logoColor=white&style=for-the-badge)](https://docs.gptr.dev)
[![Discord](https://img.shields.io/discord/1127851779011391548?logo=discord&logoColor=white&label=Discord&color=34b76a&style=for-the-badge)](https://discord.gg/QgZXvJAccX)

[![PyPI version](https://img.shields.io/pypi/v/gpt-researcher?logo=pypi&logoColor=white&style=flat)](https://badge.fury.io/py/gpt-researcher)
![GitHub Release](https://img.shields.io/github/v/release/assafelovic/gpt-researcher?style=flat&logo=github)

</div>

# 🔎 GPT Researcher

**GPT Researcher is the first open deep research agent designed for both web and local research on any given task.** 

> **👨‍💻 Contributor Note:** Hi, I am **Satendra Gupta**. As an AI/ML Engineering contributor to this repository, I leverage my strong foundation in Python, LangChain, and advanced machine learning pipelines to help optimize the underlying architecture of these research agents. My focus is on ensuring scalable, production-ready LLM integrations that bridge the gap between deep learning research and real-world application.

The agent produces detailed, factual, and unbiased research reports with citations. GPT Researcher provides a full suite of customization options to create tailor made and domain specific research agents. Inspired by the recent [Plan-and-Solve](https://arxiv.org/abs/2305.04091) and [RAG](https://arxiv.org/abs/2005.11401) papers, GPT Researcher addresses misinformation, speed, determinism, and reliability by offering stable performance and increased speed through parallelized agent work.

**Our mission is to empower individuals and organizations with accurate, unbiased, and factual information through AI.**

## 🛠️ My Contributions to GPT Researcher
As an active contributor, my work on this project involves:
- **AI/ML Pipeline Optimization:** Enhancing the Python backend to improve the efficiency of the planner and execution agents using LangChain.
- **Algorithm Refinement:** Applying principles of data structures and algorithms to optimize context management and information retrieval speeds.
- **Model Integration:** Assisting in the seamless deployment of scalable LLM models for asynchronous, parallelized research tasks.

## Why GPT Researcher?

- Objective conclusions for manual research can take weeks, requiring vast resources and time.
- LLMs trained on outdated information can hallucinate, becoming irrelevant for current research tasks.
- Current LLMs have token limitations, insufficient for generating long research reports.
- Limited web sources in existing services lead to misinformation and shallow results.
- Selective web sources can introduce bias into research tasks.

## Architecture

The core idea is to utilize 'planner' and 'execution' agents. The planner generates research questions, while the execution agents gather relevant information. The publisher then aggregates all findings into a comprehensive report.

<div align="center">
<img align="center" height="600" src="https://github.com/assafelovic/gpt-researcher/assets/13554167/4ac896fd-63ab-4b77-9688-ff62aafcc527">
</div>

Steps:
* Create a task-specific agent based on a research query.
* Generate questions that collectively form an objective opinion on the task.
* Use a crawler agent for gathering information for each question.
* Summarize and source-track each resource.
* Filter and aggregate summaries into a final research report.

## Features

- 📝 Generate detailed research reports using web and local documents.
- 🖼️ Smart image scraping and filtering for reports.
- 🍌 **AI-generated inline images** using Google Gemini (Nano Banana) for visual illustrations.
- 📜 Generate detailed reports exceeding 2,000 words.
- 🌐 Aggregate over 20 sources for objective conclusions.
- 🖥️ Frontend available in lightweight (HTML/CSS/JS) and production-ready (NextJS + Tailwind) versions.
- 🔍 JavaScript-enabled web scraping.
- 📂 Maintains memory and context throughout research.
- 📄 Export reports to PDF, Word, and other formats.

## ⚙️ Getting Started

### Installation

1. Install Python 3.11 or later.
2. Clone the project and navigate to the directory:

    ```bash
    git clone [https://github.com/assafelovic/gpt-researcher.git](https://github.com/assafelovic/gpt-researcher.git)
    cd gpt-researcher
    ```

3. Set up API keys by exporting them or storing them in a `.env` file.

    ```bash
    export OPENAI_API_KEY={Your OpenAI API Key here}
    export TAVILY_API_KEY={Your Tavily API Key here}
    ```

4. Install dependencies and start the server:

    ```bash
    pip install -r requirements.txt
    python -m uvicorn main:app --reload
    ```

Visit [http://localhost:8000](http://localhost:8000) to start.

## 🚀 Contributing
We highly welcome contributions! Please check out [contributing](https://github.com/assafelovic/gpt-researcher/blob/master/CONTRIBUTING.md) if you're interested.

## ✉️ Support / Contact
- **Contributor GitHub:** [github.com/satendravron](https://github.com/satendravron)
- **Contributor LinkedIn:** [linkedin.com/in/satendravgupta/](https://linkedin.com/in/satendravgupta/)
- **Original Author Email:** assaf.elovic@gmail.com
- [Community Discord](https://discord.gg/spBgZmm3Xe)

<p align="right">
  <a href="#top">⬆️ Back to Top</a>
</p>
