# focusfolio

MV3 extension playground: page reading-time estimator

Side project, maintained when I have time.

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## What it does

- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- No remote calls, everything stays local
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   └── config.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## Development

```bash
# run the test suite
pytest -q   # or npm test / go test ./...
```

## License

MIT - see [LICENSE](LICENSE).
