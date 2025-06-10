# AI Workbench

A simple web-based AI workbench featuring a chat interface and an image generation tool. This application allows users to interact with various AI models for text-based chat and to generate images from text prompts.

## Features

*   **AI Chat:** Engage in conversations with different AI models.
*   **Image Generation:** Create images from textual descriptions.
*   **User Authentication:** Secure login/logout functionality provided by Puter.js.
*   **Dynamic Model Selection:** Choose from a list of available AI chat models.

## Technologies Used

*   **HTML:** Structure of the web application.
*   **CSS:** Styling of the application (embedded in `index.html`).
*   **JavaScript:** Application logic and interactivity.
*   **[Puter.js](https://puter.com):** Handles user authentication and AI functionalities (chat, image generation).
*   **[Marked.js](https://marked.js.org/):** Parses Markdown for rendering AI chat responses.
*   **[DOMPurify](https://github.com/cure53/DOMPurify):** Sanitizes HTML output from Marked.js to prevent XSS attacks.

## Setup and Usage

1.  Clone this repository or download the `index.html` file.
2.  Open the `index.html` file in a modern web browser.
3.  Log in using the "Login" button to enable chat and image generation features.
4.  Select an AI model for chat from the dropdown menu.
5.  Start chatting or generate images using the respective tools.

## Security Note

AI responses in the chat are parsed as Markdown and sanitized using DOMPurify to prevent XSS vulnerabilities.
