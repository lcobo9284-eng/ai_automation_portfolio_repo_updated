# Voice Assistant and RAG Bot

## Project context

This project focused on a Telegram based assistant capable of receiving text and voice messages, converting voice input into text, retrieving relevant knowledge from a vector database, and returning AI assisted responses through a messaging interface.

## Problem

Users do not always want to interact with assistants through typed messages. Voice input creates a more natural experience, but it also adds complexity. The workflow must detect the content type, download the audio file, transcribe it, route the text into the assistant, retrieve context from a knowledge base, generate a response, and handle failures without breaking the user experience.

## Approach

The workflow separated message handling into clear stages. It first identified whether the user submitted text or voice. For voice messages, the system downloaded the audio and converted it into text. The resulting message was then used to query a vector database, retrieve relevant context, and produce a response through an AI model. Logging and notification steps were included to support monitoring and troubleshooting.

The system used n8n, Telegram, OpenAI models, Pinecone, embeddings, Google Sheets or Slack support, JSON mappings, and conditional routing.

## Solution

The final assistant created a more flexible interaction model by supporting both text and voice. The user could ask a question in a natural way, while the workflow handled transcription, retrieval, and response generation behind the scenes. The use of a vector database allowed the assistant to respond with context from the uploaded knowledge base.

## My contribution

I supported message routing logic, voice processing, retrieval architecture, AI response generation, testing, error handling, and troubleshooting. I also worked on making the workflow understandable and maintainable across several connected components.

## Impact

The project demonstrated how a messaging assistant can become more useful when it combines voice input with retrieval based context. It reduced friction for users and showed how RAG systems can be embedded inside practical communication channels.

## Public note

This case study excludes bot tokens, user messages, private knowledge base content, credentials, API keys, raw workflow exports, and internal operational data.
