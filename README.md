# Text Summariser

## Overview
Text Summariser is a Python-based application designed to generate concise summaries from longer text inputs. The project utilizes natural language processing techniques to identify and extract the most significant information, ensuring the essence of the text is retained in the summary.

## Features
- **Efficient Text Summarization**: Processes and summarizes lengthy texts accurately.
- **User-Friendly Interface**: Simple and intuitive interface for easy interaction.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Harshit787898/Text_Summariser.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Text_Summariser
    ```
3. Set up the virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
6. Install `spacy` and download the language model:
    ```bash
    pip install -U spacy
    python -m spacy download en_core_web_sm
    ```

## Usage
1. Run the application:
    ```bash
    python app.py
    ```
2. Open your web browser and navigate to `http://localhost:5000`.
3. Enter the text you wish to summarize and click on the "Summarize" button.

## Project Structure
- `app.py`: The main application script.
- `text_summary.py`: Contains the summarization logic.
- `templates/`: HTML templates for the web interface.
- `static/`: Static files (CSS, JS) for the web interface.
- `venv/`: Virtual environment directory.
- `__pycache__/`: Compiled Python files.

## Technologies Used
- **Python**: The core programming language.
- **Flask**: Web framework for building the application.
- **NLTK**: Natural Language Toolkit for text processing.
- **spaCy**: Library for advanced natural language processing.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
