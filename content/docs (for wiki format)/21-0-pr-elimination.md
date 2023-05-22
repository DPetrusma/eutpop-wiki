---
title: "21. PR Elimination"
---

# 21. PR Elimination

The game by default does not have player elimination, since a player may always Surrender when facing a catastrophic defeat in a War, and PRs always retain their Capital when a Peace is concluded.

If, however, for whatever reason, a player must leave the game before it ends, there are two ways to handle this. In either case, this should be done at the end of a Round, after resolving all of that PR's Wars.

The first (and easiest) solution is to leave all <code>t</code> and <code>v</code> belonging to that PR on the map boards, and continue playing as if all of these belonged to an NPR. Remove any <code>u</code> from those <code>t</code>/<code>v</code>, and remove all other pieces and tokens of that PR from the game. Terminate all Alliances with that PR. This new NPR cannot be Allied or Vassalized.

Whenever one of that PR's Events are revealed, simply remove it from the Event display. In those Rounds where none of that PR's Events show up, auto-resolve any symbols on the additional Unpicked Event.

The second solution, which requires a bit of custom tweaking, is to replace the human player that leaves with a Bot player (see Solo & Bot Rules, p. 6)