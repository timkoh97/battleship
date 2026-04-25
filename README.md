# Battleship
A simple Battleship game in HTML to test agentic coding.

Made for joy with Claude.

## Changelog

### v1.1 - 2026-04-26 00:40 (BST)

- Mobile-friendly - allows rotation of ship on button press; remove ability to rotate on R press
- Add margin between Launch Battle button and text above
- Update row labels from 1-9 then 0 to 0-9
- Update enemy fleet panel to show length of each ship
- Add new stats to statistics panel

### v1.0 - 2026-04-25 09:23 (BST)

- Battleship game
- AI set to hunt/target strategy (random until a hit, then systematically check adjacent cells until the ship sinks)
- Enemy fleet health tracker
- Rotation option for ships
- Footer with details

## Updates in consideration

### Urgent

### Non-urgent

- Hard mode: AI uses probability density strategy (calculate which cells are most likely to contain a ship given what's known, attack the highest-probability cell)
- Change colour schemes? Light mode and dark mode?
- Statistics tracker for multiple games
- Update final score to declare how many total shots to win (currently says 17 shots on win - the number of shots required to win)
- Update player fleet deployment panel to declare AFLOAT or SUNK like Enemy panel
