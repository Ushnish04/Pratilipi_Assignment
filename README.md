# AI Story Transformation System

Transform classic literature into modern settings using LLM-powered analysis and systematic frameworks.

## 🎯 Assignment Deliverables

✅ **Reimagined Story**: 3-5 page narrative with dialogue  
✅ **Runnable Codebase**: Jupyter notebook with complete pipeline  
✅ **Documentation**: System design, alternatives, challenges  

## 🚀 Quick Start

### 1. Install Dependencies
```bash
pip install openai requests
```

### 2. Set API Key
```bash
# Get free key from: https://openrouter.ai/keys

# PowerShell
$env:OPENROUTER_API_KEY="your-key-here"

# Mac/Linux
export OPENROUTER_API_KEY="your-key-here"
```

### 3. Run
```bash
jupyter notebook story_transformation.ipynb
```

## 📁 Project Structure
```
├── story_transformation.ipynb    # Main pipeline
├── DOCUMENTATION.md              # Technical documentation
├── README.md                     # This file
├── .gitignore                    # Security
├── outputs/
│   ├── romeo_juliet_analysis.json
│   ├── transformed_bangalore_hiphop.json
│   └── story_bangalore_hiphop.md
└── story_cache/                  # Cached stories
```

## 🎨 Features

- **Prompt Engineering**: Structured queries for consistent output
- **Prompt Chaining**: 4-stage sequential analysis
- **Systematic Framework**: Reusable transformation logic
- **Premium Generation**: LLM-powered creative writing

## 🔧 Configuration

Edit CELL 8:
```python
STORY_KEY = "romeo_juliet"        # romeo_juliet, hamlet, macbeth, frankenstein, dracula
TARGET_UNIVERSE = "bangalore_hiphop"  # bangalore_hiphop, silicon_valley, space_colony
```

## 📊 Example Transformations

| Source | Target | Output |
|--------|--------|--------|
| Romeo & Juliet | Bangalore Hip-Hop | Rival rap crews |
| Frankenstein | Silicon Valley | AI ethics tragedy |
| Hamlet | Space Colony | Political intrigue on Mars |



## 📖 Output Files

1. `{story}_analysis.json` - LLM analysis (themes, characters, plot)
2. `transformed_{universe}.json` - Complete mapping
3. `story_{universe}.md` - Final 3-5 page narrative

## 🆘 Troubleshooting

**API Errors**: Check key is set correctly  
**Rate Limits**: Wait between runs (free tier)  
**Missing Stories**: Will auto-download from Gutenberg  

## 📚 Data Source

Public domain texts from [Project Gutenberg](https://gutenberg.org)


```

---

### 4. **Sample Outputs** (Show Your Work!)

Create an `outputs/` folder with example files:
```
outputs/
├── romeo_juliet_analysis.json          # Shows prompt engineering
├── transformed_bangalore_hiphop.json   # Shows transformation logic
└── story_bangalore_hiphop.md           # Final deliverable
