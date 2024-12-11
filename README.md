# AVY

### Project Overview:

The Avy LLM Project aims to integrate a large language model (LLM) into a Learning Management System (LMS) to provide AI-powered, personalized learning experiences. The backend will focus on training the model using course-related data such as PDFs and video transcripts and will employ AI algorithms for real-time personalization of quizzes, tasks, and lessons.

The backend will interact with MongoDB for knowledge base storage, OpenAI for embeddings, and the Flask framework for API development. Additionally, AI algorithms will adjust course difficulty based on student progress and interactions.

### Requirements
This project uses several key libraries and tools, including:

**Python** (version 3.11.3)
**Flask** (3.1.0) For creating the backend APIs.
**Langchain** For processing course-related documents, especially PDFs and video transcriptions.
**OpenAI** For generating embeddings and using LLM APIs.
**Whisper** For transcribing audio from video lectures.
**MongoDB** v8.0.1 For storing the knowledge base.
**python-dotenv** To manage environment variables.# avy_llm_backend
