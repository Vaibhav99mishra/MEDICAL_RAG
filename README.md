# AI Medical Assistant Chatbot

This project is an AI-powered medical assistant chatbot designed to analyze patient symptoms and provide preliminary assessments. The chatbot leverages OpenAI's GPT models, FAISS for similarity search, and a pre-trained embedding model for sentence encoding. This chatbot is not intended to replace professional medical advice but to assist users in understanding potential symptoms and health conditions.

## Features

- **Interactive Chatbot**: The chatbot greets users automatically and provides a conversational interface.
- **Symptom Analysis**: Processes user-provided symptoms and generates structured analysis, including:
  - Assessment
  - Potential Disorders
  - Symptoms
  - Recommendations
- **AI-Powered**: Utilizes OpenAI's GPT models for natural language understanding and response generation.
- **Efficient Search**: Employs FAISS for quick and accurate retrieval of relevant medical information.

## How It Works

1. **User Interaction**: The user describes their symptoms in a conversational interface.
2. **Symptom Processing**:
   - Retrieves relevant information using FAISS index.
   - Crafts a prompt for OpenAI GPT models.
3. **Response Generation**:
   - The chatbot provides a structured analysis of symptoms.
4. **Conversation History**: Maintains the chat history for a seamless user experience.

---

## Installation and Setup

### Prerequisites
- Python 3.8+
- OpenAI API Key
- Required Python packages (see below)

## Download Required Files

You can download the necessary data files for the chatbot from the following links:
- [med_assistant_db.csv](https://drive.google.com/file/d/1jXyewQlXCEusAdvmuHLCz--iPa7RnHrE/view?usp=drive_link)
- [med_assistant_index]([https://drive.google.com/your-link-here](https://drive.google.com/file/d/1YodGOKqif3l4KCemNXyABQNraH_k03Cd/view?usp=drive_link))


### Installation Steps
1. Clone the repository:

Install the required dependencies:

pip install -r requirements.txt

Ensure you have the necessary data files:

med_assistant_db.csv: A CSV file containing relevant medical data.
med_assistant_index: A FAISS index file for searching relevant medical information.
Run the application:


Prompts

# Relevant Prompts
These prompts simulate real medical concerns that the chatbot can analyze effectively:

"I am suffering from fever and a running nose."
"My stomach hurts, and I have been vomiting for two days."
"I feel dizzy and tired all the time."
"I have a persistent cough and difficulty breathing."
"My joints are painful and stiff, especially in the morning."

# Non-Relevant Prompts
These prompts are unrelated or ambiguous and are used to test the chatbot's ability to handle irrelevant inputs:

"Tell me a joke."
"What's the weather today?"
"Who won the game last night?"
"I am just testing this chatbot."
"I feel fine, but I am curious about how this works."


Project Structure
.
├── app.py                   # Main application script
├── requirements.txt         # List of required Python packages
├── med_assistant_db.csv     # CSV file containing medical data
├── med_assistant_index      # FAISS index for data retrieval
├── README.md                # Project documentation



# Usage Instructions
Start the chatbot by running the application.
The chatbot will greet you automatically and ask for symptoms.
Enter your symptoms in the input box.
The chatbot will analyze your input and provide:
An assessment of the symptoms.
Possible medical conditions.
Recommendations for further actions.

# Limitations
Not a Replacement for Medical Advice: This chatbot provides only preliminary assessments and should not be used as a substitute for professional medical advice.
Data Dependency: The quality of analysis depends on the underlying data and models.
Example Interaction
User: Hi, I am suffering from fever and running nose.


Chatbot:

Analysis:
Assessment: Based on the input provided, the patient is suffering from fever and a running nose. These symptoms commonly indicate an upper respiratory tract infection.
Potential Disorders: Common cold, flu.
Symptoms: Fever, running nose.
Recommendations:
Stay hydrated and rest.
Monitor symptoms and consult a healthcare provider if the condition worsens.


Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.


Contact
For any questions or support, please contact:

Name: Vaibhav Mishra
Email: mishra99vaibhav@gmail.com


---

### Key Additions
1. **Relevant and Non-Relevant Prompts**:
   - Helps users understand what kind of inputs work best with the chatbot.
2. **Installation Instructions**:
   - Detailed steps to set up and run the chatbot locally.
3. **Limitations Section**:
   - Clarifies that the chatbot is not a replacement for professional medical advice.







