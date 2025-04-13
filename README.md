# PE-Project-2-StyleShift: AI Text Transformer
Overview
StyleShift is a modern web application that transforms your text into different writing styles using AI technology. Simply input your text, select a style, and watch as the application converts your writing to match your chosen format - from poems and academic papers to tweets and code comments.

Features
Multiple Text Styles: Transform your text into various formats including poems, explanations, summaries, code comments, tweets, academic papers, and short stories
Instant Transformation: See results immediately after submission
Copy to Clipboard: Easily copy transformed text with a single click
Fallback Mechanism: Works even when the OpenAI API is unavailable
Token Counter: See the approximate token usage of your transformations
Mobile Responsive: Use on any device with a clean, responsive interface
Technologies Used
Frontend: React, TypeScript, Tailwind CSS
UI Components: ShadCN component library
Backend: Node.js with Express
API Integration: OpenAI GPT API
State Management: React Hooks and Context
Installation
Prerequisites
Node.js (version 18 or 20)
npm (comes with Node.js)
Setup Instructions
Clone the repository:
git clone https://github.com/HarshKamat/PE-Project-2-StyleShift-AI-Text-Transformer.git
cd PE-Project-2-StyleShift-AI-Text-Transformer
Install dependencies:
npm install
Create a .env file in the root directory with your OpenAI API key:
OPENAI_API_KEY=your_openai_api_key_here
Note: The application includes a fallback mechanism and will still work without an API key, but with simulated responses.

Start the development server:
npm run dev
Open your browser and navigate to:
http://localhost:5000
Usage Guide
Enter your text in the input field
Select a transformation style from the dropdown menu
Click the "Generate" button
View the transformed text in the output panel
Use the copy button to copy the result to your clipboard
Customization
Adding New Styles
To add new transformation styles, edit the following files:

client/src/lib/styleOptions.ts - Add new style options
server/openai.ts - Add corresponding prompts and fallback transformers
Modifying the UI
Components are located in client/src/components/
Styles are applied using Tailwind CSS classes
License
MIT License

Acknowledgements
Built with OpenAI's GPT API
UI components from ShadCN UI
Icons from Lucide React
Created by HarshKamat 
