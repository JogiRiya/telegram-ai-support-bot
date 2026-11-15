**AI Customer Support Bot (Telegram + n8n)**

This is an advanced AI-powered customer support bot built using n8n, OpenAI, and the Telegram API.

**Features**

Dynamic Auto-Reply: Generates unique, human-like responses for every message.

Consistent Formatting: Automatically adds a professional signature ("Best regards, Radha") to every reply.

Context Memory: Remembers past interactions using a Window Buffer Memory, making conversations feel natural.

Bilingual Support: Automatically detects and replies in English or Hinglish based on the user's input.

**Tech Stack**

Automation: n8n

AI Model: OpenAI (GPT)

Integration: Telegram Bot API

**How it Works**

The Telegram Trigger listens for incoming messages.

The AI Agent (with Memory) processes the text using a custom System Prompt.

The AI generates a unique reply and appends the fixed signature.

The Telegram Node sends the final message back to the user.


