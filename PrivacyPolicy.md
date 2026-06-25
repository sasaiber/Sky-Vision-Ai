# Sky Vision Privacy Policy

**Last Updated: June 2026**

We respect your privacy and aim to be fully transparent about data collection and usage. Sky Vision is a client application for various AI models, and your data security depends directly on the features, permissions, and providers you choose to use. **This app is strictly compliant with Google Play Store Policies.**

## 1. Core Features, Permissions, and Data Usage

Sky Vision offers smart features that require specific Android permissions. Each feature processes data strictly for its intended purpose:

*   **Assistant & Chat:** Your main text and voice AI assistant. 
    *   **Functionality:** Answers questions, performs internet searches, sends SMS, makes phone calls, views your calendar, sets alarms and timers, shows weather forecasts, and sends emails.
    *   **Permissions & Data:** 
        *   `RECORD_AUDIO` (Microphone): To recognize your voice commands. Voice data is transcribed and sent to the AI to answer your queries.
        *   `READ_CALENDAR` / `WRITE_CALENDAR`: To check your schedule or add events only when you explicitly ask the Assistant.
        *   `SEND_SMS` / `CALL_PHONE` / `READ_CONTACTS`: To find contacts and execute your direct commands to text or call someone.
        *   `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`: To provide accurate weather data based on your location.
        *   `MediaProjection` (Screen Capture): Used *only* when you explicitly request the AI to analyze what is currently visible on your screen. The captured screenshot is temporarily transmitted to your chosen AI provider and never recorded as video.
*   **Writehub:** 
    *   **Functionality:** A tool to fix and improve text in any app, chat with AI, and use web search from selected providers. If **My Space** is enabled, it provides personalization and quick view of notes (e.g., quickly typing numbers, addresses, or emails of created contacts directly into the command field without leaving the current app).
    *   **Permissions & Data:** Requires `BIND_ACCESSIBILITY_SERVICE` (Accessibility). It reads the text inside the input field you are currently typing in. The extracted text is sent to the AI *only* when you manually press an action button to process it. No background keylogging is performed. It also uses `SYSTEM_ALERT_WINDOW` (Display over other apps) to show its floating UI.
*   **Alertbrief:** 
    *   **Functionality:** Groups incoming notifications and generates concise summaries.
    *   **Permissions & Data:** Requires `BIND_NOTIFICATION_LISTENER_SERVICE` (Notification Access). It reads incoming notification text and sends it to your selected AI to generate a summary.
*   **Priorityflow:** 
    *   **Functionality:** Analyzes incoming notifications based on custom rules and AI rules to determine if a message is "Important" or should be silenced.
    *   **Permissions & Data:** Requires `BIND_NOTIFICATION_LISTENER_SERVICE`. The notification text is semantically analyzed by the AI.
*   **Tasks & AI Tasks:**
    *   **Functionality:** Executes background automated AI routines and multi-step plans.
    *   **Permissions & Data:** Uses existing permissions (like Calendar or Contacts) to execute scheduled AI tasks on your behalf. Contextual data required for the task is sent to the AI.
*   **Mail Agent:**
    *   **Functionality:** Integrates with your email to draft, read, or summarize messages. 
    *   **Permissions & Data:** Processes email contents through your chosen AI provider to generate summaries or replies.
*   **Memory:**
    *   **Functionality:** An intelligent long-term memory system allowing the AI to remember context from past conversations. 
    *   **Data:** Stored strictly locally as a knowledge graph on your device.
*   **My Space:**
    *   **Functionality:** A unified hub for Assistant, Writehub, Chat, and AI Tasks. You can save specific information here so the AI knows the email of a contact or any notes to make writing emails, providing context, and generating responses easier.
    *   **Data:** Stored strictly locally on your device.

## 2. Third-Party Integrations and Privacy Policies

Sky Vision acts as an interface. You choose where your data goes by selecting providers in the app settings. When you select a cloud provider, your prompts, selected text, or screenshots are transmitted to their respective servers. You must review and agree to their privacy policies.

### AI Providers
*   **Google Gemini (AI Studio):** https://policies.google.com/privacy
*   **OpenAI:** https://openai.com/policies/privacy-policy
*   **Claude (Anthropic):** https://www.anthropic.com/legal/privacy
*   **DeepSeek:** https://www.deepseek.com/privacy
*   **Mistral:** https://mistral.ai/terms/privacy/
*   **Cohere:** https://cohere.com/privacy
*   **OpenRouter:** https://openrouter.ai/privacy
*   **Nvidia NIM:** https://www.nvidia.com/en-us/about-nvidia/privacy-policy/
*   **Groq:** https://groq.com/privacy-policy/
*   **Cerebras:** https://cerebras.net/privacy-policy/
*   **Puter:** https://puter.com/privacy
*   **Pollinations AI:** https://pollinations.ai/privacy
*   **Ollama:** https://ollama.com/privacy
*   **Gemini Nano:** Processed entirely offline on your device. No data is sent over the internet.
*   **Free G4F:** Suitable for everyday use. Data is routed through various community endpoints to provide free access.

### Web Search Providers
The Assistant and Writehub can perform internet searches. Data sent includes your search queries.
*   **Langsearch:** Available for free (limits apply) or with an API key. https://docs.langsearch.com/legal/privacy-policy
*   **Tavily:** https://tavily.com/privacy-policy
*   **DuckDuckGo:** https://duckduckgo.com/privacy

### Weather Providers
To provide weather forecasts, your location coordinates (if permitted) are sent to:
*   **Open-Meteo:** https://open-meteo.com/en/features#terms
*   **OpenWeatherMap:** https://openweathermap.org/privacy-policy
*   **WeatherAPI:** https://www.weatherapi.com/privacy.aspx

## 3. Accounts, Data Retention and Security
**Account Creation & Server Use:** Sky Vision offers account creation via Google OAuth. We maintain a server exclusively for the purpose of facilitating access to free AI models and web search functionalities. 

**Data Storage:** We (the developers of Sky Vision) do not operate centralized servers to collect or store your personal chats, emails, or system data. Your API keys, chat history, Priorityflow rules, Memory graph, and My Space profiles are stored **strictly locally** in the protected storage of your device.

**Data Deletion:** You can delete all your local data at any time by clearing the app data in Android Settings or uninstalling the app. To request the deletion of your Google OAuth account and any associated data from our servers, please contact our support at **roslovtsev167@gmail.com** (or via our Telegram community).
