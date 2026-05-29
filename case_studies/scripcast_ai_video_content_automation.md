# ScripCast AI Video Content Automation System

## Project context

ScripCast was an AI content production and social publishing automation designed to transform a simple content idea into a publishable video asset. The workflow connected form inputs, AI script generation, caption creation, avatar video generation, social platform routing, publishing, and Google Sheets tracking into one content operations pipeline.

## Problem

Content production teams often lose time moving between disconnected tools. A single short video may require topic planning, script writing, caption creation, avatar or video generation, upload to a publishing tool, selection of the correct social platform, publishing configuration, and final link tracking. When these steps are managed manually, the process becomes slow, difficult to monitor, and inconsistent across platforms.

## Approach

The system was divided into two connected workflows. The first workflow collected the content requirements through a form, including topic, target duration, social platform, background, and avatar selection. An AI agent generated the monologue, then separate AI steps created long and short captions. The generated content was stored in Google Sheets to provide an operations layer for tracking and review.

The second workflow handled video creation and publishing. It read approved rows from Google Sheets, generated an avatar based video through HeyGen, waited for the provider to complete processing, retrieved the final media asset, uploaded the video to Blotato, routed the post through platform based switch logic, published to selected channels such as TikTok, Instagram, Facebook, LinkedIn, and YouTube, and updated Google Sheets with the final video link.

## Solution

The final automation converted a fragmented content workflow into a coordinated production system. It separated content generation from publishing, preserved visibility through Google Sheets, handled asynchronous video processing through wait and status logic, and routed publishing actions according to the selected platform.

The system was designed to be practical for content operations. It kept creative inputs simple for the user, handled repetitive technical steps automatically, and gave the team a clear record of generated scripts, captions, selected platforms, and final media links.

## My contribution

I contributed to the end to end workflow structure, AI script generation flow, caption generation logic, Google Sheets tracking, API based video generation, wait and status checking, publishing payloads, platform routing, and troubleshooting of external service integrations. I also identified sensitive configuration elements that needed to remain private and separated public documentation from production workflow details.

## Impact

The automation reduced repetitive content production work by connecting idea intake, writing, video creation, publishing, and tracking. It made the process more scalable and easier to monitor, while reducing the manual coordination required between creative and technical tools.

## Public note

The original workflow exports are not included because they contain private configuration details, API references, account identifiers, webhook information, and operational credentials. This public case study is a sanitized explanation of the architecture and problem solving approach.
