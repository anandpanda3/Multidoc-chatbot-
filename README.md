

# Multidoc Chatbot Application

This project is a chatbot application built with Streamlit, leveraging Langchain and Hugging Face embeddings. The chatbot can answer user queries based on the provided documents. 

## Features

- Interactive chat interface using Streamlit.
- Conversational retrieval chain to handle queries.
- Memory buffer to retain conversation context.
- Supports PDF, text, and DOCX file formats for document loading.
- Utilizes Hugging Face embeddings for text understanding.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/streamlit-chatbot.git
    cd streamlit-chatbot
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    Create a `.env` file in the root directory and add your environment variables. For example:
    ```env
    YOUR_API_KEY=your_api_key_here
    ```

## Usage

1. **Run the application:**
    ```sh
    streamlit run app.py
    ```

2. **Upload documents:**
   The application supports PDF, text, and DOCX file formats. Upload your documents through the interface.

3. **Ask questions:**
   Type your questions in the text input box and submit to get responses based on the uploaded documents.

## Project Structure

- `app.py`: Main application file containing the Streamlit interface and chat logic.
- `requirements.txt`: File listing all the dependencies required for the project.
- `.env`: Environment file for storing sensitive information (not included in the repository for security reasons).

## Dependencies

- Streamlit
- Langchain
- Hugging Face Embeddings
- FAISS
- dotenv
- PyPDFLoader
- TextLoader
- Docx2txtLoader

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with your feature or bug fix:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or suggestions, feel free to reach out at anandpandacs@gmail.com
