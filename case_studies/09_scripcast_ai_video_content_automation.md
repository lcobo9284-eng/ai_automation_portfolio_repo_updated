# ScripCast AI Video Content Automation System

## Project overview

ScripCast was an AI content production and social publishing automation built to transform a simple content idea into a ready to publish video asset. The system connected form inputs, AI script generation, caption creation, avatar video generation, publishing workflows, and Google Sheets tracking into a coordinated content operations pipeline.

The project was designed to reduce manual effort in the content production process by automating the steps between content planning, script creation, video generation, caption preparation, publishing, and operational follow up.

## Business challenge

Content teams often lose time moving between disconnected tools to plan topics, write scripts, generate video assets, prepare captions, publish across social platforms, and track final links. The challenge was to design a workflow that could centralize these steps and support faster content production without losing quality or visibility.

## Solution designed

The system was structured as two connected automation workflows.

### Monologue generation workflow

This workflow collected content requirements through a form, including the monologue theme, target duration, social media platform, background selection, and avatar choice. It then used an AI agent to generate a short vertical video monologue and supporting captions.

Core capabilities included:

• Form based content intake  
• AI generated monologue scripts  
• Long caption generation for social posts  
• Short caption generation for simplified publishing  
• Research support through public content signals  
• Google Sheets logging for tracking and approval  
• Structured handoff into the video production workflow  

### Video creation and publishing workflow

This workflow used approved content from Google Sheets to create avatar based video assets and publish them through social media distribution tools.

Core capabilities included:

• Google Sheets trigger for approved video posts  
• Avatar video generation through HeyGen  
• Wait and status checking logic for video readiness  
• Upload of generated media into Blotato  
• Platform based routing using switch logic  
• Publishing to social channels such as TikTok, Instagram, Facebook, LinkedIn, and YouTube  
• Google Sheets update with the final video link  

## Tools and technologies

• n8n  
• OpenAI models  
• AI agents  
• Google Sheets  
• HeyGen  
• Blotato  
• Hacker News tools  
• HTTP requests  
• JSON  
• API integrations  
• Conditional logic  
• Switch routing  
• Workflow orchestration  

## Technical responsibilities demonstrated

• Designed an end to end automation pipeline for AI content generation and social media publishing  
• Connected AI writing, video generation, social publishing, and tracking systems into one operational flow  
• Built structured input and output logic to keep content production consistent and manageable  
• Implemented platform routing to publish different outputs based on selected social media channels  
• Created operational visibility by updating Google Sheets with generated content, status fields, and final video links  
• Managed API based integrations with external video and publishing platforms  
• Identified sensitive configuration elements and separated public documentation from private implementation details  

## Impact

The automation reduced repetitive content production tasks by connecting idea generation, copywriting, video creation, publishing, and tracking into a single workflow. It helped transform a manual, multi step process into a more structured and scalable content operations system.

## Public portfolio note

The original workflow exports are not included in this repository because they contain private configuration details, API references, account identifiers, webhook information, and operational credentials. This case study is a sanitized and anonymized summary intended to demonstrate the architecture, tools, and problem solving approach behind the project.
