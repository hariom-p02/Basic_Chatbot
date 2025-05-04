# Basic_Chatbot
A customer service chatbot built in Python with both rule-based logic and basic NLP-based intent classification using scikit-learn and python.


🛎️ Customer Service Chatbot A simple customer service chatbot built in Python, capable of answering basic user queries using both rule-based keyword matching and NLP-based intent classification with scikit-learn.

🔍 Features 🔹 Rule-based chatbot using keyword matching

🔹 NLP-enhanced chatbot using machine learning (Naive Bayes)

🔹 Handles queries like:

Greetings

Order status

Return/refund policies

Working hours

Contact information

Farewells

🔹 Easily extendable with more intents and responses

🔹 Fully runnable in Google Colab

🧠 Technologies Used Python 3

Scikit-learn (CountVectorizer, MultinomialNB)

NLP basics (text classification)

Google Colab (recommended for running)

📁 Project Structure

chatbot/ ├── rule_based_chatbot.ipynb # Rule-based intent matching ├── nlp_based_chatbot.ipynb # NLP-based classifier chatbot ├── README.md # Project documentation

🚀 How to Run (Google Colab) Open Google Colab

Copy-paste the code blocks from either chatbot variant:

Rule-based chatbot

NLP-based chatbot

Run each code cell one-by-one

Interact with the chatbot in the notebook

✨ Example Interaction pgsql Copy Edit Customer Service Bot: Hi there! Type 'exit' to end the chat. You: hi Customer Service Bot: Hello! How can I assist you today? You: when do you close? Customer Service Bot: Our working hours are from 9 AM to 6 PM, Monday to Friday. You: refund request Customer Service Bot: Our return policy allows returns within 30 days of delivery. You: exit Customer Service Bot: Thank you for reaching out. Have a great day! 📌 Future Improvements Add intent classification using deep learning (e.g. BERT)

Build a Streamlit or Flask web interface

Integrate with real customer support APIs or databases

Add speech-to-text and text-to-speech capabilities.
