
# Scam Message Identifier

## Project Overview

Scam Message Identifier is an AI-powered application designed to identify suspicious and fraudulent messages using a locally running Large Language Model (LLM).

The application allows users to paste suspicious messages and investigate potential scam indicators. It uses Ollama to analyze the message and provide insights into possible warning signs.<img width="1782" height="835" alt="Screenshot 2026-10-30 144443" src="https://github.com/user-attachments/assets/c850c49e-01fb-498c-9803-1667547b1e2f" /><img width="1372" height="812" alt="Screenshot 2026-10-30 144551" src="https://github.com/user-attachments/assets/6843d29d-fb38-4a03-ab51-f06a9e5dd6f8" />



## Features

* **Message Analysis:** Analyze suspicious SMS messages and text content.
* **AI-Powered Investigation:** Uses a locally running LLM for message analysis.
* **Scam Detection:** Identifies suspicious phrases and potential scam indicators.
* **Warning Signs:** Highlights possible red flags in messages.
* **Simple Interface:** Easy-to-use interface built with Streamlit.
* **Local Processing:** Uses Ollama for local AI model execution.

## Technologies Used

* Python
* Streamlit
* Ollama
* Large Language Models (LLM)



## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/aarthy2411/Scam-message-investigator.git
```

### 2. Navigate to the Project Folder

```bash
cd Scam-message-investigator
```

### 3. Install Dependencies

```bash
py -m pip install -r requirements.txt
```

### 4. Install and Configure Ollama

* Install Ollama on your computer.
* Download the language model configured in the project.
* Ensure the Ollama service is running before starting the application.

### 5. Run the Application

```bash
py -m streamlit run app.py
```

The application will open in your web browser.

## How It Works

1. Open the Scam Message Identifier application.
2. Paste a suspicious message into the text area.
3. Click the **Investigate Message** button.
4. The message is sent to the locally running Ollama service.
5. The AI model analyzes the message.
6. Review the analysis and identified warning signs.

## Example Input

```text
URGENT! Your bank account will be blocked today!

Congratulations! You have won ₹50,000
in a special reward program.

Click the link below to claim your prize
immediately.
```

## Expected Outcome

The application investigates the message for potential scam indicators, such as:

* Urgent or threatening language.
* Unexpected prize announcements.
* Suspicious links.
* Requests for personal information.
* Misleading reward claims.

## Project Objective

The main objective of this project is to help users recognize potentially fraudulent messages and improve awareness of online scams through AI-powered message analysis.

## Future Enhancements

* Support for multiple languages.
* Message history and analysis reports.
* Improved scam detection accuracy.
* Additional suspicious message detection techniques.

## Author

**Aarthy V**


