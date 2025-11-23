🌟 AI Virtual Assistant – Shifra

A voice-enabled AI virtual assistant built using HTML, CSS, JavaScript, Web Speech API, 
capable of listening to voice commands, speaking responses, performing searches, and 
interacting with the user in real time.


🚀 Features

🎤 Speech Recognition – Listens to your voice commands using Web Speech API
🔊 Text-to-Speech – Speaks responses naturally
🤖 Smart Command Handling – Understands various commands like greetings, questions, and searches
🌐 Auto Google Search – Opens browser search results for any query
🎨 Modern UI – Includes glowing neon themes and assistant animation
⚡ Fully Browser-Based – No backend required
🕹️ Interactive Button Actions – Microphone button triggers listening mode🧠 How It Works

How It Works
✔ Listening
The Project uses:
let SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
let recognition = new SpeechRecognition();

When the user clicks the mic button, the assistant starts listening.

✔ Speaking

Uses:
let text = new SpeechSynthesisUtterance("Hello, how can I help you?");
speechSynthesis.speak(text);

✔ Google Search

If the user asks a question:
"Shifra what is JavaScript"
The assistant removes the name and opens:
https://www.google.com/search?q=what is javascript

🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Web Speech API (SpeechRecognition + SpeechSynthesis)
* Google Search Integration

view Project
https://ai-virtual-assistant-shifra.netlify.app/

🎯 How to Use

Open the project in your browser
Click the microphone button
Speak any command like:
* "Hi Shifra"
* "Shifra what is HTML"
* "Shifra open Google"
* "Shifra who are you"
* The assistant will listen, respond, and perform actions
