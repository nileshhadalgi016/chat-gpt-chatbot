# ChatGPT Chatbot

This project is a simple chatbot application built using Streamlit and OpenAI's GPT-3.5-turbo. The chatbot can interact with users by generating responses based on the input provided.

## Features

- Interactive chat interface using Streamlit
- Integration with OpenAI's GPT-3.5-turbo model
- Chat history maintained throughout the session

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/nileshhadalgi016/chat-gpt-chatbot.git
    ```
2. Navigate to the project directory:
    ```sh
    cd chat-gpt-chatbot
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Set up your OpenAI API key in a `.env` file:
    ```
    OPENAI_API_KEY=your_openai_api_key
    ```
2. Run the Streamlit application:
    ```sh
    streamlit run chatbot.py
    ```

## How It Works

- The application loads environment variables and configures the OpenAI API.
- User inputs are sent to the OpenAI API to generate responses.
- The chat history is displayed using Streamlit's chat interface.

## Code Overview

- `chatbot.py`: The main application file that sets up the Streamlit interface, handles user inputs, and interacts with the OpenAI API.

## Example

![ChatGPT Chatbot](screenshot.png)

## License

This project is licensed under the MIT License.

---

Feel free to customize this README file further to fit your project's specific details and needs.
