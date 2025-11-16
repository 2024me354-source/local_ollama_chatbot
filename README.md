# Local LLM Chatbot with TinyDolphin and Streamlit

This project is a **local AI chatbot** using a lightweight LLM called **TinyDolphin**, running via **Ollama**, with a **Streamlit** web interface.  
It allows you to chat with the model, view conversation history, and adjust response settings.

---

## Features

- **Local LLM**: Runs fully offline using TinyDolphin via Ollama.
- **Streamlit Interface**: Simple and interactive UI.
- **Conversation History**: Displays all previous messages in the session.
- **Live Streaming Responses**: Chatbot responds in real-time.
- **Reset Conversation**: Clear the chat history with one click.
- **Adjustable Parameters**: Control temperature, top-k, and top-p for response creativity.

---

## Demo

![Chatbot Screenshot](screenshot.png)

*Replace `screenshot.png` with your actual project screenshot.*

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/generative_ai_project.git
cd generative_ai_project
Install Python dependencies


python -m pip install --upgrade pip
python -m pip install -r requirements.txt



Make sure Ollama is installed and TinyDolphin model is pulled


ollama pull tinydolphin
ollama list


Running the Chatbot
Start the Streamlit app:
python -m streamlit run app.py



Browser will open automatically at http://localhost:8501.


Type messages in the input box and get responses from TinyDolphin.



Project Structure
generative_ai_project/
│── app.py                # Main Streamlit chatbot code
│── requirements.txt      # Python dependencies
│── screenshot.png        # Optional: Project screenshot


Notes


Ensure the Ollama server is running locally before using the chatbot.


The TinyDolphin model is lightweight, making it fast to run even on standard laptops.


Streamlit session maintains conversation history, which clears on reset or page refresh.



License
This project is open-source and free to use for educational purposes.

---

💡 **Tip:**  

- Add your actual screenshot in the repo and name it `screenshot.png`.  
- Replace the GitHub URL with your own repo link.  

---

If you want, I can also make a **slim “one-page version” README** that looks super clean for submission on GitHub and Medium/blog, keeping only essentials.  

Do you want me to do that?
