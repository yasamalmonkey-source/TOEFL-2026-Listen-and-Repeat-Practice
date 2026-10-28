# TOEFL-2026-Listen-and-Repeat-Practice
TOEFL iBT 2026 Listen &amp; Repeat speaking practice: hear a sentence, repeat it, and get an instant 0–5 score. Works in Chrome on Android and as an installable web app.
# TOEFL Listen & Repeat
Link:  https://yasamalmonkey-source.github.io/TOEFL-2026-Listen-and-Repeat-Practice/

A free, single-file web app for practicing the Listen and Repeat task of TOEFL iBT 2026.

## Features

- 7 tasks per session: 2 Easy, 3 Medium, 2 Hard
- Random academic campus scenario for each task
- Sentence read aloud with adjustable speech speed
- Beep, then a 10-second recording with live speech recognition
- Automatic score from 0 to 5 with missing words and grammar words listed
- Load your own sentences from a .txt file with [Easy], [Medium] and [Hard] sections
- Session report downloaded as a text file

## Requirements

- Google Chrome (desktop or Android). Speech recognition uses the Web Speech API and needs an internet connection and microphone access.
- Must be opened over HTTPS (for example GitHub Pages) or localhost.

## Usage

1. Open the site in Chrome and allow the microphone.
2. Press **Play Audio**, listen, and repeat after the beep.
3. Read your score and press **Next Task**.

## Custom sentences

Create a UTF-8 text file with one sentence per line under the tags `[Easy]`, `[Medium]` and `[Hard]`, then choose it with the file button in the app.

```
[Easy]
The library opens at eight o'clock.

[Medium]
The professor emphasized that attendance is crucial for passing the final exam.

[Hard]
Subtropical regions experience significant changes in precipitation due to global climate patterns.
```

## License

Public domain (Unlicense). Free to use, copy, modify and share without any restrictions.
