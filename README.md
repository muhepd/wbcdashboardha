This is a World Baseball Classic Dashboard for Home Assistant.

It includes all Pools information and the Schedule of each game (you can click on then or tap them on your phone/tablet).

See for yourself in the screenshots below.

All you have to do is copy the wbc2026-card.html file into your /config/www/ folder.

Then create a new dashboard, I used Panel (Single Card), add a new card (manual) and copy the code that is inside the wbccard.txt file.

The card also has a popup feature for any live game.

When you click a live game (ones with the 🔴 badge), a popup opens with a Scoreboard and Play-by-Play sections:

Scoreboard section:

Large score display with current inning + Top/Bottom arrow
Full linescore grid (runs per inning, R/H/E totals) with the current inning highlighted
Ball/Strike/Out count dots
Base runner diamond showing occupied bases in gold

Play-by-play section:

Last 20 plays, most recent first, with inning tags
Colour-coded dots — 🟡 scoring plays, 🟢 hits, 🔴 outs, grey for other
RBI and run totals highlighted in gold inline

Auto-refresh: the popup refreshes itself every 30 seconds while open, and you can also hit the ↻ Refresh button manually. Close it with the ✕ button, clicking outside the popup, or pressing Escape.

That's it.

Screenshots:

<img width="1210" height="1490" alt="image" src="https://github.com/user-attachments/assets/7f04c3a8-3032-4f69-a44a-73ff9100ab1c" />

<img width="1222" height="1538" alt="image" src="https://github.com/user-attachments/assets/346f6303-71ac-437e-866a-7f40d54ac4e9" />

<img width="1227" height="1627" alt="image" src="https://github.com/user-attachments/assets/4ab01ef4-19a4-41ac-bad5-85792fc20554" />

<img width="1212" height="1498" alt="image" src="https://github.com/user-attachments/assets/305b6114-b254-4fbc-bf78-49390b5ecbaf" />


