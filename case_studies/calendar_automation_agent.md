# Calendar Automation Agent

## Project context

This automation was created to support scheduling operations through an AI assisted calendar workflow. The system was intended to interpret natural language requests and coordinate calendar actions such as creating events, adding attendees, retrieving access tokens, managing meeting details, and deleting events when needed.

## Problem

Calendar management can look simple from the outside, but operationally it involves many small decisions. The system must understand dates, attendees, meeting topics, time ranges, locations, meeting links, and the intended action. When these details are handled manually, the process becomes repetitive and prone to errors, especially when multiple tools are involved.

## Approach

The workflow used an AI agent to interpret the request and delegate the correct action to specialized sub workflows. Structured output parsing was used to extract fields such as topic, start date, end date, attendees, location, meeting ID, and password. Separate workflows handled access token retrieval, event creation, event deletion, and meeting coordination.

The architecture relied on n8n, OpenAI models, Microsoft Outlook related integrations, Zoom related tools, HTTP requests, structured parsers, and JSON mappings to pass validated information between steps.

## Solution

The final system worked as a task oriented calendar assistant. Instead of requiring the user to manually fill every field, the workflow interpreted the request, produced structured data, executed the correct calendar action, and returned a clear result. The use of specialized sub workflows made the system easier to maintain because token retrieval, creation logic, and deletion logic were separated.

## My contribution

I supported the workflow architecture, natural language interpretation logic, structured output design, tool orchestration, API based actions, testing, and troubleshooting. My work focused on making the workflow reliable enough to convert user intent into calendar operations without losing control over the required fields.

## Impact

The automation reduced manual scheduling effort and created a more consistent way to handle calendar tasks. It also demonstrated how AI can be used responsibly in operational workflows when paired with structured outputs, clear integrations, and defined execution paths.

## Public note

This case study excludes access tokens, calendar IDs, private attendees, meeting URLs, credentials, original workflow exports, and any private scheduling data.
