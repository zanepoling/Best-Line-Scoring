# Best Line Scoring

Vote tally for the AMBC Fall Fest Best Line competition.

## How it works

Men and Women are scored separately. Pick a division with the tabs at the top; each tab has its own riders, ballots and podium, and switching tabs never changes the other one. Riders vote within their own division. A rider added to the wrong tab can be moved with "→ Men" / "→ Women".

1. **Rider check-in:** add riders one at a time, or paste a list separated by commas or new lines.
2. **Rank the lines:** pick the voter, then tap their 1st, 2nd and 3rd choices. Riders can't vote for themselves.
3. **Podium:** standings update as ballots come in.

| Choice | Points |
| ------ | ------ |
| 1st    | 3      |
| 2nd    | 2      |
| 3rd    | 1      |

The top three riders by points win. Ties on points go to whoever has more 1st-place votes, then more 2nd-place votes. Riders still tied share a podium spot.

"Announce the winners" opens a full-screen reveal of 3rd, 2nd and 1st place.

## Undo

Every action can be undone with the **Undo** button in the bottom-right corner, or with Ctrl+Z / ⌘Z. That includes adding or removing riders, each pick on a ballot, saving, editing, cancelling or deleting a ballot, moving a rider between divisions, and "Clear votes in this tab" / "Start this tab over". Undo goes back one step at a time, up to the last 100 actions, and keeps its history after a page reload on the same device.

## Running it

It's a single file with no build step. Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main`, root folder).

## Where votes are saved

When it runs from GitHub Pages or a local file, riders and ballots are saved in that browser only (`localStorage`). Run the tally from one device, and don't clear site data until the winners are announced. The hosted Claude version syncs votes live across devices.
