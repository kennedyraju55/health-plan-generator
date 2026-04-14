# 💪 Health Plan Generator

[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/) 
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE) 
[![Gemma 4](https://img.shields.io/badge/Powered%20by-Gemma%204-orange?style=for-the-badge)](https://deepmind.google/technologies/gemma/) 
[![Privacy First](https://img.shields.io/badge/Privacy-First-red?style=for-the-badge&logo=shield)](https://en.wikipedia.org/wiki/Privacy_by_design) 
[![Ollama](https://img.shields.io/badge/Local%20LLM-Ollama-darkblue?style=for-the-badge)](https://ollama.ai)

> Personalized health and wellness recommendations powered by Gemma 4 and Ollama

## 🏗️ Architecture

\\\
User Input → FastAPI Endpoints → Profile Analysis → Ollama + Gemma 4 Planner → Plan Optimizer → Personalized Health Plan
\\\

## ✨ Key Features

- Personalized health and wellness recommendations
- Fitness plan generation based on goals
- Nutrition planning with dietary restrictions
- Mental health support resources
- Sleep improvement guidance
- Ollama-based local LLM for privacy
- Gemma 4 model for health insights
- Progress tracking and analytics
- Integration with health monitoring tools
- Export plans in multiple formats

## 🚀 Quick Start

### Prerequisites
- Python 3.11 or higher
- Ollama installed and running (for local LLM)
- 4GB RAM minimum

### Installation

\\\ash
# Clone the repository
git clone https://github.com/kennedyraju55/health-plan-generator.git
cd health-plan-generator

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
\\\

### Running

\\\ash
# Start the application
python -m main
\\\

## 🔧 Tech Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Backend Framework** | FastAPI | REST API endpoints |
| **LLM Runtime** | Ollama | Local model execution |
| **Model** | Gemma 4 | State-of-the-art language understanding |
| **Language** | Python 3.11+ | Core development language |
| **Processing** | NumPy/Pandas | Data manipulation |
| **Privacy** | Local Processing | No cloud dependencies |

## 📁 Project Structure

\\\
health-plan-generator/
├── src/
│   ├── __init__.py
│   ├── core/
│   │   ├── models.py          # Data models
│   │   ├── config.py          # Configuration
│   │   └── exceptions.py      # Custom exceptions
│   ├── api/
│   │   ├── routes.py          # FastAPI endpoints
│   │   └── schemas.py         # Request/response schemas
│   ├── services/
│   │   ├── processor.py       # Main processing logic
│   │   └── ollama.py          # Ollama integration
│   └── utils/
│       ├── logger.py          # Logging setup
│       └── helpers.py         # Helper functions
├── tests/
│   ├── test_api.py
│   ├── test_services.py
│   └── conftest.py
├── requirements.txt           # Python dependencies
├── setup.py                   # Package configuration
├── README.md                  # This file
├── LICENSE                    # MIT License
└── .gitignore                 # Git ignore rules
\\\

## 📖 Usage Examples

\\\python
from src.services import processor

# Initialize processor
proc = processor.MainProcessor()

# Process your request
result = proc.process("your input")
print(result)
\\\

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (\git checkout -b feature/AmazingFeature\)
3. Commit your changes (\git commit -m 'Add AmazingFeature'\)
4. Push to the branch (\git push origin feature/AmazingFeature\)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Kennedy Raju** - *Creator & Maintainer*

- 🔗 [GitHub](https://github.com/kennedyraju55) - Follow for more projects
- 📝 [Dev.to](https://dev.to/kennedyraju55) - Technical articles and tutorials
- 💼 [LinkedIn](https://www.linkedin.com/in/nrk-raju-guthikonda-504066a8) - Professional network

## ⭐ Show Your Support

If you find this project helpful, please consider giving it a star! It helps others discover the project.

---

**Last Updated:** April 14, 2026
**Version:** 1.0.0
**Status:** Active Development