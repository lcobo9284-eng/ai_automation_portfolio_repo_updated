# Voice Assistant and RAG Bot

## Project summary

Implemented a Telegram based voice and text assistant that receives user messages, processes voice input, retrieves relevant context from a vector database, and generates AI assisted responses.

## Business challenge

Users needed an easier way to interact with a knowledge assistant without relying only on typed messages. Voice input, contextual retrieval, and response generation had to work together within a messaging interface.

## Solution approach

The workflow received Telegram messages, detected whether the input was text or voice, downloaded audio when needed, converted speech into text, retrieved relevant context from Pinecone, and produced a response through an AI model.

## Core capabilities

• Telegram message handling  
• Voice message processing  
• Audio to text conversion  
• Vector database retrieval  
• AI response generation  
• Slack or Google Sheets logging support  
• Error handling and workflow branching  

## Tools used

• n8n  
• Telegram  
• OpenAI models  
• Pinecone  
• Google Sheets  
• Slack  
• JSON  
• AI memory and retrieval components  

## My contribution

Supported the workflow design, message routing logic, voice processing flow, retrieval architecture, testing, and troubleshooting needed to make the assistant usable across text and voice interactions.

## Portfolio note

This case study is shared as documentation only and excludes any bot tokens, user messages, private knowledge base content, credentials, and production workflow files.
