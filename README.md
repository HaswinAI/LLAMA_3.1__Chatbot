# 🦙 Coder Connects LLAMA 3.1 Chatbot
A user-friendly chatbot interface built with Streamlit and powered by the Groq API using the LLAMA 3.1 model. This chatbot provides intelligent and conversational assistance for your needs.

🚀 Features
Real-time conversational interface using the Groq API.
Streamlit-powered UI for seamless interaction.
Persistent chat history for a smooth user experience.
🛠️ Installation
Prerequisites
Python 3.8 or higher
An API key for the Groq platform
Steps
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/llama-chatbot.git
cd llama-chatbot
Create a virtual environment and activate it:

bash
Copy code
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Add your Groq API key:

Create a config.json file in the src/ directory:
json
Copy code
{
    "GROQ_API_KEY": "your_groq_api_key_here"
}
Run the application:

bash
Copy code
streamlit run src/app.py
📂 Project Structure
plaintext
Copy code
.
├── src/
│   ├── app.py            # Main application script
│   ├── config.json       # Configuration file for API keys
├── requirements.txt      # List of dependencies
├── README.md             # Project documentation
🐍 Usage
Run the application as described above.
Open your browser and navigate to the Streamlit app URL (typically http://localhost:8501).
Interact with the chatbot by entering your queries in the input box.
🔧 Troubleshooting
JSONDecodeError:

Ensure the config.json file exists and contains valid JSON.
Example content:
json
Copy code
{
    "GROQ_API_KEY": "your_groq_api_key_here"
}
ModuleNotFoundError:

Verify you have installed all dependencies using:
bash
Copy code
pip install -r requirements.txt
Groq Client Initialization Error:

Confirm your API key is valid and has the necessary permissions.
🤝 Contributing
Feel free to submit issues or pull requests to improve this project. All contributions are welcome!

📜 License
This project is licensed under the MIT License.
