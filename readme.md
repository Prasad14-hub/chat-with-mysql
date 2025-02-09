# MySQL Python Chatbot using OpenAI GPT-4o LLM Model

This project contains code for building a natural language SQL chatbot using OpenAI's GPT-4o llm model! This project guides you through the development of a chatbot that can interpret natural language queries, generate SQL queries, and fetch results from a SQL database, all in an intuitive and user-friendly way. It utilizes the power of OpenAI's GPT-4o llm model, integrated with a Streamlit GUI for an enhanced interaction experience.

## Features of this chatbot
- **Natural Language Processing**: Uses GPT-4 to interpret and respond to user queries in natural language.
- **SQL Query Generation**: Dynamically generates SQL queries based on the user's natural language input.
- **Database Interaction**: Connects to a SQL database to retrieve query results, demonstrating practical database interaction.
- **Streamlit GUI**: Features a user-friendly interface built with Streamlit, making it easy for users of all skill levels.
- **Python-based**: Entirely coded in Python, showcasing best practices in software development with modern technologies.

## Brief Explanation of How the Chatbot Works

The chatbot works by taking a user's natural language query, converting it into a SQL query using OpenAI's GPT-4o llm model, executing the query on a SQL database, and then presenting the results back to the user in natural language. This process involves several steps of data processing and interaction with the OpenAI API and a SQL database, all seamlessly integrated into a Streamlit application.

Consider the following diagram to understand how the different chains and components are built:

![Chatbot Architecture](./docs/mysql-chains.png)

