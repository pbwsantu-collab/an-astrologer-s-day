📖 An Astrologer's Day — Interactive English Learning Engine
A single-file, browser-based English learning application built around R. K. Narayan's An Astrologer's Day.
This project is designed as a textual learning engine, not simply an eBook. Students can read the lesson, explore vocabulary, study English-to-Bengali meanings, practise grammar, understand context and inner meaning, and test themselves with MCQs.
✨ Features
📖 Interactive textual reading
🔤 Clickable vocabulary
🇬🇧 English meaning →  Bengali meaning
🔊 Browser-based pronunciation
📌 Contextual explanation
💡 Inner/contextual meaning
📚 Vocabulary search
✍️ Grammar from the text
🧠 Literary analysis
👤 Character and theme sections
🎯 MCQ quiz with score
📝 Answer-writing practice
📱 Responsive mobile interface
💾 LocalStorage for quiz score
🚀 No backend required
🛠️ Technology
The current version uses only:
HTML5
CSS3
Vanilla JavaScript
Browser Speech Synthesis API
LocalStorage
No React, Node.js, npm, Vite, database, or API key is required.
📁 Files
The simplest repository is:
/
├── index.html
└── README.md
The complete learning engine can live inside index.html.
▶️ Run Locally
Download the HTML file.
Rename it to index.html.
Open it in Chrome, Edge, Firefox, or another modern browser.
🌐 GitHub Pages
Create a GitHub repository.
Upload index.html.
Upload this README.md.
Enable GitHub Pages.
Select the repository branch/folder requested by GitHub.
Open the generated Pages site.
Because this is a static HTML application, no server is required.
📱 Mobile
The interface is responsive and designed for phones, tablets, and desktops.
The pronunciation feature uses the browser's built-in speech synthesis where supported.
📚 Current Learning Modules
Text
The lesson is displayed as interactive text. Important words can be tapped to open their learning information.
Vocabulary
A vocabulary item can contain:
English meaning
Bengali meaning
Part of speech
Story context
Inner significance
Pronunciation
Analysis
About the author
About the text
Summary
Central ideas
Themes
Characters
Significance of the title
Grammar
The prototype includes grammar points based on sentences from the lesson, with scope for substantial expansion.
MCQ
Multiple-choice questions
Immediate feedback
Score tracking
Repeated practice
Answer Practice
Students can write an answer and receive a basic keyword-based self-check.
🔮 Future Expansion
The current application is Version 1 / Prototype. The engine can be expanded considerably.
Maximum Vocabulary Coverage
A full vocabulary record can contain:
Word
├── Pronunciation
├── English meaning
├── Bengali meaning
├── Part of speech
├── Synonyms
├── Antonyms
├── Word family
├── Example sentence
├── Context
├── Bengali contextual explanation
└── Exam relevance
Sentence-Level Learning
Each important sentence can contain:
Sentence
├── Simple English explanation
├── Bengali explanation
├── Context
├── Inner meaning
├── Grammar analysis
├── Important vocabulary
└── Questions
Question Bank
Future versions can include:
MCQ
1-mark questions
Short-answer questions
Long-answer questions
Extract-based questions
Vocabulary questions
Grammar questions
Inferential questions
Model tests
Advanced Practice
Possible future features:
Random quizzes
Difficulty levels
Wrong-answer revision
Timed tests
Progress tracking
Topic-wise tests
Search across all learning content
🎯 Design Philosophy
The central idea is:
One literary text
        ↓
Reading
        ↓
Vocabulary
        ↓
English → Bengali
        ↓
Context
        ↓
Inner Meaning
        ↓
Grammar
        ↓
Literary Analysis
        ↓
Questions
        ↓
MCQs
        ↓
Revision
        ↓
Mock Test
Instead of treating a chapter as a static eBook, the same text becomes the foundation for multiple layers of learning.
🧩 Reusable Engine
The engine can eventually be reused for other chapters.
For example:
const story = [ ... ];
const vocab = { ... };
const grammar = [ ... ];
const questions = [ ... ];
The interface and engine can remain largely unchanged while the content database is replaced.
This makes the project potentially useful as a reusable English chapter learning engine.
⚠️ Content Accuracy
The project should distinguish between:
Source text
Factual information
Literary interpretation
Study-guide explanations
Exam-oriented model answers
Study-guide material should not automatically be treated as authoritative fact. Where interpretations differ, the learning system should identify the distinction clearly.
📌 Project Status
Status: Prototype / Version 1
The current version demonstrates the core concept of a single-file interactive textual English learning book.
The content database can be expanded without changing the fundamental architecture.
👨‍🏫 Intended Educational Use
The application is intended as a supplementary learning tool for English literature and can support:
Classroom teaching
Self-study
Vocabulary building
Bengali-medium learners
Grammar practice
Literary analysis
Examination preparation
Revision
Quiz practice
🌱 Vision
The long-term goal is to create a reusable system where a teacher supplies the prescribed text and supporting study materials, and the engine turns them into a structured interactive learning environment.
Read → Tap → Understand → Practise → Test → Revise
📜 Content Notice
The application code can be customised according to the repository owner's needs.
Literary text, textbook material, guide content, translations, and other third-party materials may have separate copyright or usage restrictions. Use only content that you have permission to reproduce or distribute.
