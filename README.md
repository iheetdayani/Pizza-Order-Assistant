# 🍕 Pizza Order Assistant

An AI-powered pizza ordering assistant built using **Microsoft Copilot Studio** and **Microsoft Power Automate**.

The goal of this project is to demonstrate how an AI Agent can understand a user's intent, collect information conversationally, and guide the user through a complete pizza ordering and pickup workflow.

---

## 🤖 About the Project

The **Pizza Order Assistant** is a task-oriented AI Agent designed to simulate a real-world pizza ordering experience.

Instead of simply answering questions, the agent interacts with the customer, asks for the required information, maintains the conversation, confirms the order, and supports the collection workflow.

### Conversation Flow

```text
Customer
   ↓
Pizza Order Assistant
   ↓
Pizza Order
   ↓
Collection / Pickup
   ↓
Pizza Selection
   ↓
Cheese Selection
   ↓
Size Selection
   ↓
Order Details
   ↓
Order Confirmation
   ↓
Customer Name
   ↓
Pizza Collection
✨ Key Features
🗣️ Conversational AI interaction
🎯 User intent understanding
🍕 Pizza selection
🧀 Cheese selection
📏 Pizza size selection
👤 Customer information collection
✅ Order confirmation
🏪 Pickup / collection workflow
⚙️ Power Automate integration
🔄 End-to-end task-oriented conversation
🏗️ Architecture
                 ┌──────────────────┐
                 │     Customer     │
                 └────────┬─────────┘
                          │
                          ▼
              ┌───────────────────────┐
              │  Copilot Studio Agent │
              │ Pizza Order Assistant │
              └───────────┬───────────┘
                          │
                          ▼
                ┌──────────────────┐
                │ Conversation Flow│
                └────────┬─────────┘
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
   Pizza Choice     Order Details    Confirmation
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                ┌─────────────────┐
                │  Power Automate │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Order Processing│
                └────────┬────────┘
                         │
                         ▼
                 🍕 Pizza Pickup
🛠️ Technologies Used
Microsoft Copilot Studio
Microsoft Power Platform
Power Automate
AI Agents
Conversational AI
Workflow Automation
📂 Project Structure
pizza-order-assistant/
│
├── README.md
│
├── agent/
│   ├── bot.xml
│   └── configuration.json
│
├── solution/
│   └── PizzaOrderAssistant.zip
│
├── docs/
│   └── architecture.md
│
└── screenshots/
🎥 Project Demo

A practical demonstration of the Pizza Order Assistant is available in the project video.

The demo shows how the agent:

Understands the customer's request
Collects pizza preferences
Guides the conversation
Confirms the order
Completes the pickup workflow
💡 What I Learned

Building this project helped me understand that an AI Agent is more than a traditional chatbot.

A traditional chatbot may primarily follow predefined question-and-answer paths.

An AI Agent can combine:

User Intent
     +
Conversation
     +
Context
     +
Decision Making
     +
Actions
     =
Task Completion

Through this project, I gained practical experience with:

Designing conversational AI workflows
Creating task-oriented AI Agents
Working with Copilot Studio
Connecting AI with automation
Designing user-friendly conversations
Testing and debugging agent behavior
Understanding how AI can be integrated into real-world business processes
🚀 Future Improvements

Some possible improvements for future versions:

💳 Online payment integration
📍 Store/location selection
📦 Real-time order tracking
🧾 Automated receipt generation
📊 Order analytics
🔔 Customer notifications
🗄️ Database integration
🌐 Multi-language support
🔐 Security

This repository does not contain passwords, API keys, access tokens, or other sensitive credentials.

Connections and environment-specific authentication should be configured separately in the Power Platform environment.

👨‍💻 Author

Heet Dayani

Building and learning in the fields of:

Artificial Intelligence
Machine Learning
Generative AI
AI Agents
Automation
⭐ Project

If you find this project useful or interesting, feel free to explore the repository and follow my journey as I continue building practical AI projects.


### One change I strongly recommend

Since this is going on your **GitHub portfolio**, don't make the README only about *what the agent does*. The **“What I Learned”** section is valuable because it shows recruiters that you understand the engineering concept behind the project—not just how to click through Copilot Studio.

Also, once you upload your **demo video**, we can add it near the top:

> 🎥 **Live Demo: Pizza Order Assistant**

That will make the repository much stronger.
