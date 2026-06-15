# SyncMind

## AI-Powered Meeting Intelligence Platform

SyncMind transforms meeting recordings into structured, searchable, and actionable knowledge.

Instead of manually taking notes, creating meeting summaries, and tracking action items, SyncMind automatically processes meeting audio or video recordings and generates insights that teams can immediately use.

---

## Key Features

### Intelligent Meeting Transcription

Convert audio and video recordings into accurate text transcripts using advanced speech recognition models.

### Executive Summarization

Generate concise summaries that capture key discussions, decisions, and outcomes.

### Action Item Extraction

Automatically identify tasks, responsibilities, deadlines, and commitments mentioned during meetings.

Example:

* Manav will fix the backend API by Tuesday.
* Design team will review the dashboard mockups before Friday.

### Context-Aware Meeting Chat

Ask questions directly about meeting content.

Examples:

* Why was PostgreSQL selected?
* What deployment strategy was discussed?
* Who owns the authentication module?

### Audio Summary Generation

Convert summaries into speech for quick review and accessibility.

---

## Business Impact

### Preserve Organizational Knowledge

Store important decisions and discussions instead of losing them after meetings end.

### Increase Productivity

Eliminate manual note-taking and automate meeting documentation.

### Accelerate Onboarding

Help new team members understand historical decisions without requiring extensive knowledge-transfer sessions.

### Improve Team Alignment

Create a single source of truth for meeting outcomes and action items.

---

## Tech Stack

### Backend

* FastAPI
* Groq API
* Whisper Large V3
* Llama 3.3
* Pyttsx3
* MoviePy
* Pydub

### Frontend

* React
* Axios
* Framer Motion
* ShadCN UI
* Lucide React Icons

---

## System Workflow

1. Upload a meeting recording.
2. Extract audio and generate a transcript.
3. Create an executive summary.
4. Extract action items.
5. Ask contextual questions about the meeting.
6. Generate audio summaries.

---

## Future Enhancements

### Persistent Storage

Store meeting transcripts and summaries using PostgreSQL and SQLAlchemy.

### Historical Search

Search across previous meetings and organizational knowledge.

### PDF Export

Generate professional meeting reports and action-item summaries.

### Team Dashboard

Manage and review meeting history from a centralized interface.

### Meeting Analytics

Track recurring action items, participation trends, and decision patterns.

---

## Vision

SyncMind aims to become an AI-powered organizational memory system that transforms conversations into structured, searchable, and actionable knowledge.

By combining speech recognition, large language models, and workflow automation, SyncMind helps teams spend less time documenting meetings and more time executing decisions.
