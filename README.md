## Youtube video and Website URL Content summarization GenAI app

This project is a Text Summarizer Application  built using LangChain, Streamlit, and the Groq API. It allows users to summarize content from YouTube videos or website URLs by leveraging the Gemma2-9b-It model via Groq's API. Here's a concise summary of the project:

### Purpose:
The application provides a user-friendly interface to summarize lengthy content from YouTube videos or websites into a concise 500-word summary.

### Key Features:

* Input: Users can input a YouTube video URL or a website URL.

* Validation: The app validates the URL and ensures the Groq API key is provided.

* Content Loading:

    1. For YouTube videos, it uses YoutubeLoader to extract transcript data.

    2. For websites, it uses UnstructuredURLLoader to fetch and process content.

* Summarization: The load_summarize_chain function from LangChain, combined with a custom prompt, generates a summary using the Gemma2-9b-It model.

* Output: The summarized content is displayed to the user via the Streamlit interface.

### Technologies Used:

* LangChain: For chaining prompts, loading content, and summarizing.

* Streamlit: For building the web interface.

* Groq API: To access the Gemma2-9b-It model for summarization.

* YouTubeLoader & UnstructuredURLLoader: For extracting content from YouTube and websites.

### Challenges Addressed:

* Handling different types of URLs (YouTube vs. websites).

* Ensuring secure and efficient content loading.

* Providing a clean and intuitive user interface.

### Outcome:
* The application successfully summarizes content from diverse sources, making it a useful tool for quickly extracting key information from videos or web pages.

This project demonstrates proficiency in LangChain, API integration, web development with Streamlit, and natural language processing for summarization tasks.