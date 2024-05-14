
---

# Chatbot Collection

This repository contains a collection of chatbots developed using frameworks from OpenAI, Nvidia, and Gemini. Each chatbot resides in its own directory with all necessary Python files and dependencies listed.

## Prerequisites

Before setting up the chatbots, make sure you have Python installed on your machine. Python 3.6 or higher is recommended. You can download it from [python.org](https://www.python.org/downloads/).

## Installation

Follow these steps to get the chatbots up and running:

### 1. Clone the Repository

Start by cloning this repository to your local machine:
```bash
git clone https://github.com/your-username/chatbot-collection.git
cd chatbot-collection
```

### 2. Set Up the Environment

It's recommended to create a virtual environment for each chatbot to manage dependencies effectively:
```bash
# Navigate to the chatbot's directory, for example, OpenAI Chatbot
cd pdf_bot_openai

# Create a virtual environment
python -m venv venv

# Activate the environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
```

Repeat these steps for each chatbot by navigating to their respective directories (`pdf_bot_gemini` and `pdf_bot_Nvidia`).

### 3. API Keys

Each chatbot may require an API key to interact with its respective service. Please obtain the necessary API keys from:

- [OpenAI API](https://beta.openai.com/signup/)
- [Nvidia API](https://developer.nvidia.com/)
- [Gemini API](https://www.geminicloud.ai/)

After obtaining the keys, add it in the python file where mentioned with a comment

### 4. Run the Application

With the environment set up and API keys in place, you can run each chatbot using Streamlit:
```bash
streamlit run pdf.py
```

## Usage

Once the application is running, access it through your web browser at `http://localhost:8501`. Interact with the chatbot via the user interface provided by Streamlit.

## Support

For support, contact [your-email@example.com]. Issues and pull requests are welcome on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to adjust the content to better fit your project's needs or specific details!
 
