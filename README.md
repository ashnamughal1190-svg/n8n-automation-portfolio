n8n Automation Portfolio

A collection of AI automation workflows built with n8n. Each project connects an AI model (Gemini, OpenAI, Claude) to everyday tools like Gmail, Google Sheets, and LinkedIn, to automate real tasks end to end.
Every project has its own folder with the exported workflow JSON, screenshots, and a README explaining how it works and how to set it up.

Projects
Project	What it does	Stack
Lead Capture AI Workflow	Captures incoming leads, processes them with AI, logs them to a sheet, and sends an email follow-up	n8n, Gemini, Google Sheets, Gmail
LinkedIn Post Generator with Human Approval	Turns a one-line idea into a LinkedIn post and image, with an email approval step before anything is published	n8n, OpenAI, Gmail, LinkedIn, Wikipedia tool
What these projects show
Human-in-the-loop automation: the LinkedIn workflow pauses for an email approval, so AI drafts never go live unchecked.
AI agents with tools: agents that call tools such as Wikipedia to ground their output.
Multi-model workflows: Gemini, OpenAI, and Claude APIs used where each fits best.
Real integrations: Gmail, Google Sheets, and LinkedIn connected through n8n.
How to use a workflow
Open a project folder and read its README.
In n8n, go to Workflows > Import from file and select the JSON.
Add your own credentials (OpenAI, Gemini, Gmail, Google Sheets, LinkedIn, etc.) to the nodes that need them.
Replace any placeholders such as YOUR_EMAIL@example.com.
Run it from the trigger node to test.

Credentials are never stored in this repository. You must connect your own accounts.

Tech stack
Automation: n8n
AI models: Gemini, OpenAI, Claude
Integrations: Gmail, Google Sheets, LinkedIn, Wikipedia

About me

I'm Ashna Younas, an AI automation developer who also builds Flutter and Firebase apps, and a BSIT graduate. I focus on practical automations where AI does the heavy lifting and a human keeps control of the important decisions.

Feedback and ideas are welcome. Feel free to open an issue.
