# FutureMe

**Meet the version of you who already made it.**

FutureMe is a single-page web application designed to act as an AI reflection tool. It allows you to visualize and interact with your "future self", helping you align your current habits with your future goals.

## Features

- **Immersive Interface:** A sleek, dark-themed UI featuring glassmorphism and smooth micro-animations.
- **Future Chat:** Interact with a simulated future version of yourself to gain perspective and motivation.
- **The Vault (Journaling):** Keep track of your daily reflections and milestones.
- **Local Storage:** All identity, vault, and chat state is stored securely in your browser's local storage—no backend required.

## Tech Stack

- **HTML5:** Semantic structure.
- **CSS3:** Custom styles, CSS variables, glassmorphism effects, and animations (no external frameworks).
- **Vanilla JavaScript:** DOM manipulation, state management (via `localStorage`), and interactive elements.

## Getting Started

### Prerequisites

You only need a modern web browser and a local web server to run this application.

### Running Locally

1. Clone or download the repository.
2. Navigate to the project directory.
3. Start a local web server. If you are on Windows and have PowerShell, you can use the included script:
   ```powershell
   .\serve.ps1
   ```
   Alternatively, you can use any other local server, such as Python's `http.server` or Node's `http-server`, or the Live Server extension in VS Code.
4. Open your browser and go to `http://localhost:8000` (or whichever port your server uses).

## Deployment

FutureMe is ready to be deployed as a static site. You can easily host it on platforms like **Netlify**, **Vercel**, or **GitHub Pages**.

To deploy on Netlify:
1. Build your project into a zip file (or just zip the project directory).
2. Go to the [Netlify Drop](https://app.netlify.com/drop) page.
3. Drag and drop your project folder or zip file.

## Author
Built by **Anil**.
