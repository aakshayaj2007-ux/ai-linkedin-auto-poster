# ai-linkedin-auto-poster
🤖 AI-powered LinkedIn automation workflow built with n8n and Google Gemini. Automatically generates LinkedIn posts from a given topic and publishes them to LinkedIn.
# 🤖 AI-Powered LinkedIn Auto-Posting Workflow

An AI-powered LinkedIn content automation workflow built using n8n and Google Gemini.

The workflow automatically generates a LinkedIn post based on a given topic and publishes it to LinkedIn without requiring manual copy-pasting.

## 🚀 What It Does

The workflow follows a simple automation pipeline:

Topic
   ↓
Google Gemini AI
   ↓
LinkedIn Post
   ↓
Automatic Publishing

The goal of this project is to explore how AI and workflow automation can be combined to automate social media content creation.

## 🛠️ Technologies Used

- n8n
- Google Gemini
- LinkedIn
- AI/LLM
- Workflow Automation

## ⚙️ Workflow

The current workflow consists of:

### 1. Schedule Trigger

Starts the workflow automatically according to the configured schedule.

### 2. Google Gemini Chat Model

Gemini generates the LinkedIn post based on the provided instructions/topic.

### 3. Basic LLM Chain

Processes the prompt and generates the final post content.

### 4. LinkedIn

Publishes the generated content directly to LinkedIn.

## ✨ Features

- AI-generated LinkedIn posts
- Automatic publishing
- Scheduled execution
- No manual copy-pasting
- Simple workflow architecture
- Easy to extend with additional AI features

## 📸 Workflow Preview

![Workflow](screenshots/workflow.png)

## 🔧 Setup

### Prerequisites

You need:

- An n8n instance
- Google Gemini API access
- A LinkedIn account
- LinkedIn credentials configured in n8n

### Installation

1. Download the workflow JSON file.
2. Open your n8n instance.
3. Import the workflow.
4. Configure your Google Gemini credentials.
5. Configure your LinkedIn credentials.
6. Customize the AI prompt.
7. Set your preferred schedule.
8. Test the workflow.
9. Activate the workflow.

## 🧠 Example Prompt

You can give the AI a topic such as:

"Write a LinkedIn post about what I learned while building my first AI automation."

The AI then generates the post and sends it to LinkedIn.

## 🔐 Security

Never share:

- API keys
- OAuth tokens
- Passwords
- Private credentials
- Environment variables containing secrets

Credentials should be configured privately inside n8n.

## 🔮 Future Improvements

Possible improvements include:

- Automatic topic generation
- Trending-topic research
- Multiple post styles
- Automatic hashtag generation
- Human approval before publishing
- Image generation
- LinkedIn analytics tracking
- Post performance analysis
- Content calendar
- Multiple social media platforms

## 📚 What I Learned

This project helped me understand:

- AI workflow automation
- LLM integration
- API-based automation
- n8n workflows
- Connecting AI models with external platforms
- Automated content generation
- Practical applications of AI

## 👨‍💻 About the Project

This project was built as a learning project to explore practical applications of AI and automation.

I believe the best way to learn technology is by building real projects.

---

⭐ If you find this project useful, consider giving the repository a star!
