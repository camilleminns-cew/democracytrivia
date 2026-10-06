# Ballots & Kilowatts Trivia

Icebreaker for the Clean Energy Works report out from RECESS 2026 and the RE-AMP Network Annual Meeting (October 2026).

Ten questions across IL, KS, OR, CA, NC, MO, VA, and WA connect 2026 elections to energy outcomes. Each answer names where the decision was made (ballot box, legislature, courts, or commission). After the last question, the page shows a tally of those venues and opens discussion prompts for the guiding question:

> How much does political organizing literacy matter in our toolkit for advancing this work?

## Publish on GitHub Pages

1. Create a new public repo (for example, `election-energy-trivia`) under your GitHub account.
2. Upload `index.html` and this `README.md` to the main branch.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute or two, the site will be at `https://<your-username>.github.io/election-energy-trivia/`.

## Editing

All questions are in the `QS` list near the bottom of `index.html`. Each question has:

- `q`: question text
- `opts`: four answer choices
- `ans`: the index of the correct choice (0 = first)
- `explain`: the answer explanation
- `lever`: the "Organizing lens" note
- `venue`: one of `Ballot box`, `Legislature`, `Courts`, `Commission`
- `src`: sources line

Round headers are set in `ROUNDS`, keyed by the question index where each round starts.

## Before presenting

Polling (Q5) and Missouri redistricting litigation (Q6, Q10) were current as of October 6, 2026. Recheck both the day before.

This is nonpartisan civic education. It does not support or oppose any candidate.
