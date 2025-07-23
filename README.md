# AI Agent for E-commerce Data Question Answering

This project implements an AI-powered agent that can answer questions about e-commerce product sales data using natural language 
The agent enables users to ask any question about their sales and ad data. It uses an LLM (e.g., Gemini) to translate plain-language questions into SQL, executes them on the datasets, and returns clear, human-readable answers

Loads Excel data into Pandas, then into a SQLite database.

The LLM receives your question and data schema, and generates a safe SQL query.

The agent executes the SQL and formats the result.
