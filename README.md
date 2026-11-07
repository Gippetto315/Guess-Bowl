# Guess Bowl

Four quarters of football where every play is a guess.

## Play
Open the game link on your phone, then tap **Share → Add to Home Screen**. It launches full-screen like a real app.

## How it works
- **Offense:** each set of downs hides a number from 1–25. Every guess is a down. Hit it and you gain the yards on that tile (the edges pay the most). Miss and you get HIGHER or LOWER, and the number shifts a little.
  - Within 2: +4 · Within 5: +2 · 15+ off: tackle for loss · 20+ off: sack
- **Defense:** read their number. Exact = interception, sack, or stop. One away stuffs them. Way off gives up a big play.
- **4th down:** go for it (the defense reloads), punt, or kick a field goal. Longer kicks need a tighter guess, and one hidden number gets it blocked.
- **Special teams:** kickoff and return guesses, onside kicks, extra point or go for 2.
- **Weather:** clear, rain, snow, or wind, each changes the game.

## Modes
- **Season:** 17 games, a 32-team league, NFL-style playoffs, and the championship. Pick **Pure** (developer's pick) or **Upgrades** before Week 1, and you're locked in.
- **Quick Game:** a random opponent, just play.
- **Stats & Trophies:** season and career stats, rings, records, and achievements.

## Tech
One self-contained `index.html` with no build step and no dependencies. Progress saves on your device. Randomness uses the browser's crypto-grade generator.
