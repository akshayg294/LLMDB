# Large Language Movie DataBase: Movie Query Made Simple

Welcome to LLMDB, an impressive demonstration of the capabilities of LangChain and LLMs in extracting information from graphs! We have developed a user-friendly application that empowers users to search for movie titles within the IMDB dataset graph or explore similar movies through natural language queries. And here's the best part: if the LLM doesn't have all the details, it will conduct a Google search first and then query the title in the database.

## Overview

The Graph Explorer of LLMDB utilizes advanced technologies in natural language processing and machine learning, namely LangChain and LLMs. This application incorporates a graph representation of the IMDB dataset, containing comprehensive information about movies, actors, directors, and more. By entering queries in natural language, such as "I want to see drama movies with Leonardo DiCaprio" or "Show me films directed by Christopher Nolan," users can retrieve relevant data from the graph using the LLM.

If the LLM is unable to provide a response, it will leverage the Google Search API to gather additional information, which will then be used to improve the search results.

## Features

- Explore movie titles within the graph
- Find similar movies using natural language queries
- Automatically perform a Google search to supplement missing information

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/akshayg294/LLMDB.git

```

2. Navigate to the frontend directory and install the required dependencies

```bash
cd frontend
npm install
```

3. Install the necessary dependencies for the backend

```bash
poetry install
```

4. Launch the frontend

```bash
npm run start
```

5. Set up the environment variables

```bash
export OPENAI_API_KEY=<your-openai-api-key>
export SERPAPI_API_KEY=<your-serpapi-api-key>
```

6. Start the backend

```bash
python3 backend/main.py
```

7. Open the application in your browser at http://localhost:3000
