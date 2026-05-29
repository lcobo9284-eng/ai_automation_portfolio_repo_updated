# AI Opportunity Audit Generator

## Project context

This automation generated AI opportunity audits from company website inputs and optional business context. The purpose was to help businesses identify where automation or AI agents could create value across marketing, sales, operations, reporting, customer experience, and internal workflows.

## Problem

Many companies are interested in AI but struggle to translate that interest into practical use cases. A manual audit requires reviewing the website, understanding the business model, identifying pain points, estimating opportunities, structuring recommendations, creating a report, and delivering the final output. This process is time consuming and difficult to scale when repeated for many companies.

## Approach

The workflow started with a form based intake that captured a website URL, company overview, branding option, delivery information, and optional files. The system fetched website content, extracted HTML data, analyzed the business context with AI, generated opportunity insights, prepared a structured report payload, passed it to Make.com for document creation, and delivered the result through internal or client facing channels.

The architecture used n8n, OpenAI models, Claude related tools, Make.com, HTTP requests, HTML extraction, Google Sheets, Slack, Gmail, JSON mappings, and code nodes for data handling.

## Solution

The final system created a repeatable audit generation pipeline. It turned an input form into a structured business report that identified AI opportunities and recommended possible automation use cases. The workflow reduced the manual research and formatting burden while keeping the output organized enough for presentation or follow up.

## My contribution

I built and optimized workflow logic, improved data passing between nodes, supported prompt and output structuring, coordinated document generation through Make.com, handled delivery logic, and worked through errors related to inconsistent website inputs and report payload formatting.

## Impact

The automation made AI opportunity analysis faster and more repeatable. It helped transform a consulting style evaluation into a scalable workflow that could support lead generation, client education, and internal business development.

## Public note

This public version does not include client inputs, private reports, internal prompts, webhook URLs, credentials, API keys, or original production workflow files.
