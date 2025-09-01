 🤖 AI-CODE-REVIEWER WebApp

An interactive **React-based code review tool** where you can write or paste code, send it to an AI backend for analysis, and get feedback rendered in beautiful Markdown with syntax highlighting.

---

## 🚀 Features
- 📝 **Live Code Editor** with syntax highlighting (powered by [react-simple-code-editor](https://github.com/react-simple-code-editor) + [PrismJS](https://prismjs.com/)).
- 🤖 **AI-Powered Reviews**: Sends your code to a backend endpoint (`/ai/get-review`) for AI analysis.
- 🖋 **Markdown Rendering** for human-readable feedback (supports lists, bold/italic text, etc.).
- ⚡ **Fast & Lightweight** setup with Vite.

---

## 🛠️ Tech Stack
- **Frontend**: React + Vite  
- **Editor**: react-simple-code-editor  
- **Syntax Highlighting**: PrismJS  
- **Markdown Rendering**: react-markdown (+ remark-gfm, rehype-highlight)  
- **HTTP Requests**: Axios  

---

## 📂 Project Structure
.
├── src/
│ ├── App.jsx # Main React component
│ ├── App.css # Styling
│ ├── main.jsx # Entry point
│ └── ...
├── package.json
└── README.md
