# svobody

## Editor tooling (Cursor / VS Code)

Open the project and install recommended extensions when prompted
(`.vscode/extensions.json`), or run **Extensions: Show Recommended Extensions**.

Included workspace setup:

1. **Format & quality** — Prettier, ESLint (JS/TS), Black / Flake8 / Pylint (Python), Error Lens
2. **Navigation** — GitLens, bracket pair colorization, Path Intellisense
3. **Env & data** — Database Client, MSSQL, Docker, REST Client (see `http/examples.http`)

JS/TS:

```bash
npm install
npm run format
npm run lint
```

Python (optional local tools):

```bash
pip install black flake8 pylint
black .
flake8 .
pylint <package_or_module>
```
