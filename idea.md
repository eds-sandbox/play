# Ideas

A list of project ideas for this `play` repo. Most are meant to start as a single
`index.html` (plain JavaScript, no dependencies) and grow from there.

---

## Gravity Doodle — browser physics toy

Draw lines on a canvas with the mouse; balls drop from the top and bounce, roll,
and slide along whatever you drew. The goal is to guide them into a target cup.

**Why it's a good fit**
- One `index.html`, plain JS, no dependencies.
- Something visible works within ~50 lines (falling balls), then grows step by step.
- Touches real concepts: game loop, line-segment collision, vector reflection, input handling.

**Roadmap**
1. Balls fall with gravity and bounce off the canvas edges.
2. Draw line segments by dragging; balls collide with them.
3. Spawner and target cup; score per ball caught.
4. Levels with fixed obstacles and a limited "ink" budget.
5. Extras: bouncy/sticky line types, wind zones, level sharing via URL.

## Other non-game ideas

- **Terminal habit tracker** — a small Python CLI that logs habits to a JSON file and
  prints a GitHub-style calendar grid.
- **Markov text generator** — feed it any text file and it produces new sentences in
  the same style. Short to build, fun to read.
- **Cellular automaton playground** — Game of Life plus other rule sets you can switch
  between live, on a canvas.

---

## Game ideas

### Physics and movement
- **Grapple Swing** — swing between anchor points on a rope, let go at the right
  moment to fly through gaps. Rope physics makes even simple levels feel good.
- **Orbit Golf** — mini golf in space where planets bend the ball's path with gravity.
  One shot per hole, aimed using a predicted trajectory line.
- **Jelly Stack** — drop wobbly soft-body blocks onto a tower that sways more as it grows.

### Puzzle
- **Light Bender** — rotate mirrors and prisms to send coloured laser beams into
  matching receivers. Levels can be checked automatically for a solution.
- **Shadow Match** — turn a 3D object until the shadow it casts on the wall matches a
  target outline.
- **Ice Slide** — a grid puzzle where you slide until you hit a wall. Levels generated
  by a solver that keeps only puzzles with exactly one solution.
- **Pipe Flow, timed** — connect pipes before the water reaches them; the flow speeds
  up each round.

### Action and arcade
- **Echo Dash** — each run records your moves; on the next run a ghost of your past
  self replays them. Avoid all your earlier selves.
- **One-Button Lighthouse** — hold to sweep a light beam and guide ships away from
  rocks. Easy to learn, gets frantic.
- **Typing Defense** — enemies march toward you, each labelled with a word; typing the
  word fires at it. Harder words appear as waves grow.
- **Snake that grows backwards** — start long; every pickup shortens you. Win at length 1.

### Strategy and simulation
- **Tiny Ant Colony** — ants find food using pheromone trails; you only place obstacles
  and food, then watch the behaviour emerge.
- **Hex Territory** — two players (or vs. AI) claim hex tiles; enclosed areas flip to
  your colour. Comes with a simple minimax AI.
- **Market Stall** — set prices for a lemonade-style shop as the weather and customer
  moods change; tune your strategy across days.

### Experimental
- **Sound Maze** — a near-dark screen; navigate by sound, with stereo panning pointing
  toward walls and the exit.
- **Reverse Tetris** — you choose the pieces and an AI places them. Your goal is to
  make the AI lose.
- **Procedural Dungeon in the Terminal** — a small Python/curses roguelike with a new
  map generated each run.

---

## Picks

- **Echo Dash** (action) and **Light Bender** (puzzle) — both get to a playable state
  fast and have a clear hook.
- **Shadow Match** — chosen to build first; see `shadow-match/`.
- **Tiny Ant Colony** — built second; see `tiny-ant-colony/`.
- **Light Bender** — built third; see `light-bender/`.
- **Gravity Doodle** — built; see `gravity-doodle/`.
- **Grapple Swing** — built; see `grapple-swing/`.
- **Orbit Golf** — built; see `orbit-golf/`.
- **Jelly Stack** — built; see `jelly-stack/`.
- **Ice Slide** — built; see `ice-slide/`.
- **Pipe Flow** — built; see `pipe-flow/`.
- **Echo Dash** — built; see `echo-dash/`.
- **Lighthouse** — built; see `lighthouse/`.
- **Typing Defense** — built; see `typing-defense/`.
- **Shrink Snake** — built; see `shrink-snake/`.
- **Hex Territory** — built; see `hex-territory/`.
- **Market Stall** — built; see `market-stall/`.
- **Sound Maze** — built; see `sound-maze/`.
- **Block Saboteur** — built; see `block-saboteur/`.
