# API LLM Chat Guide

This guide provides instructions for setting up and using the API LLM Chat node in nndeploy for conversational AI interactions.

---

## Prerequisites

Using the API LLM Chat requires:
- An active account with a compatible LLM API provider (OpenAI, Anthropic, etc.)
- Valid API key from your chosen provider
- Internet connection for API calls

---

## Setup Instructions

### Step 1: Obtain LLM API Key

1. Choose your preferred LLM provider:
   - **OpenAI**: Visit [OpenAI Platform](https://platform.openai.com/)
   - **Anthropic**: Visit [Anthropic Console](https://console.anthropic.com/)
   - **Other OpenAI-compatible APIs**: Check your provider's documentation
2. Sign up or log in to your account
3. Navigate to API Keys section
4. Create a new API key
5. Copy and securely store your API key

### Step 2: Configure API Settings in Node

1. Open the LLM Chat node configuration
2. Set the following parameters:
   - **API Key**: Paste your API key into the designated field
   - **Base URL**: Set the API endpoint (e.g., https://api.openai.com/v1 for OpenAI)
   - **Model**: Choose your preferred model (e.g., gpt-3.5-turbo, gpt-4, claude-3-sonnet)
   - **Temperature**: Adjust creativity level (0.0-1.0)
   - **Max Tokens**: Set maximum response length
3. Save the configuration

### Step 3: Configure Chat Parameters (Optional)

1. **System Prompt**: Set the AI's role and behavior instructions
2. **Context Window**: Configure conversation history length
3. **Streaming**: Enable/disable real-time response streaming
4. **Safety Settings**: Configure content filtering if available

### Step 4: Verify Setup

1. Test the node with a simple chat message
2. Ensure the API connection is working properly
3. Check that responses are being generated successfully
4. Verify conversation context is maintained across messages

---

## Important Notes

- Keep your API key secure and do not share it publicly
- Monitor your API usage to avoid unexpected charges
- Refer to your provider's pricing page for current rates
- Ensure you have sufficient credits/quota in your account
- Be aware of rate limits and adjust usage accordingly
- Consider using environment variables for API key storage
- Test thoroughly before deploying in production environments