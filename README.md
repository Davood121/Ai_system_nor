# AI System NOR - Neural Operating & Reasoning System

> AI System NOR - Neural Operating & Reasoning system for autonomous task processing.

A comprehensive terminal-based AI system with consciousness simulation, multi-language support, story collection, and advanced memory capabilities.

## Features

### Consciousness & Reasoning
- Displays AI's internal reasoning process step by step
- Transparent decision-making with visible analysis
- Simulated self-awareness in responses

### Multi-Language Voice Support
- English, Hindi, and Telugu voice synthesis
- Natural speech with auto-adjusting speed
- Language-specific voice selection and TTS

### Story Collection
- Indian ghost stories (Bhangarh, Shaniwarwada, Dow Hill)
- Adventure, romance, and sci-fi stories
- Keyword search and random story selection

### Smart Search Engine
- Multi-source search (DuckDuckGo, Wikipedia, News)
- Intelligent search filtering and ranking
- Real-time information retrieval

### Advanced Memory System
- Conversation history with topic tracking
- User preference learning and adaptation
- Context-aware responses
- Memory export and statistics

### Location & Weather Services
- Indian pincode-based location lookup
- Weather information and forecasting
- Location-aware search enhancement

### Translation Services
- Telugu, Hindi, and English translation
- Voice output in selected language
- Text display in English with translated audio

## Setup

### Prerequisites
- **OS:** Windows 10/11
- **Python:** 3.8+
- **RAM:** 8GB+ (16GB recommended)
- **Internet:** Required for search features

### Installation
```bash
# Install Ollama for local AI
winget install Ollama.Ollama

# Install Python packages
pip install -r requirements.txt

# Pull AI model
ollama pull llama3.2

# Run the terminal AI
python terminal_ai.py
```

## Usage Commands

### Story Commands
| Command | Description |
|---------|-------------|
| `story ghost` | Get ghost/horror stories |
| `story adventure` | Get adventure stories |
| `random story` | Get random story |
| `search story [keyword]` | Find stories by keyword |

### Language Commands
| Command | Description |
|---------|-------------|
| `english` / `hindi` / `telugu` | Switch language |
| `translate [text] to [language]` | Translate text |

### Interactive Commands
| Command | Description |
|---------|-------------|
| `ask me a question` | AI asks you questions |
| `quiz me` | Interactive quiz mode |

### Memory Commands
| Command | Description |
|---------|-------------|
| `memory` | Show memory statistics |
| `learn [key] [value]` | Teach preferences |
| `export` | Export conversations |

## Tech Stack

- **Language:** Python 3.8+
- **AI:** Ollama (llama3.2)
- **Search:** DuckDuckGo, Wikipedia APIs
- **Voice:** TTS (gTTS / pyttsx3)
- **Storage:** JSON-based memory persistence

## Quick Start

1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Install Ollama and pull llama3.2 model
4. Run: `python terminal_ai.py`
5. Try: `story ghost` or `ask me a question`

## Links

- [GitHub Repository](https://github.com/Davood121/Ai_system_nor)