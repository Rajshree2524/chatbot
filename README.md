https://rajshree2524.github.io/chatbot/
Chat Bot - Hungry Nerds
Introduction
This repository contains the code for creating a Chat Bot called "Hungry Nerds." The Chat Bot is built using Natural Language Processing (NLP) techniques to understand and respond to user queries and requests.

Natural Language Processing (NLP)
NLP is a subfield of artificial intelligence that focuses on the interaction between computers and human languages. It enables the Chat Bot to understand user input in a more human-like manner, allowing for more natural and contextually relevant responses.

Dialogflow
To implement the Chat Bot's NLP capabilities, we used Dialogflow, a powerful NLP platform by Google. Dialogflow helps in creating intents, defining contexts, and handling user queries through fulfillment and webhooks.

Intents: Intents represent different types of user queries and actions that the Chat Bot needs to understand and respond to. We created various intents to handle different user requests, such as ordering food, checking the menu, or getting assistance.

Contexts: Contexts help the Chat Bot maintain conversational context, making the conversation flow more coherent and meaningful. We utilized contexts to keep track of the user's ongoing requests and information.

Fulfillments and Webhooks: Fulfillments allow the Chat Bot to take actions based on user queries. We used webhooks to connect Dialogflow to our Python backend, allowing the Chat Bot to process user requests and interact with the database.

Backend - Python, FastAPI, and MySQL
We built the backend of the Chat Bot using Python and the FastAPI framework, which is an efficient and modern web framework. FastAPI provided the necessary tools to handle incoming requests from Dialogflow and respond appropriately.

To manage and store the data, we integrated MySQL as the database. The Chat Bot relies on MySQL to store information such as the menu items, user orders, and other relevant data.

Website - GitHub Pages, HTML, and CSS
For the frontend part, we created the "Hungry Nerds" website using HTML and CSS. GitHub Pages allowed us to host the website and make it accessible to users.

Integration
Finally, we integrated the Dialogflow demo into the website. Users can now interact with the Chat Bot directly on the website, placing food orders, checking the menu, and getting assistance through natural language queries.
