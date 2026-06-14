Environment setup

This project can optionally use Google Gemini (GenAI) for AI-powered suggestions.

Set the `GEMINI_API_KEY` environment variable before running the app to enable AI features.

Windows (PowerShell):

```powershell
setx GEMINI_API_KEY "YOUR_API_KEY_HERE"
# restart your terminal after setx
```

macOS / Linux:

```bash
export GEMINI_API_KEY="YOUR_API_KEY_HERE"
```

If the variable is not set, the app will still run but AI features will fall back to local heuristics or show a warning.