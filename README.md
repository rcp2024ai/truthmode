# ⚡ TRUTHMODE

> **Your thinking. Organized.**  
> A voice-first personal thinking and content intelligence system.

TRUTHMODE captures what you say, extracts the valuable cognitive insights, organizes it automatically into your personal knowledge base, and builds a searchable personal dataset ready to turn into content.

---

## 🎯 The Core Product Loop

```
🎙️ Voice Capture
       │
       ▼
⚡ Single-Pass Gemini Multimodal Extraction
       │ (Transcript + Summary + Core Insight + Taxonomy + Tags + TRUTH SCORE™)
       ▼
🗄️ Local IndexedDB Knowledge Base (Offline, Private, Zero-Latency)
       │
       ├── 🔍 "My Thoughts" Library (Real-time Search & Filter)
       ├── 🧭 Discover Engine (Recurring Themes & Content Clusters)
       └── 📤 Portability (1-Click Markdown & JSON Export)
```

---

## ✨ Features

- **One-Tap Voice Capture (`MediaRecorder`)**: Record naturally without worrying about structure. Includes live audio waveform indicator, timer, and in-app audio playback.
- **Single-Pass Gemini Multimodal Processing**: Directly analyzes raw audio recordings without needing a separate speech-to-text service.
- **Cognitive Taxonomy**: Automatically classifies thoughts into 8 distinct cognitive types:
  - 💡 `IDEA`
  - 🔍 `INSIGHT`
  - 📖 `STORY`
  - ⚠️ `PROBLEM`
  - 🛠️ `SOLUTION`
  - 🗣️ `OPINION`
  - 🎓 `LESSON`
  - ❓ `QUESTION`
- **TRUTH SCORE™ (0–100)**: Proprietary content-potential scoring evaluated across *Originality*, *Specificity*, *Point of View*, and *Reusability*.
- **Local-First & Private**: Powered by IndexedDB directly on your device. Zero server costs, zero storage quota limits, and 100% private.
- **Discover & Content Clusters**: Automatically surfaces recurring themes and analyzes multi-thought connections for larger newsletters, articles, or frameworks.
- **Data Portability**: Instant export to clean Markdown (ready for Obsidian/Notion) or JSON.
- **PWA Ready**: Installable directly to your iOS or Android home screen with offline caching.

---

## 🚀 Quick Start (Local Run)

No build steps or Node dependencies required.

1. Clone or download the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/truthmode.git
   cd truthmode
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Safari, Brave):
   - Double-click `index.html` or run a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   ```
3. Navigate to `http://localhost:8000`.

---

## 📱 Deploy as a Mobile App (GitHub Pages in 60 Seconds)

1. Push this repository to GitHub.
2. Go to your repository on GitHub and click **Settings**.
3. Under the **Code and automation** section in the left sidebar, click **Pages**.
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **`main`** / **`/ (root)`**
5. Click **Save**.
6. GitHub will provide your live URL (e.g., `https://YOUR_USERNAME.github.io/truthmode/`).
7. **Install on Phone**:
   - **iPhone (Safari)**: Open the link $\rightarrow$ Tap the **Share** button $\rightarrow$ Tap **Add to Home Screen**.
   - **Android (Chrome)**: Open the link $\rightarrow$ Tap the **Three Dots Menu** $\rightarrow$ Tap **Install App** / **Add to Home screen**.

---

## 🔑 API Key Configuration

TRUTHMODE can use the active runtime environment key, or you can supply your own Google AI Studio key:
1. Open the app $\rightarrow$ Tap the **Settings** tab.
2. Paste your Google AI Studio API key (from [aistudio.google.com/apikey](https://aistudio.google.com/apikey)).
3. Tap **Save**. The key is stored locally in your browser's private storage.

---

## 🗺️ Roadmap

- [x] **Phase 1: MVP Core** (Voice capture, Gemini multimodal extraction, IndexedDB library, TRUTH SCORE™, Discover engine, Markdown export)
- [ ] **Phase 2: Content Studio** (Multi-thought selection $\rightarrow$ Generate LinkedIn posts, newsletters, video outlines grounded in your dataset)
- [ ] **Phase 3: "My Voice" Profile** (Adaptive stylistic learning based on your accumulated thoughts)

---

## 📄 License

MIT License — Feel free to customize and expand for your personal workflows.
