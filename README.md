# Wortschatztrainer

A German vocabulary trainer that teaches the most widespread words first. It's a single-file web app (HTML, CSS and JavaScript in `index.html`), built with Claude and aimed at learners heading for C1.

## Features

- **Frequency-first learning**: new words are introduced in order of how common they are, with progress shown by frequency band
- **Spaced repetition**: daily reviews of due words, with articles colour-coded (der / die / das)
- **Exercises**: gap-fill and checking exercises, writing your own sentences, worksheets
- **Topics**: practise all words or filter by topic
- **Exam training**: practice for telc / Goethe C1
- **Pronunciation audio**: built-in audio with a choice of voices
- **Your own words**: save new words and sentences, and back up or restore your progress

Progress is stored in the browser (`localStorage`), so it stays on the device you use.

## Running it

Open `index.html` in a browser. No build step or server needed.

Note: the app was first published as a Claude artifact. Part of the audio was loaded from the artifact host in separate files that aren't in this repo, so some words may play without sound when the app runs outside Claude. Everything else works offline.
