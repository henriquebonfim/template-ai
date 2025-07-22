# template-ai

A simple chatbot web application built in Python and Node.js that connects to a local LLM service (llama.cpp) to provide AI-powered responses.

## Environment Variables

The application uses the following environment variables defined in the `.env` file:

- `AI_MODEL_URL`: The base URL of the LLM API
- `LLM_MODEL_NAME`: The model name to use

To change these settings, simply edit the `.env` file in the root directory of the project.

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/henriquebonfim/template-ai
   cd ai-templates
   ```

2. Run the application using the script:
   ```bash
   ./run.sh
   ```

3. Open your browser and visit the following links:

   http://localhost:8081 for the GenAI Application in Python

   http://localhost:8082 for the GenAI Application in Node

## Requirements

- Docker and Docker Compose
- Local LLM server

If you're using a different LLM server configuration, you may need to modify the`.env` file.
