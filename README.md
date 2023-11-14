## Custom-Ai-Agent
Custom Ai Agent using OpenAI, Langchain, streamlit, wikipedia.

## Overview

This project is a Streamlit web app powered by OpenAI's GPT language model. It allows users to generate YouTube video titles and scripts based on a given topic. The app utilizes langchain's prompt templates, chains and memory mechanisms and Wikipedia API to enhance the quality and coherence of generated content.

## Prerequisites

- Python
- API key from OpenAI (stored in `apikey.py`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/tjdharani/Custom-Ai-Agent
    cd Custom-Ai-Agent
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up the OpenAI API key:

    - Create a file named `apikey.py` in the project root.
    - Add your OpenAI API key to `apikey.py`:

        ```python
        apikey = "your-api-key-here"
        ```

## Usage

1. Run the app:

    ```bash
    streamlit run app.py
    ```

2. Open your web browser and navigate to the provided URL. http://localhost:8501

3. Enter a topic in the text input box and let the app generate YouTube video titles and scripts for you.

## Configuration

- Adjust the `temperature` parameter in the OpenAI language model initialization for different levels of creativity and randomness in the generated content.


## Acknowledgments

- This project uses the [Streamlit](https://www.streamlit.io/) library for creating the web interface.
- [OpenAI](https://openai.com/) provides the GPT language model used for content generation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
