# LangChain-Streamlit-RAG

This project provides a FastAPI interface to serve Ollama models. It allows other applications to send queries to the model and receive responses.

## Features

- **LangChain**: Manages and processes language models.
- **Ollama**: The core language model used for generating responses.
- **RAG**: RAG for pdf.

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/ersinaksar/LangChain-Streamlit-RAG.git
    cd serve-ollama-models
    ```

2. **Create a virtual environment and activate it:**

    ```sh
    python3 -m venv .venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Start the streamlit application:**

    ```sh
    streamlit run main.py 
    ```

## License

This project is licensed under the MIT License.