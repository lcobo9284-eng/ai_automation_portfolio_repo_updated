# RAG Knowledge Ingestion System

## Project context

This system was designed to transform documents, audio, and video files into searchable knowledge for AI assistants. The workflow connected cloud storage, content extraction, transcription support, embedding generation, vector database storage, and operational tracking.

## Problem

Teams often store valuable knowledge in files that are difficult for AI assistants to use directly. Documents may be scattered across folders, videos require transcription, and processed content needs to be chunked, embedded, and stored with enough context to support later retrieval. Without an automated ingestion process, knowledge bases become slow to update and hard to maintain.

## Approach

The automation was designed as a controlled ingestion pipeline. Files were retrieved from Dropbox, processed depending on their type, converted into text when necessary, split into smaller chunks, transformed into embeddings, and inserted into Pinecone. Tracking tools such as Airtable or Google Sheets helped keep visibility over processed content and reduce duplicate work.

The system used n8n as the orchestration layer, Dropbox as a file source, AssemblyAI related transcription logic for media content, OpenAI embeddings, Pinecone for vector storage, and code nodes for data preparation and workflow control.

## Solution

The final workflow created a repeatable path for turning files into retrievable knowledge. It allowed documents and media content to move from storage into a vector database through a structured process. This made it easier for downstream AI assistants to retrieve relevant context rather than relying only on generic model knowledge.

## My contribution

I developed and maintained ingestion logic, configured file processing steps, supported vector database insertion, worked through file format issues, adjusted code nodes, and improved tracking so the team could understand what content had been processed and where it was stored.

## Impact

The system improved the maintainability of knowledge bases by reducing manual ingestion work. It also created the foundation for retrieval based assistants that could respond using organization specific content rather than disconnected or outdated information.

## Public note

This public version does not include original files, transcripts, private documents, client data, credentials, API keys, original prompts, or production workflow exports.
