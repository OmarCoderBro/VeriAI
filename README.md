# VeriAI

> AI-powered verification platform for detecting misinformation and validating claims using LLMs and trusted sources.

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

## Overview

VeriAI helps users verify the credibility of information by combining large language models with trusted external sources. Given a claim or article, VeriAI analyzes the content, retrieves supporting evidence, and generates an explainable confidence score.

## Features

- 🔎 Fact-check natural language claims
- 🤖 AI-powered reasoning
- 📚 Evidence retrieval
- 📊 Confidence scoring
- ⚡ Fast API responses
- 🖥️ Modern web interface

## Tech Stack

- Frontend: Flutter
- Backend: Flask   
- ML models: HuggingFace hallucination models
- LLM Models: OpenAI, Meta, Gemini
- Deployment: Vercel

## Architecture

```text
User
   │
Frontend
   │
Backend API
   │
───────────────
│ LLM Service │
│ Retrieval   │
│ Database    │
───────────────
```

## Installation

```bash
git clone https://github.com/OmarCoderBro/VeriAI.git
cd VeriAI
```

Install dependencies

```bash
npm install
# or
pip install -r requirements.txt
```

Run locally

```bash
npm run dev
# or
python app.py
```

## Usage

1. Enter a claim.
2. VeriAI searches for supporting evidence.
3. The AI analyzes credibility.
4. Review the confidence score and explanation.

## Screenshots

*Add screenshots or a demo GIF here.*

## Roadmap

- [ ] Browser extension
- [ ] PDF verification
- [ ] Multi-language support
- [ ] Citation export
- [ ] User accounts

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

MIT License
