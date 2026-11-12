KRILLION — LOCAL GEMINI PROXY VERSION

WHY THIS VERSION IS DIFFERENT
The browser no longer calls Google's Gemini API directly. It calls a small local Node.js server at 127.0.0.1:3000. That server forwards the request to Google, avoiding the browser CORS problem.

REQUIREMENTS
- Node.js 18 or newer
- Internet access
- A Gemini API key from https://aistudio.google.com/app/apikey

WINDOWS SETUP
1. Extract this ZIP into a folder.
2. Open that folder in File Explorer.
3. Click the folder address bar, type cmd, and press Enter.
4. Run: node --version
   If Node is missing or the version is below 18, install a current Node.js LTS release from https://nodejs.org/ and reopen Command Prompt.
5. Run: node server.js
6. Keep that Command Prompt window open.
7. Open Chrome and visit http://127.0.0.1:3000
8. Paste your Gemini API key into Krillion and press Test Key.

IMPORTANT
- Do NOT double-click krillion.html. Open http://127.0.0.1:3000 instead.
- The API key is stored in this browser's localStorage, as in the original app. The browser sends it only to your local server; the local server forwards it to Google over HTTPS.
- server.js binds to 127.0.0.1 only, so it is not exposed to other computers on your network.
- Do not deploy this development proxy publicly as-is.
- If Test Key now shows an HTTP/API error (401, 403, 404, 429, etc.), the CORS transport problem is solved and the displayed Google error can be diagnosed separately.
