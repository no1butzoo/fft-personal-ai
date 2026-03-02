# Project Overview

## Features
- Countdown Timer: Keep track of time for various activities.
- Syllabus: Organize course materials and topics.
- Terminal Preview: Interactive shell experience within the browser.
- FAQ: Address common questions and concerns.
- Chatbot: Engage with users for assistance and information.

---

# Prerequisites
To get started, make sure you have the following:
- Node.js and npm installed (for development)
- A code editor (like VS Code)

## Setup Options
1. **Direct Browser**: 
   - Open `index.html` in your web browser to start using the application.

2. **Live Server**:
   - Use any live server extension from your code editor. This allows for hot-reloading.
   - Example: If you are using VS Code, the "Live Server" extension works great.

3. **Docker**:
   - Pull the Docker image:
     ```bash
     docker pull no1butzoo/fft-personal-ai
     ```
   - Run using:
     ```bash
     docker run -p 8080:80 no1butzoo/fft-personal-ai
     ```
   - Access via `http://localhost:8080`.

---

# Project Structure
```
fft-personal-ai/
├── index.html
├── css/
├── js/
├── assets/
└── README.md
```

---

# Feature Breakdown

## Countdown Timer
- Description: A dynamic timer that allows users to set and track events.

## Syllabus
- Description: A component that outlines the course materials and presents them in a structured manner.

## Terminal Preview
- Description: An interface that emulates terminal commands for learning and testing purposes.

## FAQ
- Description: A section dedicated to addressing common inquiries that users might have.

## Chatbot
- Description: An interactive model that answers questions and assists users in navigating the app.

---

# Deployment Options
- **GitHub Pages**: Host your static site directly from your GitHub repository.
- **Netlify**: Connect your repository for continuous deployment.
- **Vercel**: Similar to Netlify, but optimized for dynamic applications.

---

# Customization Guide
- Colors: Modify the CSS files under the `/css` directory.
- Content: Change texts directly in the HTML and JavaScript files.

---

# Browser Compatibility
This application is compatible with the latest versions of:
- Chrome
- Firefox
- Safari
- Edge

---

# Troubleshooting
- If the app does not display correctly, ensure all assets are loaded from the correct path.
- Clear your browser cache if you encounter any issues.

---

# License and Support
- This project is licensed under the MIT License.
- For support, please open an issue in the repository or contact the maintainer.