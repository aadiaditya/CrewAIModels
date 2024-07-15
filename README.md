# Blog Content Creation using CrewAI and YouTube

This repository demonstrates how to use CrewAI to automate the process of researching and writing blog content based on YouTube videos. The project leverages AI agents to extract information from specified YouTube channels and generate compelling blog posts.

## Features

- **Automated Research**: Uses an AI agent to extract relevant information from YouTube videos.
- **Content Writing**: Another AI agent creates engaging blog content based on the extracted information.
- **Task Management**: Sequential execution of research and writing tasks.
- **Enhanced Feedback**: Provides detailed feedback and output customization.

## Setup

### Prerequisites

- Python 3.7 or later
- CrewAI
- OpenAI API Key
- YouTube Data API Key

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/blog-content-creation.git
    cd blog-content-creation
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    Create a `.env` file in the root directory and add your API keys:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    OPENAI_MODEL_NAME=gpt-4-0125-preview
    ```

## File Structure

- `agents.py`: Defines the research and writing agents.
- `crew.py`: Sets up the CrewAI task execution process.
- `tasks.py`: Defines the specific tasks for research and writing.
- `tools.py`: Configures the YouTube channel search tool.

