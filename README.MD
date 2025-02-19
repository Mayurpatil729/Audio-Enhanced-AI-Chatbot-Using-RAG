<!-- @format -->

## Problem Overview

Audio-Enhanced Conversational AI Chatbot

People often consume a wealth of information via videos, webinars, and podcasts but lack efficient ways to interact with or query specific information within these media. The challenge lies in converting long-form audio or video content into an interactive experience, allowing users to ask questions and retrieve precise information from the content without manually searching or listening through the entire file.

### Problem Statement

Develop a tool that transforms video or audio content into an interactive, conversational experience by transcribing audio, processing content for context, and providing accurate, real-time answers to user questions.

1. Transcribing audio from YouTube videos.
2. Processing and organizing this content for effective retrieval.
3. Ceate Summary for entire transcript
4. Enabling users to query and receive accurate, context-based answers from the transcription using a language model.

### Project Setup

#### 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

#### 2. Create a Virtual Environment

```bash
conda create -p env python=3.10 -y
```

#### 3. Activate the Virtual Environment

```bash
conda activate env/
```

#### 4. Install Project Requirements

```bash
pip install -r requirements.txt
```

#### 5. Environment Variables

Create a .env file and add the required key-value pairs:

```bash
ASSEMBLY_AI_KEY = your_api_key
OPENAI_API_KEY = your_secret_key
```

#### 6. How to Run the Project

```bash
streamlit run app.py
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
