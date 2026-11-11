# Math Blast Racer

A free, single-page math practice game for kids in grades 2 through 6. Help the alien crew outrace the rival robots by typing in the right answers to beam rocket power into your spaceship.

**Play it here:** [ekloff.github.io/math-blast-racer](https://ekloff.github.io/math-blast-racer/)

## What it practices

- Multiplication tables (up to 12 × 12), including missing-factor problems like `7 × ? = 35`
- Addition and subtraction
- A mixed mode that combines both

## How it is designed for learning

- **No countdown timers.** Races end after a set number of answers (10, 15 or 25), not after a clock runs out. Quick answers earn a bonus boost, but taking your time is never punished.
- **Typing answers, not picking them.** An on-screen number pad (and keyboard support) asks kids to recall the answer rather than recognize it from a list.
- **Spaced repetition.** A 5-box [Leitner system](https://en.wikipedia.org/wiki/Leitner_system) brings missed facts back more often and shows mastered facts less often.
- **Fair placement.** First place goes to a perfect or near-perfect run. A few mistakes put you in the middle of the pack.

## Privacy

Everything runs in the browser. Progress is saved only in your browser's local storage. There are no accounts, no tracking and no server. Parents can back up, restore or clear progress from the settings screen.

## Running it locally

It is a single HTML file. Open `index.html` in a modern browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Credits

Built with [three.js](https://threejs.org/) and the [Fredoka](https://fonts.google.com/specimen/Fredoka) and [Mochiy Pop One](https://fonts.google.com/specimen/Mochiy+Pop+One) fonts from Google Fonts.

## License

[MIT](LICENSE)
