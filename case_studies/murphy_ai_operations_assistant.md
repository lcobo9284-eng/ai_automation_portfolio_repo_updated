# Murphy AI Operations Assistant

## Project context

Murphy was a multi tool AI operations assistant designed to connect messaging channels, AI models, vector retrieval, workflow tools, and communication platforms. The system supported operational requests by interpreting user messages, retrieving context, calling specialized workflows, and returning useful responses through connected channels.

## Problem

Operational teams often need quick answers or actions from several systems. Without an assistant layer, users must move between tools, search for information manually, trigger workflows themselves, or ask technical team members for help. The challenge was to create an assistant that could receive natural language input and coordinate actions across different workflow tools.

## Approach

The architecture used a conversational AI layer connected to tools and knowledge sources. The assistant received messages through channels such as WhatsApp or Telegram, processed user intent, retrieved context from vector stores such as Supabase or Pinecone when needed, called specialized workflows, formatted the response, and delivered the output back to the user.

The system used n8n, OpenAI models, Supabase, vector stores, WhatsApp, Telegram, HTTP requests, AI agent tools, memory, JSON mappings, and response formatting logic.

## Solution

The final assistant acted as an operational coordination layer rather than a single purpose chatbot. It could connect user requests with internal workflows, knowledge retrieval, message handling, and response delivery. This made it easier to centralize small operational tasks and reduce the need for manual tool switching.

## My contribution

I contributed to workflow architecture, tool orchestration, response handling, retrieval logic, testing, troubleshooting, and coordination of the assistant across multiple connected workflows. I worked on the practical details that make an AI assistant usable in an operations environment, including routing, data formatting, and reliability.

## Impact

The project showed how a conversational assistant can become a functional operations interface when it is connected to workflow tools and knowledge sources. It helped reduce friction between user requests and backend automation processes.

## Public note

This public documentation excludes credentials, phone IDs, private user messages, internal knowledge base content, API keys, business instructions, original prompts, and raw workflow exports.
