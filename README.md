# Soccer Tactics Board

An interactive soccer tactics board for coaching 9–12 year olds. Pick a formation, move the ball around the field, and every player shifts to where they should be, both when your team has the ball and when the other team has it.

## Formations

Formations are written defenders-midfielders-strikers, so a 4-3-3 is four defenders, three midfielders and three strikers.

**11 v 11:**

- 4-3-3 (Flatback 4), the default
- 4-3-3 (with Sweeper)
- 4-3-3 (with Stopper)
- 3-4-3
- 4-4-2 (Flatback 4), (with Sweeper), (with Stopper)
- 4-2-4 (Flatback 4), (with Sweeper), (with Stopper)
- 3-3-4

**7 v 7** (six field players plus the goalkeeper):

- 3-0-3 (3 defenders, 3 strikers)
- 2-0-4 (2 defenders, 4 strikers)
- 3-1-2 (3 defenders, 1 mid, 2 strikers)
- 2-1-3 (2 defenders, 1 mid, 3 strikers)

**6 v 6** (five field players plus the goalkeeper):

- 2-3 (2 defenders, 3 strikers)
- 3-2 (3 defenders, 2 strikers)
- 2-1-2 (2 defenders, 1 mid, 2 strikers)

7v7 and 6v6 use the same field drawing, but every distance on the page (readouts, coaching tips and player cards) is shown for a small-sided field: about 55 × 35 m for 7v7 and 42 × 27 m for 6v6.

The page remembers the last formation picked, and the link updates (for example `#442-stopper`) so you can send a specific formation to another coach.

## Features

- **Live positions:** place the ball at your finger, or move it relative to how your finger moves (the default on phones and tablets).
- **Drag a player:** switch **Drag** from Ball to Player and move any field player. **Player control** works like ball control: *Player at finger* sends the picked player to wherever you touch, and *Move with finger* moves them the same way your finger moves (the default on phones and tablets). Tap a player to pick them.
  - *We have the ball:* that player carries it. A teammate comes short behind and inside for an easy pass, and the most advanced striker runs in behind.
  - *They have the ball:* that player presses the attacker (shown in red). A teammate drops in behind at an angle to cover, and a far-side defender tucks in for balance.
- **Situations:** starting shape, building from the back, attacking down the right, shooting at their goal (strikers crash in for rebounds), crossing from the left, defending your right side, the high press, and stopping a counter.
- **Set pieces:** your corner kicks and theirs (both can be flipped to the other side), plus your goal kicks and theirs. Every formation gets its own set-piece jobs.
- **Player cards:** tap any player to see their job with and without the ball, a coaching cue, and what they're doing right now.
- **Coverage areas:** shows where each position can expect to be across all situations, with their set-piece spots marked. The goalkeeper's area is the whole penalty box.
- **Shape readouts:** back line height, team length, and team width.

## Run it

It's one self-contained HTML file with no build step. Open `index.html` in a browser, or host it free with GitHub Pages: go to **Settings → Pages**, set the source to the `main` branch and the `/ (root)` folder, and the board will appear at `https://<your-username>.github.io/<repo-name>/`.

Fonts load from Google Fonts. Without an internet connection, the page falls back to system fonts.
