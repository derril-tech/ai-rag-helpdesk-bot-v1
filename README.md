# 🤖 AI RAG Helpdesk Bot
**with LangGraph AI Agents**


> **Enterprise-ready AI helpdesk that answers support questions using LangGraph-powered RAG over your Notion docs. Get accurate answers with citations and guardrails—instantly.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-15.1-black.svg)](https://nextjs.org/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)

---

## ✨ Features

### 🎯 **Core Functionality**
- 🤖 **Intelligent Q&A** - Ask natural-language questions about your helpdesk
- 📚 **RAG over Notion** - Answers grounded in your Notion knowledge base
- 🔗 **Citation Tracking** - See which Notion pages were used for each answer
- 🎙️ **Voice Input** - Speak your questions with Web Speech API
- 🔄 **Regenerate Answers** - Try again if the answer isn't quite right
- 💡 **Suggested Follow-ups** - AI generates relevant next questions

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism, video backgrounds, micro-animations
- 🌙 **Dark Mode** - Full theme support with smooth video transitions
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile
- ⌨️ **Keyboard Shortcuts** - Power-user features (Ctrl+K, Ctrl+/, Enter)
- 🎯 **Intuitive Interface** - Single-page app with elegant state transitions

### 📊 **Dashboard Features**
- 📈 **Usage Analytics** - Query volume, success rate, and performance metrics
- 📝 **Conversation History** - View all previous questions and answers
- 🔍 **Real-Time Stats** - Total conversations, average response time
- 💾 **Persistent Storage** - All conversations saved to Supabase
- 📊 **Per-Project Tracking** - Multi-project support with isolated analytics

### 🚀 **Advanced Features**
- 🎯 **LangGraph Pipeline** - 4-node RAG workflow (embed → retrieve → answer → guardrails)
- 🔒 **Built-in Guardrails** - Safety checks and content filters
- 📋 **Export Chat History** - Download conversations as Markdown
- 🔄 **Background Job System** - Real-time polling for async processing
- 🎚️ **Customizable** - Configurable retrieval, answer length, and safety rules

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **LangGraph** - AI agent orchestration and RAG pipeline
- **OpenAI API** - GPT-4.1-mini for chat + text-embedding-3-small
- **Python 3.11+** - Latest features and performance

### **Frontend** ⚛️
- **Next.js 15.1** - React 19 with App Router
- **Tailwind CSS** - Utility-first styling with custom glassmorphism
- **shadcn/ui** - Beautiful component library
- **Lucide Icons** - Modern icon set

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with real-time capabilities (schema: `helprag`)
- **Upstash Redis** - Serverless job queue & caching (prefix: `helprag`)

### **External APIs** 🔌
- **Notion API** - Knowledge base synchronization
- **OpenAI Embeddings** - Vector search for document retrieval

### **Deployment** 🚀
- **Railway** - Backend API deployment
- **Vercel** - Frontend deployment
- **Full CI/CD** - Automatic deployments on push

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Ask Your Question**
   - 💬 **Type** - Enter your question in the chat input
   - 🎙️ **Speak** - Click the microphone to use voice input

2. **Get AI Answer**
   - ⚡ **Real-time** - See the answer appear with typing indicator
   - 🔗 **Citations** - Click citation chips to see source pages
   - 💡 **Follow-ups** - Click suggested questions to continue

3. **Interact with Results**
   - 📋 **Copy** - Copy answer to clipboard with one click
   - 🔄 **Regenerate** - Try again for a better answer
   - 📥 **Export** - Download full chat history as Markdown

4. **Keyboard Shortcuts**
   - `Enter` - Send message
   - `Ctrl+K` - Focus input
   - `Ctrl+/` - View all shortcuts

5. **Manage History**
   - 🗑️ **Clear** - Remove all messages from current session
   - 💾 **Auto-save** - History persists in localStorage

### 📊 Using the Dashboard

1. **View Analytics**
   - Total conversations processed
   - Average response time
   - Success rate metrics

2. **Browse History**
   - Recent conversations with timestamps
   - Question preview and answer snippet
   - Click to view full conversation

3. **Track Performance**
   - Query volume over time
   - Top questions and patterns
   - Per-project statistics

---

## 🎨 Customization

### Theme Options
- ☀️ **Light Mode** - Clean interface with dark glass chat panel
- 🌙 **Dark Mode** - Cross-fading video backgrounds with elegant gradients
- 🖥️ **System** - Follows OS preference automatically

### Chat Options
- **Voice Input** - Toggle microphone on/off
- **Auto-scroll** - Automatically scroll to latest message
- **Follow-ups** - Show/hide suggested questions

### RAG Configuration (Backend)
- **Retrieval Count** - Number of Notion pages to retrieve (default: 5)
- **Answer Length** - Max tokens for answer generation
- **Guardrails** - Enable/disable safety filters

---


---

## 👨‍💻 Creator

**Created by Derril Filemon**
---

## 🙏 Acknowledgments

- **LangGraph** - For powerful AI agent orchestration
- **OpenAI** - For GPT-4.1-mini and embeddings API
- **Notion** - For flexible knowledge base API
- **Supabase** - For database & real-time capabilities
- **Upstash** - For Redis caching
- **Railway** - For seamless deployment
- **Vercel** - For Next.js hosting
- **shadcn/ui** - For beautiful components

---


<div align="center">

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
