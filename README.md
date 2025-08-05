# ✨ AI-Powered Collaborative Content Creation Platform

A feature-rich, collaborative text editor designed to supercharge the writing experience by blending real-time collaboration with intelligent AI tools. Think of it as a **next-gen Google Docs**, where multiple users can edit simultaneously while leveraging cutting-edge AI for writing, editing, analysis, and creativity.

---

## 🔑 Key Features

### 📝 Collaborative Real-Time Text Editor
- **Live Syncing:** Built using WebSockets to instantly broadcast edits across all connected users in a document room.
- **Rich Text Formatting:** Powered by **Quill.js** with support for headers, fonts, colors, lists, image embedding, and more.
- **Document Sharing:** Share documents via email invites directly from the platform.
- **PDF Export:** Download your content as a professionally formatted PDF.

---

### 🤖 AI-Powered Writing Assistant
- **Automatic Suggestions:** AI suggests better phrasing for recent lines — one-click to accept.
- **Content Enhancement:** Rewrite any section or the whole document to make it clearer, more professional, or more engaging.
- **Sentiment Analysis:** Instantly understand the tone of your writing.
- **Poetic & Script Transformations:** Reimagine your content as poetry or screenplay format.
- **Text-to-Image Generation:** Create images from your descriptions using an integrated AI model.

---

### 🎤 Speech-to-Text with AI Enhancement
- **Live Transcription:** Real-time speech-to-text using the browser’s Speech Recognition API.
- **AI Refinement:** Clean up and improve transcribed content using AI post-processing.

---

### 📂 Version Control & Document Management
- **Auto-Saving:** Work is saved every 30 seconds to prevent data loss.
- **Version History:** Manually save document milestones with custom titles and timestamps.
- **Restore Versions:** View or revert to any previous version with a single click.

---

## 💻 Tech Stack & Architecture

| Layer         | Technology Used                                  |
|---------------|--------------------------------------------------|
| **Frontend**  | React.js, Quill.js, Tailwind CSS, Socket.io-client |
| **Backend**   | Node.js, Express.js, Socket.io                   |
| **Database**  | MongoDB with Mongoose                            |
| **AI Engine** | Python (FastAPI, Flask), Google Gemini API       |

---

## 🚀 Future Enhancements
- **User Roles & Permissions:** Owner, Editor, and Viewer roles for better control.
- **Folder Organization:** Group documents in folders for easier management.
- **In-Document Commenting:** Add contextual comments for collaborative editing.
- **Advanced Analytics:** Track writing trends, reading time, and sentiment over time.

---

