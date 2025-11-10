# AI Therapist App

A simple, compassionate AI therapist messaging app built with Expo and React Native, powered by OpenAI's GPT-3.5.

## Features

- 🤖 AI-powered therapeutic conversations using OpenAI API
- 💬 Clean, intuitive messaging interface
- 🔒 Secure API key storage (local only)
- 📱 Cross-platform (iOS, Android, Web)
- ⚙️ Easy API key management

## Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Get your OpenAI API Key:**
   - Visit [OpenAI API Keys](https://platform.openai.com/api-keys)
   - Create a new API key
   - Copy the key (starts with `sk-`)

3. **Run the app:**
   ```bash
   # For web
   npm run web
   
   # For iOS (requires macOS)
   npm run ios
   
   # For Android
   npm run android
   ```

4. **Enter your API key:**
   - When you first open the app, you'll be prompted to enter your OpenAI API key
   - The key is stored locally on your device and never shared

## Usage

- Simply type your thoughts or feelings in the message input
- The AI therapist will respond with empathetic, supportive messages
- Tap the settings gear (⚙️) in the header to change your API key

## Important Notes

- This is not a replacement for professional therapy
- Your conversations are processed by OpenAI's API
- API usage will be charged to your OpenAI account
- For serious mental health concerns, please consult a licensed professional

## Privacy

- Your API key is stored locally on your device
- Messages are sent to OpenAI for processing
- No conversation data is stored permanently in this app