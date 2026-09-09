# mdfolio

My tiny static site generator, ~100 lines of Python

## Getting started

```bash
pip install -r requirements.txt
```

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Highlights

- RSS feed generation
- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- Index page with post list by date

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT. Do whatever you want.
