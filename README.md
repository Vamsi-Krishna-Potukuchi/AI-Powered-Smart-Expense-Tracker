# AI-Powered Smart Expense Tracker

## Overview

AI-Powered Smart Expense Tracker is a full-stack personal finance management application built using the MERN Stack. It enables users to securely manage income and expenses, categorize transactions, view financial summaries, and analyze spending through interactive dashboards.

The application also integrates an AI-powered financial assistant using LangChain, the open-source Llama 3 model through Ollama, and Retrieval-Augmented Generation (RAG). The assistant uses ChromaDB-based semantic retrieval to answer natural-language questions about users’ financial records and provide personalized spending insights.

## Features

- Secure user registration and login using JWT authentication
- Password hashing using bcrypt
- Protected routes and user-specific financial data
- Add, update, and delete income transactions
- Add, update, and delete expense transactions
- Categorize income and expense records
- Interactive dashboard with financial visualizations
- Income-versus-expense comparison charts
- Display total income, total expenses, and current balance
- Responsive user interface
- Secure transaction storage using MongoDB
- AI-powered financial assistant
- Natural-language queries about financial records
- Retrieval-Augmented Generation using LangChain
- ChromaDB-based vector storage and semantic retrieval
- Local Llama 3 model execution through Ollama
- Personalized spending summaries and financial insights

## Tech Stack

### Frontend

- React.js
- HTML
- CSS

### Backend

- Node.js
- Express.js
- Python
- Flask

### Database

- MongoDB
- ChromaDB

### AI/ML

- LangChain
- Llama 3
- Ollama
- Retrieval-Augmented Generation (RAG)

### Authentication

- JWT
- bcrypt

## AI Assistant Workflow
- The user asks a question through the React interface.
- The backend verifies the user’s JWT token.
- Relevant financial transaction data is obtained.
- Transaction information is converted into searchable vector representations.
- ChromaDB retrieves relevant transaction records.
- LangChain prepares a prompt using the retrieved financial context.
- Llama 3 processes the prompt through Ollama.
- The generated response is returned to the React interface.
- The user receives a personalized financial answer.

## Example Queries
How much did I spend on food recently?

What was my highest expense category?

Show me my recent shopping transactions.

How much did I spend this month?

What are my major spending patterns?

## Future Enhancements
- Automatic Transaction Detection: Extract transaction details such as amount, merchant, date, and transaction type from bank SMS notifications or uploaded bank statements to reduce manual data entry.
- Smart Transaction Categorization: Automatically classify transactions into categories such as food, travel, shopping, bills, and entertainment using AI-based text analysis.
- Bank and Payment Account Integration: Integrate with supported banking or payment services to securely synchronize financial transactions in real time.
- Monthly Budget Planning: Allow users to set category-wise budgets, track spending limits, and receive alerts when expenses approach or exceed a budget.
- AI-Powered Financial Forecasting: Analyze historical spending patterns to estimate future expenses, predict monthly savings, and identify potential overspending.
- Personalized Financial Recommendations: Provide AI-generated suggestions for reducing unnecessary expenses, improving savings, and achieving financial goals.
- Automated Reports and Notifications: Generate periodic financial reports and send reminders or alerts for recurring payments, unusual transactions, and budget limits.
- Secure Data Import and Export: Support importing transactions from CSV or bank statements and exporting financial reports in PDF or Excel format.

