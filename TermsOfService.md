# Sky Vision Unified Legal Document
**Last Updated: March 17, 2026**

This document serves as the End User License Agreement (EULA), Terms of Service (ToS), and Privacy Policy for the **Sky Vision** application. By downloading, installing, or using the Software, you agree to these terms.

**Important Note regarding "Sky Vision Agent":** The advanced "AI Agent" module (which performs autonomous device control and clicks) is distributed as a separate, optional application and is **NOT available on the Google Play Store** due to its advanced automation capabilities. This document primarily governs the features available in the main Sky Vision app (Assistant, WriteHub, AlertBrief, PriorityFlow). If you choose to sideload the separate Agent app, these terms apply to its data processing as well.

---

## I. PROMINENT DISCLOSURES & PERMISSIONS (IMPORTANT)

To provide its core AI functionalities, Sky Vision requires specific permissions. We strictly adhere to Google Play Developer Policies regarding user transparency. Below is a detailed explanation of what data is accessed, why it is needed, and how it is used for each feature.

### 1. Accessibility Service API (`BIND_ACCESSIBILITY_SERVICE`)
*   **What data is accessed:** The text visible on your screen, the contents of input fields, and the structural layout of user interface (UI) elements.
*   **Why it is used (Core Functionality - WriteHub):** The Accessibility Service is used exclusively by the **WriteHub** feature. It allows the app to read the text you have typed or selected in any application, process it according to your commands (e.g., fix grammar, change tone, summarize), and automatically insert the improved text back into the active text field. 
*   **Data Handling & Privacy:** The Accessibility Service is *never* used to silently monitor your activity, bypass Android privacy controls, or record remote call audio. Extracted text is only processed when you actively trigger a WriteHub command. If a cloud AI provider is selected, the specific text snippet is temporarily transmitted to that provider for processing and is not stored by us.

### 2. Screen Capture / MediaProjection API
*   **What data is accessed:** Images (screenshots) of your entire device screen.
*   **Why it is used (Core Functionality - Assistant Vision):** To provide "Vision" capabilities for the **Sky Vision Assistant**. When you open the Assistant chat overlay and explicitly ask a question about what is currently on your screen (e.g., "Summarize this article", "Translate this image"), the app captures a temporary screenshot to provide visual context to the AI.
*   **Data Handling & Privacy:** Screen recording is *never* done in the background without your knowledge. A system-level consent dialog will appear, and a standard Android recording indicator will be visible while active. The captured screenshot is temporarily transmitted to your chosen cloud AI (e.g., Google Gemini) to generate a response, after which it is immediately discarded. We do not save or record video of your screen.

### 3. Notification Access (`BIND_NOTIFICATION_LISTENER_SERVICE`)
*   **What data is accessed:** Notification content, including app package names, sender names, message titles, and message text.
*   **Why it is used (Core Functionality):** 
    *   **AlertBrief:** To group incoming notifications and generate concise, smart summaries so you don't have to read long message threads.
    *   **PriorityFlow:** To semantically analyze incoming notifications against your custom rules to determine if they are "Important" or should be silenced.
*   **Data Handling & Privacy:** Notification data is only accessed as it arrives. To generate summaries or classifications, the text of the notification is sent to your selected AI provider.

### 4. Microphone (`RECORD_AUDIO`)
*   **What data is accessed:** Your voice input.
*   **Why it is used:** To allow you to dictate prompts and questions directly to the Assistant.
*   **Data Handling:** Audio is transcribed locally using Android's built-in speech recognizer, and the resulting text is processed by the AI.

### 5. Display Over Other Apps (`SYSTEM_ALERT_WINDOW`)
*   **What it does:** Allows the app to draw UI elements on top of other running applications.
*   **Why it is used:** To display the floating WriteHub action bar and the Assistant chat window, allowing you to access AI features without leaving your current app.

---

## II. PRIVACY POLICY & DATA PROCESSING

### 1. Data Processing and Third-Party AI Providers
Sky Vision acts as an interface between you and various AI models. The privacy of your data depends heavily on the AI provider you select in the app's settings:

*   **On-Device Processing (Gemini Nano):** If your device supports it and you select Gemini Nano, inference is performed entirely locally. Your prompts, screen data, and text do not leave your device.
*   **Cloud Processing:** If you select a cloud-based provider (e.g., Google Gemini AI Studio, OpenRouter, NVIDIA NIM, Groq, Pollinations), the data required to fulfill your request (prompts, selected text, notification snippets, or screenshots) is transmitted securely via HTTPS to that provider's API. 
*   **Provider Policies:** We do not control how third-party providers handle your data once transmitted. You must review and agree to their respective privacy policies before use:
    *   Google Privacy Policy: https://policies.google.com/privacy
    *   OpenRouter Privacy Policy: https://openrouter.ai/privacy
    *   NVIDIA Privacy Policy: https://www.nvidia.com/privacy

### 2. Data Retention
SkyTech Inc. does not maintain centralized servers that log or store your personal data, chat history, or screen contents. Your chat history, custom AI rules, API keys, and app preferences are stored **locally** on your device's private storage. You can delete this data at any time by clearing the app's data or uninstalling the app.

---

## III. TERMS OF SERVICE & USER RESPONSIBILITY

### 1. Scope of Services
The Software provides AI-powered assistance and text processing. It is provided "AS IS" and "AS AVAILABLE" as a productivity tool, not as a guaranteed, infallible system.

### 2. User Responsibility & AI Output
*   **Output Accuracy:** AI-generated content (including text generation, code, and summaries) may be inaccurate, incomplete, or misleading. You are solely responsible for reviewing and verifying all AI output before relying on it or sending it to others.
*   **High-Risk Use:** You must not rely on the Software for medical, legal, financial, emergency, or safety-critical decisions.

### 3. API Keys and Billing
If you utilize third-party AI providers that require an API key, you are solely responsible for securing that key, managing your provider account, and paying any associated billing or usage charges incurred by your API requests.

---

## IV. END USER LICENSE AGREEMENT (EULA)

### 1. Grant of License
SkyTech Inc. grants you a revocable, non-exclusive, non-transferable, limited license to download, install, and use the Software solely for your personal, non-commercial purposes on your Android device in accordance with these terms.

### 2. Restrictions
You agree not to, and you will not permit others to:
*   License, sell, rent, lease, assign, distribute, or commercially exploit the Software.
*   Modify, make derivative works of, disassemble, reverse compile, or reverse engineer any part of the Software.
*   Remove, alter, or obscure any proprietary notice.
*   Use the Software for any illegal purpose or in violation of any applicable law.

### 3. Limitation of Liability
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL SKYTECH INC., ITS AUTHORS, OR DISTRIBUTORS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER (INCLUDING, BUT NOT LIMITED TO, DAMAGES FOR LOSS OF PROFITS, LOSS OF DATA, DEVICE MALFUNCTION, OR OTHER PECUNIARY LOSS) ARISING OUT OF THE USE OF OR INABILITY TO USE THE SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

### 4. Updates and Termination
SkyTech Inc. reserves the right to modify these terms at any time. Continued use of the Software constitutes acceptance of the modified terms. This license is effective until terminated. We may terminate this license at any time if you fail to comply with these terms.

**Contact Information:** For support, feedback, or inquiries, visit our community at https://t.me/i_sky_vision_i
