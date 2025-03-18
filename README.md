# LangChain-Based Pipelines

## Overview
This project demonstrates various **LLM-powered pipelines** using **LangChain**. It includes implementations of different **LLM chain architectures** for tasks such as generating business names, slogans, and historical data.

## Features
- **Simple Sequential Chain:** Processes inputs sequentially to generate structured responses.
- **Sequential Chain:** Connects multiple LLM calls, allowing information from previous steps to be used.
- **MapReduce Chain:** Breaks down tasks into smaller chunks, processes them individually, and combines results.
- **Business Name Generator:** Uses OpenAI's API to suggest business names and slogans.
- **Historical Data Retrieval:** Fetches relevant data based on user queries.

## Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/langchain-pipelines.git
   cd langchain-pipelines
   ```
2. **Create a Virtual Environment (Optional but Recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the main script to test different pipelines:
```sh
python lang_chains.py
```

Modify `lang_chains.py` to test different chain types and customize input prompts.

## Technologies Used
- **Python**
- **LangChain**
- **OpenAI API**
- **LLM-Based Processing**



