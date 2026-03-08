# AceGerman 🇩🇪

A single-page German learning web app with flashcards, grammar reference tables, quizzes, essential phrases, and number guides — all in one beautifully styled interface.

---

## Features

- **Flashcards** — flip cards across 4 vocabulary categories (Greetings, Nouns, Verbs, Adjectives) with German articles, translations, and example sentences. Mark cards as known or shuffle the deck.
- **Quiz Mode** — 10-question multiple-choice quiz drawn from the full vocabulary pool. Earn XP for correct answers and track your streak.
- **Grammar Reference** — 8 topics including definite/indefinite articles, verb conjugations (*sein*, *haben*), the four cases, noun plurals, negation, and word order — all in clean, readable tables.
- **Essential Phrases** — 30+ real-world phrases across Greetings, Travel, Food, and Emergency categories.
- **Numbers** — cardinal numbers from 0 to 1000 with pronunciation guides, filterable by range.
- **XP & Streak System** — earn XP from flashcard reviews (+5) and correct quiz answers (+10), with a live progress bar in the header.

---

## Tech Stack

- **Vanilla HTML, CSS, JavaScript** — no frameworks, no dependencies
- **Google Fonts** — Playfair Display, DM Sans, DM Mono
- Single self-contained `.html` file — no build step required

---

## Getting Started

No installation needed. Just open the file in a browser.

```bash
git clone https://github.com/your-username/acegerman.git
cd acegerman
open index.html
```

Or simply drag `index.html` into any modern web browser.

---

## Project Structure

```
acegerman/
└── index.html    # Entire app — HTML, CSS, and JS in one file
```

All vocabulary, phrases, grammar content, and quiz logic live inside `index.html`.

---

## Customisation

All content is defined as plain JavaScript objects at the top of the `<script>` block and is easy to extend:

- **`vocabulary`** — add words under existing categories or create new ones
- **`phrasesData`** — add phrase categories or new entries
- **`grammarTopics`** — add grammar topics with custom HTML tables
- **`numbers`** — extend the number list beyond 1000

---

## License

This project is licensed under the [MIT License](LICENSE).
