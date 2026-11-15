![Built with Claude](https://img.shields.io/badge/Built%20with-Claude-D97757)

# Zen-n-Back

A card game based on n-back memory training: spot when a new Zener card matches one 'n deep' in a stack.

**[▶ Play now](https://dionliddell.github.io/zen-n-back/)** | **[⬇ Download](https://github.com/dionliddell/zen-n-back/archive/refs/heads/main.zip)** (unzip and open index.html to play offline)

## How to play
Zen-n-Back is built to be tough. Every level asks more of your focus and memory than the last, and so far no one in testing (me included) has made it past n = 3. Consider it a challenge.

Tap the draw pile in the centre to start. Each tap turns up a Zener card and deals the previous one onto a random tile around it. If the card n deep in one of the stacks matches the face-up card, tap that stack to score a point and burn it away. If there's no match, tap the draw pile to deal again. Tapping the wrong stack, or dealing when a match was there, costs a point. Every 10 points takes you up a level: fewer tiles, deeper stacks, and more for your memory to hold. The game ends when you reach 50 points or after 5 minutes, and your score is the highest total you reached along the way.

## Modes
- **Easy:** cards are dealt face up
- **Hard:** cards are dealt face down
- **Training (Hard only):** Click Me! marks the right move, wrong taps are ignored, a level every 3 points, ends at 15 points or 2 minutes. No high scores.

## Rules in detail
- Each symbol always has its own colour: star yellow, circle red, waves blue, square black, cross green.
- At n = 1 the match is the top card, at n = 2 the second card down, and so on.
- n rises at 10, 20, 30 and 40 points and falls if you drop below a mark. Fewer tiles are in play as n rises.
- Double-click the draw pile to undo the last deal.
- Flames: blue = match, green = level up, yellow = level down, missed match or time up, purple = points target reached.
- Keys: Space draws. Q W E / A D / Z X C or the number pad claim a stack. Esc closes the help panel.

## What is Zen-n-Back?
An n-back task shows you a stream of items and asks whether the current one matches the one from n steps earlier. Psychologists have used it since the 1950s to measure working memory.

I've always wanted to combine n-back with a card game, and Zen-n-Back (made in partnership with AI) is the result.

Dion Liddell
