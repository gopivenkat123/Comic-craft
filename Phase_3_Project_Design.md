# Phase 3: Project Design

## System Architecture

* **Client Tier:** Dynamic HTML5/CSS3 templates served via Jinja2.
* **Server Tier:** Asynchronous FastAPI backend running on Uvicorn.
* **AI Processing Tier:** Google Generative AI API (Gemini 1.5 Flash) for multimodal parsing.
* **Infrastructure:** Containerized web service running on Render cloud.

## Data Flow

1. User uploads a receipt image via the web client.
2. FastAPI processes the payload and forwards the image to the Gemini multimodal endpoint.
3. Gemini extracts itemized details and spending insights.
4. Jinja2 renders and returns the structured results view to the user.





* *Date:* 30 September 2026
* *Team ID:* 10
* *Project Name:* ComicCraft - Al Comic Story Creator using Gemini Models
* *Maximum Marks:* 3 Marks

\---

## Step 3: Project Design Phase Phase

|S.No|Team Member|Idea / Suggestion|Category|Group No.|
|-|-|-|-|-|
|1|Gopi Venkat J|Multimodal receipt image parsing using Google Gemini 1.5 Flash API|AI Architecture \& Vision|Group 10|
|2|Mathesh Krishna R|Automated line-item expense categorization and tax breakdown|Data Processing \& Logic|Group 10|
|3|Aneesh R|Dynamic Jinja2 web interface for intuitive mobile and desktop uploads|Frontend \& UI/UX|Group 10|
|4|Ragulhariharan|Budget threshold alerting and smart savings recommendations engine|Business Logic \& Rules|Group 10|



