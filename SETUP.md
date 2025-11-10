# Setup Instructions

## Adding Your OpenAI API Key

1. **Get your OpenAI API Key:**
   - Go to [OpenAI API Keys](https://platform.openai.com/api-keys)
   - Click "Create new secret key"
   - Copy the key (it starts with `sk-`)

2. **Add the API key to your environment:**
   - Open the `.env` file in the project root
   - Replace `your_openai_api_key_here` with your actual API key:
   ```
   EXPO_PUBLIC_OPENAI_API_KEY=sk-your-actual-key-here
   ```

3. **Run the app:**
   ```bash
   npm run web
   ```

## Important Notes

- The `.env` file is already added to `.gitignore` so your API key won't be committed to version control
- Make sure to restart the development server after adding your API key
- Your API key is only used locally and sent directly to OpenAI's servers

## File Locations

- **API Key:** `.env` file in the project root
- **Main App:** `App.tsx`
- **Environment variable name:** `EXPO_PUBLIC_OPENAI_API_KEY`

The app will automatically use your API key from the environment variable - no need to enter it in the app interface!