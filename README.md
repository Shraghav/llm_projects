# llm_projects
These are the projects I have implemented using Ed Donner's course - On my own

---

## File Overview & Problem Statement

### 1. `code_explainer.ipynb`
* **High-Level Overview:** An interactive Gradio web application integrated with OpenRouter/Groq LLM APIs that takes a code snippet in one programming language and explains it tailored to a user's preferred language of expertise.
* **What it Solves:** Helps developers and students understand code snippets written in unfamiliar programming languages by translating concepts into terms and patterns from a language they already know well.

---

### 2. `general_tool_simulator.ipynb`
* **High-Level Overview:** A Gradio chatbot powered by Groq's function calling capabilities, connected to local Python utility functions for precise text analysis.
* **What it Solves:** Overcomes LLM limitations in exact counting and quantitative reasoning by dynamically delegating character and word count queries to deterministic function tools rather than relying on model generation.

---

### 3. `jokes_scrapper.ipynb`
* **High-Level Overview:** An automated scraper and content generator that extracts text from any given web URL using BeautifulSoup and prompts an LLM to craft targeted, original comedy.
* **What it Solves:** Automates context-aware content generation by transforming raw webpage content into grounded observational humor and clean, structured joke lists.

---

### 4. `multichat_orcehstrator.ipynb`
* **High-Level Overview:** A multi-agent conversation simulator that orchestrates multi-turn group discussions among three distinct AI personas (Alex, Raghav, and Harish), tracking shared dialogue history.
* **What it Solves:** Simulates collaborative brainstorming and multi-perspective discussion dynamics by having specialized personas synthesize ideas, analyze practical implementations, and ask insightful questions in turn.

---

### 5. `pipeline_orchestrator.ipynb`
* **High-Level Overview:** A multimodal orchestration workflow combining Hugging Face pipelines and Diffusers to generate text, synthesize speech audio, and render generated images.
* **What it Solves:** Demonstrates end-to-end multimodal AI orchestration by turning a simple text prompt into generated text content, spoken audio output, and dynamic visual assets within a single pipeline.

---

### 6. `problem_job_evaluator.ipynb`
* **High-Level Overview:** An automated hiring assessment tool using web scraping and LLM evaluation within a Gradio interface.
* **What it Solves:** Streamlines technical candidate evaluation by scraping a candidate's online portfolio, evaluating their skills against a specific business problem, and delivering structured pros, cons, and hiring recommendations for decision-makers.
