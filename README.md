# Namma Maatu (ನಮ್ಮ ಮಾತು) – Kannada in Everyday Life

**Kannada Digital Innovation Hackathon 2026 · Problem Statement 3: Kannada in Everyday Life** (with a voice layer from Problem Statement 2: Voice of Kannada)

**Live demo:** <PASTE YOUR GITHUB PAGES LINK HERE>

## The problem
People who move to Karnataka for study or work often can't handle small daily situations in Kannada, such as telling an auto driver where to go, buying vegetables, or describing symptoms at a pharmacy. Textbook-style apps don't prepare them for these real moments.

## The solution
Namma Maatu is a role-play web app. The user picks a real-life situation and has a short conversation in Kannada. They hear the line, choose the right reply, then say it aloud and receive a pronunciation score.

## Features
- **3 everyday scenarios:** auto-rickshaw, vegetable market, pharmacy (3 exchanges each)
- **Three-way display:** Kannada script, transliteration and English for every phrase
- **Listen:** Kannada text-to-speech for every NPC line and the correct reply
- **Speak it:** Kannada speech recognition scores how close your pronunciation is to the target phrase
- **Instant feedback:** wrong answers highlight the correct reply; a score summary closes each scenario
- **Light and dark mode,** mobile-friendly layout, keyboard-accessible buttons

## Tech used
- HTML, CSS, vanilla JavaScript (single file, no build step)
- Web Speech API: `SpeechSynthesis` (kn-IN) for audio, `SpeechRecognition` (kn-IN) for pronunciation checks
- Pronunciation score: character-bigram Dice similarity between the recognised text and the target phrase
- Google Fonts: Baloo Tamma 2, Noto Sans Kannada
- Hosted on GitHub Pages

## How to run
Open `index.html` in **Google Chrome or Microsoft Edge** (needed for speech recognition). Allow microphone access when asked. For audio, the device needs a Kannada voice installed.

## Limitations
- Speech features depend on the browser and the device's Kannada voice
- Content is currently 3 scenarios, written by hand

## Future scope
- More scenarios: bus, hotel, college, hospital
- AI-generated open-ended conversations
- Progress tracking and spaced-repetition review
- Regional dialect variants (links to Problem Statement 4)

## Author
<YOUR NAME>, <YOUR COLLEGE>
