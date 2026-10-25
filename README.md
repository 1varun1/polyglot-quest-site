# Polyglot Quest

<p align="center">
  <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=1400&q=80" alt="Polyglot Quest language learning banner" width="1200" />
</p>

An evidence-based, game-driven language learning interface built for fast, repeatable study across multiple languages.

Polyglot Quest combines spaced repetition, recall tracking, sentence-building practice, and arcade-style speed challenges into a browser-based experience that feels playful while reinforcing memory science.

## Live demo

- Production site: https://polyglot-quest-site.vercel.app
- GitHub repo: https://github.com/1varun1/polyglot-quest-site

## Highlights

- 10-language+ study hub with quick switching between global languages
- Spaced repetition logic inspired by half-life regression and SM-2 principles
- Flashcard recall flow with streaks, hearts, and XP progression
- Sentence reconstruction mode for contextual learning
- Speed-match mini-game for dual coding and pattern recognition
- Arcade mode for a more gamified challenge loop
- Fully static front-end, so it runs without a backend or build step

## How it works

1. Choose a language and start with a short vocabulary challenge.
2. Review cards with timed recall and memory decay logic.
3. Practice sentence construction to reinforce meaning in context.
4. Play a quick matching or arcade challenge to strengthen pattern recognition.
5. Repeat the loop as memory strength updates over time.

## Project structure

- `index.html` — main app UI and game logic
- `README.md` — project overview and usage
- `vercel.json` — deployment configuration for Vercel

## Run locally

You can open the page directly in a browser, or serve it with a lightweight local web server:

```bash
cd polyglot-quest-site
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Tech stack

- HTML
- CSS
- JavaScript
- Tailwind CSS
- Chart.js
- Browser localStorage

## License

This project is provided as a learning/demo project for educational and personal use.

## Notes

This is a static frontend demo focused on language-learning mechanics and UI flow. It is designed to be easy to run, share, and extend.
