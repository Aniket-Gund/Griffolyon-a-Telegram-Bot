# **Griffolyon-a-Telegram-Bot**

## **Workflow Link: https://aniketgund12.app.n8n.cloud/workflow/EvUmoUezPd6Aog3M **
## **Telegram Link: https://t.me/Griffolyon_bot **

# **🤖 AI-Powered Telegram Chatbot using n8n**
## **📌 Project Overview**

This project is an AI-powered Telegram chatbot built using n8n workflow automation. The bot listens to user messages on Telegram, processes them through an AI Agent powered by Google Gemini, optionally retains conversation context using memory, and sends intelligent responses back to the user in real time.

The main goal of this project is to demonstrate how low-code automation platforms like n8n can be used to build production-ready AI agents without writing a full backend from scratch.

## **🧠 System Architecture**

The chatbot workflow consists of the following components:

1. Telegram Trigger

Listens for incoming messages from a Telegram bot

Acts as the entry point of the workflow

Trigger type: message

2. AI Agent (Core Logic)

Receives user input from Telegram

Uses an LLM to generate intelligent responses

Handles:

Prompt understanding

Context-aware replies

Conversational flow

3. Chat Model – Google Gemini

Integrated using n8n’s AI node

Responsible for:

Natural language understanding

Response generation

Chosen for fast inference and strong conversational capabilities

4. Memory Module (Optional but Implemented)

Stores past interactions

Enables:

Context-aware conversations

Follow-up questions

Demonstrates real-world chatbot behavior instead of stateless replies

5. Telegram Send Message

Sends the AI-generated response back to the user

Completes the request–response cycle

## **🔄 Workflow Execution Flow**

User sends a message on Telegram

Telegram Trigger activates the workflow

Message is passed to the AI Agent

AI Agent processes input using Gemini model

Memory module retrieves or updates conversation history

Final response is generated

Response is sent back to the user via Telegram

## **🛠️ Technologies Used**

n8n – Workflow automation platform

Telegram Bot API – User interaction interface

Google Gemini – AI chat model

AI Agent Node – Conversational intelligence

Memory Module – Context retention

## **🚀 Key Features**

Real-time Telegram chatbot

AI-generated intelligent responses

Context-aware conversations using memory

No-code / low-code implementation

Easily extendable (APIs, databases, tools can be added)

## **📂 Repository Contents**

workflow.json – Exported n8n workflow

README.md – Project documentation

screenshots/ – Workflow and chatbot screenshots and video

## **🧪 How to Run This Project**

Install or access n8n (cloud or self-hosted)

Import the provided workflow JSON

Create a Telegram bot using BotFather

Add Telegram credentials in n8n

Configure Google Gemini API credentials

Activate the workflow

Start chatting with your Telegram bot

## **📈 Use Cases**

AI customer support bots

Educational assistants

Personal productivity bots

FAQ automation

AI experimentation with minimal backend setup

## **🎯 Why This Project Matters**

Most beginners just build static rule-based bots.
This project goes further by:

Using LLM-powered AI

Maintaining conversation memory

Applying real-world automation concepts

It shows clear understanding of:

AI workflows

Event-driven systems

Practical chatbot architecture

## **🔮 Future Improvements**

User authentication and role-based responses

Database-backed long-term memory

Tool calling (APIs, web search, internal tools)

Multi-language support

Deployment monitoring and logging
