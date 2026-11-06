# Pocket Playground

Tiny browser games. No sign-up, just play.

**Play it:** https://laspapas1212.github.io/pocket-playground/

71 games in one page:

- **Reaction:** Reaction Time, Quick Draw, Go / Stop, Lightning Tiles, Bonk, Color Rush, Stop the Clock, Rhythm Tap, Rhythm Keys
- **Aim:** Aim Trainer, Balloon Pop, Tracker, Fruit Slice, Shooting Gallery, Shrinking Dots, Precision, Zombie Survival
- **Arcade:** Click Frenzy, Stacker, Dodge, Slither, Sky Hopper, Hop Runner, Brick Breaker, Paddle Duel, Fruit Catch, Space Blaster, Lane Racer, Sky Jumper, Pinball, Tower Defense, Platform Jumper, Block Drop, Bubble Shooter
- **Puzzle:** Tile Merge, Sweeper, Number Rush, Odd One Out, Higher or Lower, Lights Out, Slide Puzzle, Math Sprint, Maze Run, Sudoku, Solitaire, Gem Swap, Spot the Difference, Battleships, RPS Tournament
- **Memory:** Echo Pads, Pair Up, Grid Recall, Number Memory, Simon Says Plus, Flag Quiz
- **Word:** Type Sprint, Five Letters, Word Scramble, Balloon Words, Typing Defense, Crossword Mini
- **2 Player:** Tic-Tac-Toe, Connect Four, Paddle Battle, Reflex Duel, Checkers, Dots and Boxes, Air Hockey. Play a friend on the same computer, or a bot (easy, medium, hard, extreme).
- **Chill:** Bubble Wrap, Paint Splat, Idle Factory

Also:

- **Daily Challenge:** one game a day, with a streak counter.
- **Achievements:** 26 badges to unlock.
- **Settings** (gear button): sound and volume, theme, animations, confetti, screen shake, keyboard hints, and resetting your data.

Best scores, badges and your Idle Factory are saved in your browser only.

## Run it locally

It's a single `index.html` with no build step. Open it in a browser, or serve the folder with any static web server.

## Tests

Open `tests.html` from the same folder (through a local web server). It loads the site in a frame and checks the riskiest logic: the best-score rule, the bots, Sudoku puzzles, Checkers rules, Slide Puzzle shuffles, and that every game opens.
