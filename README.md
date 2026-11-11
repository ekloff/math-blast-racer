# Math Blast Racer

A free, single-page math practice game for kids in grades 2 through 6. Help the alien crew outrace the rival robots by typing in the right answers to beam rocket power into your spaceship.

**Play it here:** [ekloff.github.io/math-blast-racer](https://ekloff.github.io/math-blast-racer/)

## What it practices

- Multiplication tables (up to 12 × 12), including missing-factor problems like `7 × ? = 35`
- Division facts (up to 144 ÷ 12), including missing-divisor problems like `35 ÷ ? = 5`
- Addition and subtraction
- Mixed modes that combine operations

## How it is designed for learning

- **No countdown timers.** Races end after a set number of answers (10, 15 or 25), not after a clock runs out. Quick answers earn a bonus boost, but taking your time is never punished.
- **Typing answers, not picking them.** An on-screen number pad (and keyboard support) asks kids to recall the answer rather than recognize it from a list.
- **Spaced repetition.** A 5-box [Leitner system](https://en.wikipedia.org/wiki/Leitner_system) brings missed facts back more often and shows mastered facts less often.
- **Fair placement.** First place goes to a perfect or near-perfect run. A few mistakes put you in the middle of the pack.

## Educational and psychological foundations

Why we designed Math Blast Racer around cognitive science and educational research:

### Why time pressure harms math learning
Traditional math drills rely on countdown timers that tick down rapidly, failing students who do not answer in time. Research by [Jo Boaler at Stanford University](https://www.youcubed.org/resources/research-see-problem-timed-math-tests/) and cognitive psychologists like [Mark Ashcraft and Sian Beilock](https://doi.org/10.1007/s10648-007-9050-7) reveals that timed testing is a primary catalyst for early math anxiety.

When placed under severe time pressure, children experience an acute stress response. Cortisol surges and emotional apprehension overloads working memory in the prefrontal cortex, which is the very resource required for mental arithmetic and memory retrieval. When working memory is compromised, children panic, freeze, or resort to wild guessing, reinforcing a feeling of mathematical inadequacy.

To address this, we decoupled time from task completion:
- **No countdown clocks.** Races conclude only after a child works through a fixed quota of energy cells (10, 15, or 25 questions). Questions never expire, and taking time to count on fingers or reason through a strategy carries no penalty.
- **Positive boost windows instead of punitive timers.** Fast answers earn a small rocket boost, but taking longer never hurts. Once the boost window closes, the timer bar displays a calm ready state, keeping the child focused on accuracy.
- **Untimed calm mode.** For learners experiencing heightened anxiety, parents or teachers can select untimed mode in settings to remove speed cues entirely.

### Why active recall replaces multiple-choice guessing
Many digital games present four multiple-choice buttons to click. Cognitive psychology research on the [testing effect](https://en.wikipedia.org/wiki/Testing_effect) by Henry Roediger and Jeffrey Karpicke demonstrates that actively producing an answer from memory produces far deeper and longer-lasting retention than recognizing an answer on a screen.
- **Construction over recognition.** Instead of scanning options and using process of elimination, children type the solution using the number pad or physical keyboard. This requires genuine retrieval from long-term memory.
- **Self-monitoring.** The child must commit to a numerical value and evaluate it before beaming it to the rocket ship, developing cognitive self-regulation.

### Why spaced repetition supports long-term retention
Learners do not master all math facts simultaneously. Some combinations (such as `7 × 8` or `6 × 7`) take longer to solidify than simpler doubles or identity rules. Math Blast Racer incorporates a five-box [Leitner spaced repetition system](https://en.wikipedia.org/wiki/Leitner_system) directly in the browser:
- **Prioritizing struggling facts.** Missed facts drop to box 1, where the algorithm samples them in 50% of upcoming problems until the child masters them.
- **Preventing cognitive fatigue.** Well-retained facts advance into higher boxes and appear less frequently, ensuring practice time targets emerging knowledge rather than repeating already solid material.

### Why low-stakes recovery builds math resilience
Carol Dweck's research on [growth mindset](https://en.wikipedia.org/wiki/Mindset#Fixed_and_growth_mindsets) demonstrates that children build perseverance when errors are treated as routine information rather than personal failure.
- **Immediate second chances.** An incorrect entry makes the engine sputter and prompts an encouraging message ("Not quite! Give it another try!"). The question does not disappear, allowing the child to reconsider their thinking and try again right away.
- **No game-over penalty.** A learner is never ejected from a race or forced to restart because of mistakes. Every race reaches the finish line, keeping motivation high.

### Why missing-factor problems develop algebraic reasoning
Research on early algebra by [Thomas Carpenter and colleagues](https://doi.org/10.1016/j.jmathb.2003.09.002) notes that elementary students frequently view the equals sign as an operational command meaning "compute the answer," rather than a relational symbol of equivalence.
- **Understanding equivalence.** Seeing problems like `7 × ? = 35` or `? + 9 = 24` encourages children to examine relationships across both sides of the equal sign.
- **Preparation for division.** Missing-factor multiplication lays the conceptual bridge for division and inverse operations well before formal algebra instruction.

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
