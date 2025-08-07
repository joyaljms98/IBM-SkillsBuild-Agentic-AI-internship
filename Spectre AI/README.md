# Spectre AI: Your Indian Legal AI Agent ⚖️

Spectre AI is a dedicated legal assistant engineered to simplify the complexities of Indian law. This web-based application provides users with clear, step-by-step guidance on various legal issues and connects them to official government resources and contact information.

## ✨ Features

* **Intelligent Legal Guidance**: The core feature of Spectre AI is its ability to understand a user's legal situation and provide a structured, actionable response. It offers step-by-step guidance on procedures like filing an FIR, handling consumer complaints, or dealing with property disputes.
* **Comprehensive Knowledge Base**: The agent is powered by a robust internal knowledge base covering a wide range of legal domains, including:
    * Personal & Family Law
    * Financial & Commercial Law
    * Safety & Civic Rights
    * Employment & Labour Law
    * Intellectual Property (IP) Law
* **Official Resources & Contacts**: For every legal topic, the application provides a list of official government websites and, where available, direct contact information like helpline numbers and email addresses. This ensures users are directed to authoritative sources for further action.
* **Email Generation Assistant**: When a user's query is substantial enough to warrant formal communication, the AI can generate a professional email draft. This draft includes a clear subject line and a summary of the case with placeholders for personal details, making it easy for the user to contact a lawyer or official.
* **Chat History Management**: All conversations are saved in a persistent chat history, allowing users to revisit past queries and their corresponding legal guidance. Users can easily switch between chats, create new ones, and delete old ones.
* **Customizable API Integration**: The application is built to be flexible, supporting both the **Gemini** and **OpenAI** APIs. Users can easily enter and save their preferred API key in the settings to power the AI backend.
* **User-Friendly Interface**: The application features a clean, modern, and responsive design with a sidebar for chat history and a separate sidebar for displaying relevant references.
* **Dark Mode**: A dark theme is available and can be toggled to reduce eye strain, providing a comfortable user experience in different lighting conditions.
* **Persistence and Privacy**: All user data, including API keys, chat history, and theme preferences, are stored securely in the browser's local storage and are never shared with external services.
* **About Section**: A modal provides information about the project and its creators, Team MCA from CUCEK Dept, CUSAT, Kerala.

## 🛠️ Technology Stack

* **Frontend**: HTML5, CSS3 (including a responsive layout and dark mode styling), and JavaScript (for all dynamic functionality).
* **Backend**: The application is a front-end-only project that connects to external AI services. There is no custom backend server.
* **APIs**:
    * **Google Gemini API**: Used for generating AI responses.
    * **OpenAI API**: An alternative option for the AI backend.
