---
id: 7bf03171-3ad3-434a-807a-466638d554a7
sortOrder: 11
created: 2026-02-15T20:48:23.223Z
modified: 2026-02-15T20:48:23.223Z
---
# Situational Gita Article Generator & Book Creator

> Transform ancient Gita wisdom into unique, modern articles with AI-powered variety
>
> **Now with bestseller book strategy included!**

An intelligent system that generates empathetic articles about Bhagavad Gita teachings for modern life. Each article uses a different narrative structure from a library of 12 storytelling frameworks, ensuring every piece feels fresh and engaging.

Perfect for creating individual articles OR compiling into a complete book.

## ✨ Key Features

- **110 Life Situations**: Complete coverage from the Situational Gita book
  - 62 general life themes (Anger, Depression, Loneliness, etc.)
  - 48 chapter-specific spiritual topics (Liberation, The three gunas, etc.)
- **12 Narrative Strategies**: Each article uses a different storytelling approach
- **Book-Ready Output**: Optimized for bestseller book compilation
- **Intelligent Matching**: Themes automatically paired with suitable strategies
- **Style Compliance**: Follows Light of Dharma writing guidelines
- **Variation System**: 6,000+ possible combinations prevent repetitive writing
- **Hugo-Ready**: Articles generated with proper frontmatter
- **Two Usage Modes**: Claude Code (easy) or Standalone scripts (automation)

## 🚀 Quick Start (2 Steps)

### Option 1: Using Claude Code (Recommended - No API Key Needed!)

```bash
# 1. Extract content (first time only, takes 2-3 minutes)
python3 extract_themes.py

# 2. Generate articles by talking to Claude
# Just say: "Generate an article about Anger"
```

That's it! No API key, no costs, same quality.

### Option 2: Using Standalone Scripts (For Automation)

```bash
# 1. Install dependencies
pip3 install anthropic

# 2. Set API key
export ANTHROPIC_API_KEY='your-api-key-here'

# 3. Extract content
python3 extract_themes.py

# 4. Run interactive UI
python3 gita_ui.py
```

## 📖 Usage Examples

### Using Claude Code (Conversational)

```
You: "Generate an article about Anger"
Claude: [Generates using Single Day strategy, saves to articles/anger.md]

You: "Generate 5 articles: Depression, Loneliness, Fear, Pride, Confusion"
Claude: [Generates all 5 with different strategies]

You: "Show me which strategy would work best for Death of a loved one"
Claude: [Shows Observer Witness strategy, explains why]

You: "Generate an article about Boss using Dialogue-Driven strategy"
Claude: [Generates with specific strategy]
```

### Using Standalone Scripts

```bash
# Interactive menu (easiest)
python3 gita_ui.py

# Command line - Single article
python3 article_generator.py --theme "Anger"

# Batch generation
python3 article_generator.py --batch --limit 10

# Random strategies
python3 article_generator.py --batch --limit 5 --random-strategy
```

## 🎭 The 12 Narrative Strategies

Each article uses one of these unique storytelling approaches:

| Strategy | Description | Best For |
|----------|-------------|----------|
| **Dual Narrative** | Two parallel stories showing contrast | Ambition, Achievement |
| **Reverse Chronology** | Start with crisis, trace backwards | Depression, Grief |
| **Observer Witness** | Told through someone watching | Death, Loss |
| **Single Day** | 24-hour compressed narrative | Anger, Temptation |
| **Dialogue-Driven** | Story through conversations | Boss, Family, Teams |
| **Recursive Loop** | Pattern repeating with variations | Laziness, Habits |
| **Letter/Confession** | First-person direct address | Loneliness, Shame |
| **Before/After** | Transformation snapshots | Change, Growth |
| **Multiple Vignettes** | Several brief stories | Family, Universal themes |
| **Question Investigation** | Exploring a question | Confusion, Identity |
| **Case Study** | Clinical examination | Complex patterns |
| **Seasonal Journey** | Story across time | Spiritual journey |

**Plus**: 10 opening hooks × 5 pacing styles × 10 section naming approaches = **6,000+ variations!**

### Preview Strategies

```bash
# See all strategies and sample blueprints
python3 narrative_strategies.py

# Or ask Claude: "Show me narrative strategies for Fear"
```

## 📁 Project Structure

