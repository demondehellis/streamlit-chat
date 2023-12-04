## Overview
This application integrates OpenAI's GPT-4 model into a chat interface created using Streamlit. 
It allows users to interact with the GPT-4 model by sending messages and receiving responses in a conversational format.

## Features

   - Chat Interface: Utilizes Streamlit for a smooth and responsive chat experience.
   - OpenAI GPT-4 Integration: Seamlessly integrates OpenAI's GPT-4 model for generating conversational responses.

## Running app in a Docker Container

1. **Set Environment Variables on Your Host:**
   Set `OPENAI_API_KEY` and `OPENAI_MAX_TOKENS` as environment variables on your host machine.

2. **Build the Docker Image:**
   ```
   docker-compose build
   ```

3. **Run the Docker Container:**
   ```
   docker-compose up
   ```

   This will pass the `OPENAI_API_KEY` and `OPENAI_MAX_TOKENS` environment variables from your host to the Docker container.

4. **Access the App:**
   Open your web browser and go to `http://localhost:8501`. The Streamlit app should be running there.
