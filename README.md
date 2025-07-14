# Chatbot_AI
This project is an AI-powered car sales assistant built using LangGraph, Groq, and Python. It acts as a virtual car salesperson that can provide detailed information about specific Toyota models 

# 🚗 AI Car Sales Assistant

This project is an AI-powered car sales assistant built using [LangGraph](https://github.com/langchain-ai/langgraph), [Groq](https://groq.com/), and Python. It acts as a virtual car salesperson that can provide detailed information about specific Toyota models such as Camry, Corolla, RAV4, Highlander, Sienna, and Tundra.

## 🧠 Features

- Interacts with users using natural language
- Supports six Toyota car models
- Uses Groq’s ultra-fast `llama-3.1-8b-instant` model
- Friendly, convincing salesperson persona
- Easily extendable with more car models or tools

## 📦 Tech Stack

| Component | Description |
|----------|-------------|
| **LangGraph** | Agent framework for managing LLM workflows |
| **Groq** | Backend LLM provider (LLaMA 3.1 8B Instant) |
| **Python** | Core programming language |
| **dotenv** | For environment variable management |
| **IPython** | Used to display formatted markdown responses |

## 🚀 How to Run

# 1. Clone this repository:
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

## 2  pip install -r requirements.txt
 cd your-repo-name

## 3 Install the required packages:

## 4 pip install -r requirements.txt
Set your environment variable:

Create a .env file in the root directory:

GROQ_API_KEY=your_groq_api_key_here

## Run the script:

python your_script_name.py
Example usage:
run_agent("i want to buy tundra")

🧪 Example Output
Input: i want to buy tundra
Output: A full description of the Toyota Tundra including engine options, towing capacity, off-road features, reliability, and resale value.



---




