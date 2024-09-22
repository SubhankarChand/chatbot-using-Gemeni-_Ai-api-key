# Chatbot Using Gemini AI API Key

This project implements a chatbot using the Gemini AI API. By integrating the API into a Python application, this chatbot can engage in intelligent conversations, provide answers, and simulate human-like interaction.

## Features

- **AI-powered conversations**: Leverages the Gemini AI API to provide intelligent, context-aware responses.
- **Customizable interactions**: The chatbot can be adapted and extended for various use cases (customer support, personal assistants, etc.).
- **Simple integration**: Easily integrate the Gemini AI API into your Flask application.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- Flask (`pip install flask`)
- Requests library (`pip install requests`)

You will also need a valid Gemini AI API key. 

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/SubhankarChand/chatbot-using-Gemeni-_Ai-api-key.git
    cd chatbot-using-Gemeni-_Ai-api-key
    ```

2. **Install required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your Gemini AI API Key**:

    Open `config.py` and replace `YOUR_API_KEY` with your actual Gemini AI API key.

4. **Run the application**:

    ```bash
    python app.py
    ```

5. **Access the chatbot**:

    Open your browser and navigate to:

    ```
    http://127.0.0.1:5000
    ```



- **`templates/index.html`**: The frontend interface for interacting with the chatbot.
- **`app.py`**: Main Python script that handles the chatbot logic and API integration.
- **`config.py`**: This file contains the API key and any other configuration needed for the Gemini AI API.
- **`requirements.txt`**: Contains the list of required Python libraries to run the project.
- **`README.md`**: Project documentation (this file).

## Code Explanation

1. **API Integration**:
   - The Gemini AI API key is stored in `config.py`, and API calls are made using the `requests` library to handle interactions.
   
2. **Flask Application**:
   - The application uses Flask to serve the chatbot interface and manage incoming and outgoing messages.
   
3. **Frontend**:
   - The chatbot interface is a simple HTML page served via Flask, where users can input messages and receive responses.

## Example Output

Once the app is running, you can chat with the AI in real-time through a web interface. Type your message, and the chatbot will respond using Gemini AI's powerful language model.

## Contributing

Contributions are welcome! If you want to improve this project, feel free to fork the repository and submit a pull request.



### Author

Developed by [Subhankar Chand](https://github.com/SubhankarChand).


