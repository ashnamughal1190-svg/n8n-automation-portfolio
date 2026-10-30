# n8n Automation Portfolio

AI automation workflows built with **n8n**. Each project connects an AI model (Gemini, OpenAI, Claude) to everyday tools like Gmail, Google Sheets and LinkedIn, and automates a real business task from start to finish.

Every project folder has the exported workflow JSON, screenshots, and a README that explains how it works and how to set it up.

## Projects

| Project | What it does | AI | Tools |
| --- | --- | --- | --- |
| [Lead Capture and AI Qualification](lead-capture-ai-workflow) | Turns a website contact form into a lead pipeline. AI sorts each lead into Hot, Warm or Spam, writes a summary and a reply, logs it, replies to real leads and alerts the team about Hot ones. | Gemini | Google Sheets, Gmail |
| [LinkedIn Post Generator with Human Approval](linkedin-post-generator-human-approval) | Turns a one-line idea into a LinkedIn post. AI drafts it, a human approves by email, and only then is an image generated and the post published. | OpenAI | Gmail, LinkedIn, Wikipedia |

## What these show

- **AI with a safety net:** a human approval step before anything goes public, a prompt-injection guard on form input, and structured JSON output so the AI's answers stay predictable.
- **End-to-end flows:** from the trigger, through the AI step, to logging, emailing and publishing, with error alerts when a step fails.
- **Clear setup:** each project lists the credentials it needs and the steps to run it. No credentials are stored in this repository.

## Tech stack

- **Automation:** n8n
- **AI models:** Gemini, OpenAI, Claude
- **Integrations:** Gmail, Google Sheets, LinkedIn, Wikipedia

## About me

I'm Ashna Younas, an AI automation developer and BSIT graduate who also builds Flutter and Firebase apps. I focus on practical automations where AI does the heavy lifting and a human keeps control of the important decisions.

Connect with me on [LinkedIn](https://www.linkedin.com/in/ashna-mughal-89b87a2b5/). Feedback and ideas are welcome, feel free to open an issue.