```
situational_gita/
│
├── 📚 Documentation
│   ├── README.md .................. Quick overview (this file)
│   ├── QUICK_START.md ............. Fast setup guide
│   ├── COMPLETE_GUIDE.md .......... Everything explained
│   ├── SYSTEM_EXPLANATION.md ...... How it all works
│   └── WRITING_STYLE_GUIDE.md ..... Style rules
│
├── 📖 Source
│   ├── situational_gita.pdf ....... Original book
│   └── situational_gita.txt ....... Converted text (267KB)
│
├── 🔧 Core System
│   ├── extract_themes.py .......... Extract 60 themes & content
│   ├── narrative_strategies.py .... 12 storytelling frameworks
│   ├── article_generator.py ....... AI-powered generator
│   └── gita_ui.py ................. Interactive menu
│
├── 💾 Data
│   ├── comprehensive_gita_data.json  Extracted content
│   └── articles/ .................. Generated articles
│
└── 📦 Distribution
    ├── package_system.sh .......... Create shareable package
    ├── setup.sh ................... Quick setup script
    └── requirements.txt ........... Python dependencies
```

## 📦 Downloadable Package

To create a shareable package:

```bash
./package_system.sh
```

Creates `situational_gita_complete_YYYYMMDD.zip` with:
- All scripts and documentation
- Source book content
- Pre-extracted data
- Setup script
- Ready to use immediately

Share this .zip file with others - they just run `./setup.sh` and it's ready!

## 🎯 What Gets Generated

Each article (2,000-3,500 words) includes:

✅ Hugo frontmatter (title, date, tags, description)
✅ Unique narrative structure (never formulaic)
✅ Creative section headers
✅ Concrete modern examples
✅ Bhagavad Gita verses (Prabhupada 1972 edition)
✅ Psychological insights
✅ Real-world consequences
✅ Practical takeaways
✅ Empathetic, hopeful tone

Example output: `articles/anger.md`, `articles/loneliness.md`, etc.

## 🌟 Why This System is Special

**Traditional AI article generation** = Same structure every time, feels robotic

**This system** = 12 different storytelling frameworks, 6,000+ variations, unique every time

No two articles feel the same. Readers stay engaged.

## 💡 Tips for Best Results

1. **Start Small**: Generate 3-5 articles, review, then batch
2. **Use Auto-Select**: Intelligent matching usually works best
3. **Review Content**: Check verse accuracy, tone, examples
4. **Iterate with Claude**: "Make opening more vivid" → refine → continue
5. **Track Patterns**: Note which strategies work best

## 🤔 Which Mode Should I Use?

### Use Claude Code If:
✅ You want easiest workflow (just talk to Claude)
✅ No API costs desired
✅ Generating 1-50 articles
✅ Want iterative refinement
✅ **RECOMMENDED FOR MOST USERS**

### Use Standalone Scripts If:
✅ Need automation (cron jobs)
✅ Batch generating 100+ articles
✅ Running on server
✅ Okay with API costs (~$0.10-0.30 per article)

## 📚 Documentation

- **QUICK_START.md** - Get running in 5 minutes
- **COMPLETE_GUIDE.md** - Everything explained in detail
- **SYSTEM_EXPLANATION.md** - How it all works
- **WRITING_STYLE_GUIDE.md** - Style rules followed
- **BOOK_STRATEGY.md** - Complete bestseller book plan ⭐ NEW
- **ALL_TOPICS.md** - All 110 situations organized

## 🆘 Troubleshooting

**Articles feel repetitive?**
- Use random strategy mode
- Generate in smaller batches with review between

**Generation fails?**
- Check API key (standalone mode only)
- Verify `comprehensive_gita_data.json` exists
- Run `python3 extract_themes.py` if needed

**Missing dependencies?**
```bash
pip3 install anthropic
```

**Need help?**
- Check COMPLETE_GUIDE.md
- Review QUICK_START.md
- Ask Claude Code directly

## 📊 Stats

- **Situations**: 110 total (62 themes + 48 chapter topics)
- **Strategies**: 12 narrative frameworks
- **Variations**: 6,000+ possible combinations
- **Output**: 1,800-2,200 words per article (book-optimized)
- **Time**: 1-2 minutes per article
- **Quality**: High (style guide enforced)

## 📚 Book Creation

**NEW: Complete bestseller book strategy included!**

Create **"The Gita Playbook: Ancient Solutions to Modern Day Struggles"**

- **60 curated topics** for optimal book (from 110 available)
- **4-part structure** (380-400 pages)
- **120,000 words total**
- **Bestseller-optimized** format and length
- See `BOOK_STRATEGY.md` for complete publishing plan

## 🚀 Next Steps

```bash
# 1. Extract content (first time, takes 2-3 minutes)
python3 extract_themes.py

# 2. Generate your first article
# Option A: Talk to Claude Code
#   "Generate an article about Anger"

# Option B: Use UI
python3 gita_ui.py
```

## 📄 License

Private tool for Situational Gita content creation.

---

**Ready to generate unique, empathetic Gita wisdom articles? Start now! 🙏**
