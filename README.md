# MoodLens AI

An explainable, local-first sentiment analysis dashboard. MoodLens scores emotional tone, highlights the words that influenced its decision, measures positivity, energy, and clarity, and suggests a stronger rewrite.

![Explainable NLP](https://img.shields.io/badge/NLP-Explainable%20AI-a7ef77?style=for-the-badge&labelColor=151817)

## Why it is interesting

Many sentiment tools return a label without explaining it. MoodLens makes its reasoning visible. The interface connects each score to highlighted language signals, giving users a practical introduction to explainable AI.

## Features

- Weighted sentiment lexicon
- Intensifier and negation handling
- Confidence and emotional-dimension scoring
- Word-level positive and negative highlighting
- Context-aware clarity suggestions
- Local-only analysis with no API or tracking
- Responsive editorial dashboard

## Run locally

Open `index.html` in any modern browser.

## How the model works

1. Text is tokenized into words and punctuation.
2. Tokens are scored with a weighted sentiment lexicon.
3. Nearby intensifiers and negations modify the score.
4. Scores are normalized into tone, confidence, positivity, energy, and clarity.
5. The interface highlights contributing tokens so the result can be inspected.

## Tech

HTML, CSS, and vanilla JavaScript.

## Limitations

This is an educational lexicon-based NLP model. It does not fully understand sarcasm, cultural context, or complex language ambiguity.

## Future improvements

- Add multilingual lexicons
- Compare multiple messages over time
- Export analysis reports
- Add a transformer-model backend as an optional advanced mode

## License

MIT
