1. Cloned the Repository: We cloned the sample application's repository from GitHub using the git clone command.

2. Created .env File: In the docker-genai directory, we created a .env file and specified our API keys for both OpenAI and Pinecone, following the example provided in the .env.example file.

3. Ran docker-compose up: We changed directory to the docker-genai directory and ran the docker compose up command in the terminal. This command started the Docker containers defined in the docker-compose.yaml file, including the yt-whisper and dockerbot services.

4. Accessed Streamlit Apps: After the containers started successfully, we accessed the Streamlit apps provided by both services in our web browser using the URLs provided in the terminal output.

5. Observed Processing: We observed that the yt-whisper service was processing YouTube videos, logging information such as video URLs, file sizes, and file names as it processed them
