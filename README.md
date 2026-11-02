# Jackpot Calculator

A one-page calculator for 12-game football jackpots (1 X 2). For each game it works out the chance of a home win, draw and away win from the teams' results, then finds the best mix of singles, doubles and triples for the number of lines you want to pay for, and shows your chance of getting every game right.

Use it online at https://efrederickkofi-hue.github.io/jackpot-calculator/, or open `index.html` in a browser.

## What it does

- **Chances from results**: each team's attack and defence ratings, from its scores this season and last, give each game's expected goals and so its home, draw and away chances. Bookmakers' odds are not used.
- **Team news**: form, head-to-head and injury ratings for each game can move the chances, with notes and sources.
- **Best ticket**: for any number of lines it picks which games to double or triple, and shows how many games you're likely to get right.
- **What more lines buy**: a table of the best ticket for 1 to 256 lines.

## Loading games from a screenshot

On claude.ai or in the Claude app, Claude reads the screenshot. Anywhere else, such as the GitHub Pages link, a text reader built into the page does it ([Tesseract.js](https://github.com/naptha/tesseract.js), about 3 MB, downloaded the first time you use it). It reads team names well, but it can get a letter, a kick-off time or the odds wrong, so check the coupon after loading. Odds it can't read cleanly are left blank.

## Works only on claude.ai

The track record (saving coupons, marking results and learning from them) uses Claude's artifact features, so it works only when the calculator is open on claude.ai or in the Claude app.

Your coupon, line count and settings are saved in your own browser.

## Note

This is a probability tool, not betting advice. Even a well-chosen ticket wins a 12-game jackpot only rarely.
