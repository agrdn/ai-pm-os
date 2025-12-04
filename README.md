<p align="center">
  <img src="https://img.shields.io/badge/Built_for-Product_Managers-6366f1?style=for-the-badge" alt="Built for PMs"/>
  <img src="https://img.shields.io/badge/Works_with-Obsidian-7c3aed?style=for-the-badge" alt="Obsidian"/>
  <img src="https://img.shields.io/badge/Syncs_via-iCloud-3b82f6?style=for-the-badge" alt="iCloud"/>
  <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge" alt="MIT License"/>
</p>

<h1 align="center">🧠 AI PM OS</h1>

<p align="center">
  <strong>Your personal AI-powered knowledge system for product management.</strong><br/>
  Capture messy meeting notes → Get structured insights → Build institutional memory.
</p>

<p align="center">
  <a href="#-the-idea">The Idea</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-how-it-works">How It Works</a> •
  <a href="#-commands">Commands</a> •
  <a href="#-tips">Tips</a>
</p>

---

## 💡 The Idea

Most PM knowledge lives in your head. Meetings happen, decisions get made, context gets lost.

**AI PM OS changes that.**

```
📱 Capture notes on your phone (Obsidian)
       ↓
☁️  Auto-sync via iCloud
       ↓
🤖 Tell AI: "Process my notes"
       ↓
📚 Knowledge base grows automatically
       ↓
🧠 AI becomes your thought partner
```

After a few weeks, you have:
- Every decision logged with reasoning
- Stakeholder context at your fingertips
- Patterns you'd never notice manually
- An AI that actually knows your product

---

## 🚀 Quick Start

### 1. Download & Setup

```bash
# Clone the repo
git clone https://github.com/agrdn/ai-pm-os.git

# Or download ZIP and extract to your Obsidian vault
```

### 2. Set Your Goals

Edit `GOALS.md` with your priorities. This is your north star — AI uses it to understand what matters.

### 3. Start Capturing

Drop notes into `Raw notes/`. Use your phone, laptop, whatever. Just capture.

### 4. Process with AI

Open in Cursor (or your AI editor) and say:

> "Process my meeting notes"

Watch your knowledge base grow. 🌱

---

## 📁 How It Works

```
AI_PM_OS/
│
├── 📥 Raw notes/           # Your inbox — dump messy notes here
│   └── _TEMPLATE.md        # Quick capture guide
│
├── 📚 Knowledge/           
│   ├── 🔥 Context/         # AI updates these automatically
│   │   ├── decisions.md    # Every decision + reasoning
│   │   ├── projects.md     # Project status & blockers
│   │   ├── people.md       # Stakeholder context & patterns
│   │   └── threads.md      # Recurring themes & issues
│   │
│   └── 🧊 Reference/       # Your stable docs (PRDs, specs, research)
│
├── 📦 Archive/             # Processed meeting notes
│
├── 🎯 GOALS.md             # Your priorities (edit this!)
├── ⚙️ SYSTEM.md            # AI instructions
└── 📖 README.md            # You are here
```

### The Magic

| Folder | What Happens |
|--------|--------------|
| **Raw notes/** | You dump messy notes here. Voice memos, quick thoughts, meeting chaos. |
| **Knowledge/Context/** | AI extracts structure — decisions, people, projects, patterns. |
| **Knowledge/Reference/** | You upload stable docs. AI reads them for context. |
| **Archive/** | Processed notes get saved here as your searchable history. |

---

## 🎮 Commands

Tell your AI assistant:

| Command | What Happens |
|---------|--------------|
| **"Process my meeting notes"** | Extracts insights from Raw notes → updates Knowledge |
| **"What should I focus on?"** | Prioritized suggestions based on your Goals |
| **"Prep me for [meeting]"** | Pulls relevant context + talking points |
| **"What did we decide about X?"** | Searches your decision history |
| **"Update [project/person]"** | Helps you update specific context |

---

## ✍️ Capture Shorthand

Use these in your notes for faster capture:

```
DEC: → Decision made        @name → Person mentioned
?    → Question/unclear     TODO  → Action item
!    → Important            RISK  → Blocker/concern
>>   → Follow-up needed     ~~    → Changed from before
```

### Example Raw Note

```markdown
# Sprint Planning - Dec 4

@sarah wants eval component done by dec 15
DEC: push auth to Q1, focus RAG instead
@mike worried about data pipeline - "could slip 2 weeks"
! budget still not approved - blocking hiring
TODO update data team on timeline change
? why did we skip dashboard - seemed important before

## My gut feel
Good alignment on priorities. Mike seems stressed.
```

---

## 📈 The Growth Cycle

| After... | Your Knowledge Base Has... |
|----------|---------------------------|
| **1-2 meetings** | Basic decision log, first stakeholder notes |
| **5 meetings** | Useful project tracking, emerging patterns |
| **10+ meetings** | Rich context, pattern recognition, real thought partner |

The more you use it, the smarter it gets.

---

## 💡 Tips

### For Voice Notes (Phone)

- **Speak naturally** — AI structures it later
- **Name names** — "Sarah said..." not "someone mentioned..."
- **State decisions** — "We decided X because Y"
- **Capture gut feelings** — "Meeting felt tense"

### For Written Notes

- **3-second rule** — Important? Write immediately
- **Name everything** — `@mike: pipeline risk`
- **Write questions** — `? why are we doing this`
- **Post-meeting dump** — Spend 2 min adding what you remember

### For Best Results

- Process notes within 24 hours while context is fresh
- Review `GOALS.md` monthly and update priorities
- Check `threads.md` weekly to catch recurring issues
- Add reference docs to `Knowledge/Reference/` for richer context

---

## 🛠️ Setup Options

### Option A: Obsidian + iCloud (Recommended)

1. Install [Obsidian](https://obsidian.md) on phone + computer
2. Put this folder in iCloud Drive
3. Open as vault in Obsidian on both devices
4. Notes sync automatically ✨

### Option B: Any Markdown Editor

Works with any setup that syncs markdown files:
- VS Code + Git
- Notion (export to markdown)
- Bear, iA Writer, etc.

### Option C: Just Cursor

Keep everything local, process notes directly in Cursor with AI.

---

## 🤝 Contributing

Found a bug? Have an idea? PRs welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

MIT License — use it, modify it, share it. See [LICENSE](LICENSE) for details.

---

<p align="center">
  <strong>Built for PMs who need a thought partner that remembers everything.</strong>
</p>

<p align="center">
  <sub>Star ⭐ this repo if it helps you!</sub>
</p>
