✨ Gemini Content Generator (Browser-Only React App)

This is a single-file, zero-setup web application built with React and Tailwind CSS that utilizes the Gemini API to generate grounded, factual content based on user prompts.

The entire application—including the React component logic, all dependencies (React, Babel, Tailwind), and custom mouse-driven parallax animations—is contained within a single HTML file. No build tools or Node.js are required to run it.

🚀 Getting Started

Clone the Repository:

git clone [your-repo-link]

Get Your API Key: Obtain a Gemini API Key from Google AI Studio.

Configure the Application: Open the index.html file in a text editor. Find the following line near the top of the main script block:

const apiKey = "";

Replace the empty quotes with your API key:

const apiKey = "YOUR_PASTED_API_KEY_HERE";

Run Locally: Simply double-click the index.html file. It will open directly in your web browser (Chrome, Firefox, etc.) and is ready to use.

🛠️ Technology Stack

Frontend: React (loaded via CDN)

Compiler: Babel (loaded via CDN, compiles JSX in the browser)

Styling: Tailwind CSS (loaded via CDN)

API: Gemini API (gemini-2.5-flash-preview-09-2025)
