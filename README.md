# Advanced RAG Q&A Chatbot with LangChain

This project implements a powerful Question-Answering chatbot using LangChain's Retrieval-Augmented Generation (RAG) concepts. The chatbot can process uploaded PDF documents, answer complex questions based on their content, and leverage advanced techniques like chains and retrievers.

**Key Features**

*   **PDF Document Processing:** Ability to upload and extract knowledge from PDF files.
*   **Retrieval-Augmented Generation (RAG):** Employs retrievers to access relevant information and chains to structure the question answering process.
*   **Streamlit Integration:** User-friendly web interface powered by Streamlit.
*   **LangChain:** Built on the flexible and powerful LangChain framework.
*   **OpenAI Integration (Optional):** Support for integrating OpenAI's language models like GPT-3.5.

**Prerequisites**

*   Python 3.x
*   A LangChain API Key (if specified in the code)
*   An OpenAI API Key (if you're using OpenAI models)

**Installation**

1.  Clone this repository:
    ```bash
    git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>
    ```
2.  Navigate to the project directory:
    ```bash
    cd <your-repo-name>
    ```
3.  Create a virtual environment (recommended):
    ```bash
    python -m venv env
    env\Scripts\activate  # For Windows
    source env/bin/activate  # For Linux/macOS
    ```
4.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

**Usage**

1.  **Environment Variables:**
    *   Create a `.env` file in the project root.
    *   Add the following, replacing placeholders with your actual keys:
        ```
        OPENAI_API_KEY=<your_openai_api_key>
        LANGCHAIN_API_KEY=<your_langchain_api_key>
        ```
    *   Load the environment variables using the `dotenv` library (already included in the code).

2.  **Start the Application:**
    ```bash
    streamlit run app.py 
    ```

3.  **Using the Web Interface**
    *   Open `http://localhost:8501` (or the provided Streamlit URL) in your web browser.
    *   Upload a PDF file.
    *   Type your question in the text box.
    *   Click "Submit" to get the answer.

**Customization**

*   **LLM Choice:** Modify the code to switch between OpenAI and Ollama language models.
*   **Embedding Techniques:** Experiment with other embedding providers.
*   **Streamlit Enhancements:** Add more interactive elements or styling to the web interface.

**Contributions**

This project welcomes contributions! Feel free to add features, fix bugs, or suggest improvements.

**License**

[Specify the license of your project, e.g., MIT, Apache 2.0, etc.]
