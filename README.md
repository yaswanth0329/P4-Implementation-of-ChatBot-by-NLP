P4-Implementation-Chatboy-by-NLP

This project demonstrates the implementation of an intelligent chatbot capable of understanding and responding to user queries using Natural Language Processing (NLP). The chatbot leverages tools like NLTK for preprocessing, Scikit-learn for machine learning, and Streamlit for an interactive user interface.




Features : 

Interactive Interface: Built with Streamlit for seamless user interactions.

Natural Language Processing: Preprocessing using NLTK (tokenization, stemming, and lemmatization).

Intent Classification: Logistic Regression for mapping user input to intents.

Response Generation: Contextually relevant responses selected from predefined data.

Conversation Logging: Logs user inputs and responses to a CSV file.

History Management: Allows users to review past conversations.




Tools and Technologies : 

Software Requirements :

Python: Programming language.

Streamlit: Framework for building the user interface.

NLTK: For natural language preprocessing.

Scikit-learn: For feature extraction and intent classification.


Hardware Requirements : 

Processor: Dual-core processor or higher.

RAM: 4GB or higher recommended.

Storage: Minimum 2GB free space.





Installation : 

1. Clone the repository:

git clone <repository-url>  
cd <repository-folder>


2. Install required libraries:

pip install -r requirements.txt


3. Download NLTK data:

import nltk  
nltk.download('punkt')


4. Run the application:

streamlit run app.py



File Structure : 

app.py: Main application file.

intents.json: Dataset containing predefined intents and responses.

chat_log.csv: Log file for saving user and chatbot conversations.

requirements.txt: List of dependencies.





How to Use : 

1. Run the application using Streamlit.


2. Use the text input box to enter your query.


3. View the chatbot’s response in real-time.


4. Access conversation history from the sidebar menu.






Future Enhancements : 

Support for multiple languages.

Emotion detection for empathetic responses.

Voice input and output integration.

Advanced machine learning models like Transformers for better accuracy.




Acknowledgments :

This project is built using open-source libraries and tools. Special thanks to the creators of Streamlit, Scikit-learn, and NLTK for their powerful functionalities.


