# FAQ Chatbot

This project is being developed as Task 2 of my CodeAlpha Artificial Intelligence Internship.

The aim is to build a simple chatbot that answers common questions about an online shopping store. The chatbot will compare the user’s question with a collection of saved FAQs and return the most relevant answer.

## Planned Features

- Simple chat interface
- Frequently asked questions stored in a separate file
- Text processing using NLP techniques
- Question matching using TF-IDF and cosine similarity
- Relevant chatbot responses
- A fallback response when no suitable answer is found

## Technologies

- Python
- Streamlit
- scikit-learn
- Natural Language Processing
- TF-IDF
- Cosine similarity

## How It Will Work

The user will enter a question in the chatbot interface. The application will compare that question with the saved FAQ questions using TF-IDF and cosine similarity.

The answer linked to the most similar question will be displayed. When the similarity score is too low, the chatbot will ask the user to rephrase the question.

## Planned Project Structure

```text
.
├── app.py
├── faqs.json
├── requirements.txt
├── README.md
└── .gitignore
```

## Project Status

The project is currently under development.

## Author

**Shayan Akbar**

Developed as part of the CodeAlpha Artificial Intelligence Internship.
