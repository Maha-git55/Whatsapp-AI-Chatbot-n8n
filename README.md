# WhatsApp AI Chatbot with n8n

A powerful WhatsApp chatbot integrated with Google Gemini AI using n8n workflow automation.

## 🚀 Features

- WhatsApp Business API integration
- Google Gemini AI responses
- Ngrok tunneling for webhook handling
- Automated message processing

## 📋 Prerequisites

- n8n instance (local or cloud)
- Meta Developer Account
- Google Gemini API Key
- Ngrok account

## 🔧 Setup Steps

### 1. Local n8n Setup
- Install n8n locally
- Configure WhatsApp trigger node
- **Issue**: Webhook requires public domain

### 2. Ngrok Tunnel Solution
- Create ngrok tunnel: `ngrok http 5678`
- Obtain public URL for webhooks

### 3. WhatsApp Configuration
- Set up WhatsApp Business API
- Configure webhook with ngrok URL
- Use test number: +15556306465

### 4. AI Integration
- Add Google Gemini API key
- Configure AI Agent node
- Set up message processing workflow

### 5. Workflow Nodes
- WhatsApp Trigger (on message)
- AI Agent (process message) 
- Google Gemini Model (AI brain)
- WhatsApp Send Message (reply)

## 🛠️ Technical Stack

- **n8n**: Workflow automation
- **Google Gemini**: AI model
- **WhatsApp Business API**: Messaging
- **Ngrok**: Secure tunneling


## 🎯 Usage

1. Send message to WhatsApp test number
2. AI processes the message via n8n workflow
3. Automated response sent back via WhatsApp

## ⚡ Troubleshooting

- Ensure ngrok tunnel is active
- Verify WhatsApp webhook configuration
- Check Google Gemini API key validity
- Monitor n8n workflow executions

## 📞 Support

For issues related to this setup, check n8n community forums or create an issue in this repository.
