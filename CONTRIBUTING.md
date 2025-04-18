## How to add or improve a myth

1. **Fork** the repo → edit `myths.json`.
2. Keep the object schema:
   - `id` – kebab‑case, immutable.
   - `title` / `myth` – ≤120 chars each.
   - `rebuttalPro` – max ~700 words, include *at least one* source.
   - `rebuttalELI5` – ≤250 chars, no jargon.
3. Cite sources as objects `{title,url}`; no raw links in text.
4. Run `npm test` (JSON schema lint).
5. Open a pull request; CI will format & validate.

_Please keep it factual and civil — memes go elsewhere._

