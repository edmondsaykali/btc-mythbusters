# Bitcoin-Myths JSON – Quick Guide

This project is meant to be a useful resource: a structured list of common Bitcoin myths, each with a clear rebuttal and references. 

If you have something to add,a new myth, a better way to explain one, or a helpful source, feel free to contribute. 

Open a pull request with your changes to `myths.json`.

---

## How the file works

Each myth is a JSON object with these keys (in this order):

```json
{
  "title": "Short label",
  "myth": "The wrong idea people have",
  "rebuttalPro": "Longer explanation (use \\n for new lines)",
  "eli5": "Two-sentence kid-friendly summary",
  "references": [
    { "title": "Source name", "url": "https://example.com" }
  ]
}
