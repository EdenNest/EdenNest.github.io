# Chatbot Website

This is the repository for the website that integrates a chatbot into a Notion page. The chatbot's backend is hosted on Render, while the frontend is embedded in Notion using HTML, CSS, and JavaScript.

You can checkout the details of implementation and how to implement this for you own website [here](https://github.com/soheilzi/AI-assistant-backend-python)

## Project Overview

- **Frontend**: The website's UI is built on Notion, with a chatbox embedded via HTML and JavaScript. Since Notion doesn't support direct integration of JavaScript and HTML, the chatbox is embedded using an iframe.
  
- **Backend**: The chatbot backend is built using the Flask framework. It processes requests sent from the frontend, communicates with OpenAI's GPT-4-mini model, and returns responses. This backend is hosted on Render, which handles server uptime and scaling.

- **API Integration**: The chatbot backend uses OpenAI’s GPT-4-mini API for natural language processing. The OpenAI API is used to send and receive messages to generate conversational responses from the chatbot.

- **Hosting**: The frontend of the website is hosted on GitHub Pages, while the backend is hosted on Render.

## Key Features

1. **Notion-Integrated Chatbox**: The website provides a user-friendly chatbox that is fully integrated into a Notion page, allowing seamless communication between the user and the chatbot.
  
2. **OpenAI GPT-4-mini Integration**: The chatbot is powered by OpenAI's GPT-4-mini model, providing dynamic and intelligent responses based on user input.

3. **Flask-based Backend**: The backend is written in Python using Flask. It handles incoming chat requests from the frontend and forwards them to OpenAI's API for processing.

4. **Scalable Deployment**: The backend is deployed on Render, ensuring that the server can handle multiple requests and scale as needed.

## Customization

The chatbot's personality and behavior can be customized by adjusting the prompt sent to OpenAI's GPT-4-mini model. Additionally, the chatbox's appearance and functionality can be updated by modifying the HTML, CSS, and JavaScript files.

For more information on the backend, including setup instructions and code, visit the backend repository. You can also explore further customization options for both the frontend and backend to suit your needs.
