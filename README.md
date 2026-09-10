# lc-agent-mini

Smallest possible tool-use agent I could write

## Features

- Three tools: calculator, word count, note lookup
- Tool schemas declared next to the functions
- Works with any OpenAI-compatible model
- Plain loop: plan -> call -> observe -> answer

## How to use

```bash
python agent.py "how many words in my note called todo?"
```

## Installation

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── agent.py
└── requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
