# The League — Weekly Challenges

One side-challenge a week, on top of the normal matchup. This is the page that
tracks them: which one is live, who is projected to take it, who is actually
taking it right now, and who has already won one.

**[Open the board](https://the-league-challenges-alex-slocums-projects-b41b31f7.vercel.app)**

## The slate

| Wk | Challenge | |
|---|---|---|
| 1 | Chunk Play Club | Most 40+ yard plays by your starters — completions, runs and catches all count. |
| 2 | Catch Party | Most combined receptions by your starting lineup. |
| 3 | The Turnover Tax | Fewest points handed back. *Lowest wins.* |
| 4 | Field Position | Most kick and punt return yards, D/ST included. |
| 5 | The Understudy | Best score from a starter drafted round 10 or later, or never drafted. |
| 6 | Takeaway Artist | Most interceptions + fumble recoveries by your starting D/ST. |
| 7 | Bad Beat | Score the most points and still lose. |
| 8 | Scrambled | Most rushing yards from your starting QB. |
| 9 | The Donut Shop | Own the most starters who finish under five points. |
| 10 | Leg Day | Most fantasy points from your starting kicker. |
| 11 | One-Man Band | Largest share of your total from a single starter. |
| 12 | Overachiever | Beat your own lineup's projection by the most. |
| 13 | Perfect Vision | Highest share of the points you actually had available. |
| 14 | Grand Finale | Most total starting points. No gimmick. |

They lean on the things our scoring makes interesting — full PPR, return yards
at 1 per 20, −3 interceptions, the 40+ bonus ladder, raised D/ST tiers — so
most of them are bets you could not run on default settings.

## How to read it

**Projected** (purple) is a forecast. **Actual** (green) is what happened. Both
sit on one scale so the gap between them is the interesting part. Under each
team are the players who made the number, because "4.4 expected touchdowns"
starts an argument and "Gibbs 1.16, Montgomery 0.70" ends one.

Two labels worth knowing:

- **Real lineups** — scored against what people actually started that week.
- **Assumed lineups** — nobody's real lineup was on record, so each team is
  scored against its *best possible* lineup instead. Two challenges measure the
  starter/bench split itself and are only placeholders on those weeks; they say
  so on the card.

If the page is out of date, a red bar says so across the top. Believe the bar
over the numbers.

## Two honest limits

1. A **projected** winner is an expected value, not a forecast of the winner.
   "1.4 expected 40+ plays" does not mean one happens. Read it as who is best
   positioned.
2. Everything is scored in **our** rules, not Yahoo's defaults. The numbers here
   will not match other sites. That is the point.

## What's in here

A single HTML file and a JSON snapshot. No server, no API, no build step — the
snapshot is produced separately and committed, so the page is always exactly as
correct as the file next to it.

```
index.html              the whole app
data/challenges.json    the snapshot it reads
```
