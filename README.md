# AI-for-E-commerce-business

# 🛒 AI for E-Commerce Business – n8n Automation Workflow

An AI-powered e-commerce assistant built using n8n that integrates Telegram, OpenAI, AssemblyAI and Google Sheets to provide a smart shopping, product discovery and AI-based ad generation system.

<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/5c386847-32a3-4f3c-8b82-3574c5936df3" />

---

## 🚀 Features

- Telegram based AI shopping assistant
- Supports text, voice and image inputs
- Voice to text using AssemblyAI
- AI powered product search and recommendations
- Price and stock checking from Google Sheets
- Product image analysis
- AI generated UGC style ad prompts
- AI image generation for marketing creatives
- Conversation memory enabled

---

## 🧠 What this workflow does

### 1. Telegram trigger
Users interact with the bot through Telegram using:
- text messages
- voice messages
- product images

---

### 2. Input routing
A switch node automatically detects whether the input is:
- text
- voice
- or image

---

### 3. Voice assistant flow
- Downloads voice file from Telegram
- Sends audio to AssemblyAI
- Converts speech to text
- Sends the text to the AI shopping agent

---

### 4. Text shopping assistant flow

The AI agent helps users to:
- find products
- check price and availability
- get recommendations
- ask product related questions
- get offers and basic shopping support

The product data is fetched directly from Google Sheets.

---

### 5. Image & ad creation flow

- Product image is analyzed using OpenAI vision
- AI creates a professional UGC style advertisement prompt
- AI generates a marketing image based on that prompt

---

### 6. Telegram response
The final AI output is sent back to the user in Telegram.

---

## 🛠 Tech Stack

- n8n
- Telegram Bot
- OpenAI (Chat, Vision, Image generation)
- AssemblyAI (Speech-to-Text)
- Google Sheets (Inventory database)
- LangChain agents inside n8n

---

## 📁 Workflow File

---

## 🔐 Required credentials

You must configure the following credentials in n8n:

- Telegram Bot API
- OpenAI API
- AssemblyAI API key
- Google Sheets OAuth

---

## 📊 Google Sheet inventory format

Your Google Sheet should contain columns such as:

- product_name
- price
- stock
- category
- brand

---

## ▶️ How to run

1. Import the workflow JSON file into n8n
2. Add all required credentials
3. Activate the workflow
4. Start chatting with your Telegram bot

---

## 💬 Example queries


You can also send a voice message or a product image.

---

## 🎯 Use cases

- AI shopping assistant
- Telegram commerce bot
- AI powered product support
- AI marketing creative generation
- Small and medium business automation

---

## 👨‍💻 Author

Rohit Bachchhe  
AI & Data Science Engineer

