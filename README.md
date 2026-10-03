# ⚡ DoubtBuster AI — Multimodal Academic Tutor

DoubtBuster AI is an intelligent study buddy web application built with Streamlit and Google Gemini (`gemini-2.5-flash`). Students can snap photos of diagrams, handwritten notes, formulas, or textbook exercises to receive instant step-by-step solutions and explanations. Once finished, a single click delivers a clean revision digest straight to their email inbox.

## ✨ Highlights & Features
- **Visual Doubt Buster**: Understands complex diagrams, equations, and textbook excerpts using multimodal AI.
- **Quick Action Triggers**: 1-click actions to explain diagrams, show step-by-step solutions, or generate practice questions.
- **Difficulty Tagging**: Dynamically tags responses with a difficulty rating (Beginner, Intermediate, Advanced).
- **Session Sidebar**: Shows live student details, usage tips, and provides a quick session reset button.
- **Email Digest**: Formats and emails a structured revision sheet using Python's `smtplib`.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **AI Model**: Google Gemini API (`gemini-2.5-flash` via `google-genai` SDK)
- **Delivery Service**: Python `smtplib` (Gmail SSL)

## 🚀 Setup & Local Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/doubtbuster-ai.git
   cd doubtbuster-ai