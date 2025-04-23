# Prompt Engineering with LangChain

This project explores **Prompt Engineering** using the [LangChain](https://github.com/langchain-ai/langchain) framework and OpenAI's language models. The goal is to build intelligent chains that take user input, apply tailored prompts, and generate useful language model outputs.

## 🧠 Features
- Simple LLMChain using LangChain
- Custom prompt template for concise answers
- Integration with OpenAI GPT models

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Prompt-Engineering-with-Langchain.git
cd prompt-engineering-langchain
```

### 2. Set Up Environment
Using Conda:
```bash
conda create -p prompt python=3.9 -y
conda activate ./prompt
```

### 3. Install Dependencies
```bash
pip install langchain openai python-dotenv
```

### 4. Add Your OpenAI API Key
Create a `.env` file:
```bash
echo "OPENAI_API_KEY=your-api-key" > .env
```
Or set it directly in the script using `os.environ`.



## 📄 File Structure
```
├── main.py                 # Main script with LLMChain logic
├── README.md               # Project overview and setup guide
└── .env                    # Your OpenAI API key (excluded from version control)
```

## 📌 Example Prompt
```
Question: What is LangChain and how is it used in prompt engineering?
Answer: LangChain is a framework for developing applications powered by language models. It helps structure prompts, connect chains, and manage memory and tools effectively.
```

## 📫 Contact
For questions or contributions, feel free to reach out!

---

