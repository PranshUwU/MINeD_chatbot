### MINeD Hackathon Chatbot Project
This project is a chatbot developed for the MINeD hackathon. The chatbot is designed to interact with users, answer questions, and provide relevant information based on uploaded documents.
It leverages various technologies such as Flask, OpenAI's GPT-3.5, PyMuPDF, easyOCR, and more to achieve its functionality.

## Files Included:
app.py: This file contains the main Flask application that serves as the backend for the chatbot. It handles file uploads, text extraction from various document formats, and question answering functionality.

index.html: This HTML file is used for rendering the user interface of the chatbot. It likely includes elements for uploading documents and displaying chat interactions.

style.css: The CSS file provides styles for the HTML elements, enhancing the visual presentation of the chatbot interface.

script.js: This JavaScript file may contain client-side scripts for handling user interactions on the chatbot interface, such as sending questions and displaying responses.

## Usage:
Running the Application:

Ensure you have all dependencies installed, including Flask, Flask-CORS, PyMuPDF, requests, dotenv, sentence-transformers, pptx, docx, textract, easyocr, and any others required.
Run app.py using Python to start the Flask server.
Uploading Documents:

Navigate to the chatbot interface (likely served at / endpoint).
Use the document upload feature to upload supported document types such as PDF, DOCX, TXT, TEX, or PPTX.
Asking Questions:

Once a document is uploaded, users can ask questions through the chat interface.
The chatbot will use OpenAI's GPT-3.5 to generate responses based on the uploaded document's content.
For questions related to the document, appropriate lines from the document will be included in the response.
Note:
Ensure you have set up environment variables, including OPENAI_API_KEY, to access the OpenAI API for question answering.
Additional configuration or modifications may be required based on specific deployment environments or use cases.
For any inquiries or issues, please contact the project developers.
