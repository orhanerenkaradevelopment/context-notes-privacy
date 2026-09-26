# MindContext: AI Research Notes & Side Panel — Privacy Policy

**Last Updated:** September 26, 2026  
**Developer:** Orhan Eren Kara  
**Contact:** orhanerenkara.dev@gmail.com  

---

**MindContext** allows you to save notes and quotations tied to web pages, organize multi-source research projects, and compile rich context prompts from your selected web content to use seamlessly with AI services.

---

## 1. Data We Process

MindContext processes only the minimum data required to deliver its core features:

- **Active Tab URL and Page Title:** Used solely to match and display the appropriate notes and quotes for the webpage you are currently viewing.
- **User Notes and Saved Quotes:** Thoughts, notes, and quotations explicitly highlighted and saved by the user.
- **Extracted Webpage Body Text:** Cleaned visible text extracted from the webpage upon explicit user request (e.g., when clicking "Send to AI" or "Preview Context").
- **Research Projects & Custom Prompt Templates:** Project collections, source relationships, and custom prompt templates created by the user.
- **User Preferences & Timestamps:** Interface language selection (`tr` / `en`), default AI provider, display preferences, and record creation/update timestamps.
- **Voluntary Pilot Survey Responses:** If you voluntarily participate in the pilot survey, your submitted feedback and (if optionally provided) your contact email address.

> MindContext **does not** monitor your overall browsing history, track visited websites, or archive your web activity.

---

## 2. Local Storage (`chrome.storage.local`)

All notes, quotes, research projects, prompt templates, and settings are stored **100% locally** within your browser sandbox via Chrome's native `chrome.storage.local` API.

- **No Remote Application Servers:** We do not maintain any central database, analytics servers, or remote cloud storage for user data.
- **No Analytics or Trackers:** MindContext contains zero third-party tracking scripts, telemetry, or user behavior tracking scripts.
- **Voluntary Pilot Survey:** Participation in the pilot survey is entirely optional. Data is transmitted directly to the developer through a secure form processor (Formspree) only when you explicitly click "Submit Feedback". Your notes, quotes, and web page contents are strictly excluded from this survey.
- **Data Integrity & Backups:** Temporary staging and journal records created during backup export or restore operations exist strictly within your local browser storage to prevent data corruption.

---

## 3. Transfer to Third-Party AI Services

MindContext offers two ways to interact with external AI providers:

- **Copy Prompt (Copy Context):** Copies the compiled context and instruction directly to your operating system's clipboard.
- **Send to AI:** Opens the selected AI service (**ChatGPT**, **Claude**, or **Gemini**) in a new tab. If the "Auto-paste" preference is enabled, the compiled context is automatically placed into the chat input area.

### Important Safety & Privacy Disclosures:
- Once placed in the chat input area, the prompt becomes subject to the respective third-party service provider's privacy policies and terms of service.
- **Zero Auto-Submit:** MindContext **never** clicks "Send" or presses the Enter key automatically. You retain full control to inspect, edit, or clear the prompt before submitting it yourself.
- Auto-paste can be disabled at any time in the **Settings** menu.

AI providers' data handling practices are governed by their respective privacy policies:
- **OpenAI (ChatGPT):** [https://openai.com/policies/privacy-policy/](https://openai.com/policies/privacy-policy/)
- **Anthropic (Claude):** [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)
- **Google (Gemini):** [https://policies.google.com/privacy](https://policies.google.com/privacy)

We strongly encourage users to review the preview screen before sending sensitive or confidential information to any external AI service.

---

## 4. Purpose and Justification of Chrome Permissions

MindContext requests only the permissions strictly necessary to operate:

- **`sidePanel`:** To render the user interface inside Google Chrome's native Side Panel alongside your active web pages.
- **`tabs`:** To identify the URL and title of the active tab, synchronize notes when switching tabs, and open target AI / source tabs upon user request.
- **`activeTab`:** To establish temporary, secure access to the active webpage when the user interacts with the extension.
- **`scripting`:** To extract the visible article text locally when context creation is requested, and to place the compiled prompt into the opened AI provider's chat box.
- **`contextMenus`:** To provide the right-click context menu option (*"Add to MindContext"*) when text is highlighted on any webpage.
- **`storage`:** To persist your notes, quotes, projects, prompt templates, and user preferences locally via `chrome.storage.local`.
- **Host Permissions (`http://*/*` and `https://*/*`):** Required to extract visible article text and highlight quotes on standard web pages while using the side panel.
- **Host Permissions (`chatgpt.com`, `claude.ai`, `gemini.google.com`):** Required exclusively to locate the chat input field and paste the compiled context when you click "Send to AI".
- **Host Permission (`formspree.io`):** Used solely to transmit user feedback when you voluntarily fill out and submit the pilot feedback survey.

---

## 5. Data Sharing and Use Restrictions

Under **no circumstances** do we sell, monetize, rent, or transfer your personal data to third parties, advertising networks, or data brokers. Your data is never used for credit evaluation, personalized ads, or any purpose outside the explicit functionality of MindContext.

MindContext's use and transfer of information received from Google APIs adhere strictly to the **Chrome Web Store User Data Policy**, including the **Limited Use** requirements.

---

## 6. User Control and Data Deletion

- Users can edit, organize, or delete individual notes, quotes, templates, and projects at any time through the extension interface.
- You can export a full JSON backup of all your data or restore from a backup whenever you wish.
- **Complete Removal:** When you uninstall MindContext from Google Chrome, all data stored in `chrome.storage.local` is permanently and automatically deleted by the browser.

---

## 7. Contact Us

If you have questions, feedback, or data privacy concerns regarding this policy, please contact:

**Developer:** Orhan Eren Kara  
**Email:** orhanerenkara.dev@gmail.com  

---

*© 2026 Orhan Eren Kara. All rights reserved.*
