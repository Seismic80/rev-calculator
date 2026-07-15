# Revenant Weapon Hunt Calculator

Decide whether hunting revenant weapon drops (Craw's bow, Thammaron's sceptre, Viggora's chainmace) in Old School RuneScape is faster **on a Krystilia slayer task** (via Turael skipping) or **off task** — and what the trade-off costs you.

**Use it here: https://trackingse.github.io/rev-calculator/**

## What it shows

- On-task vs off-task time per weapon drop, including task-acquisition overhead, with a break-even analysis (minimum task chance / skips per hour for skipping to win).
- Loot forgone by skipping (4 × K<sub>on</sub> fewer kills), itemised in the wiki's average-drop-value format with live GE prices. Left-click drops you leave on the ground to exclude them.
- Slayer XP lost by hunting off task: revenant task kills + Turael filler tasks (with a block-list picker).
- Larran's keys per hour on task, and keys lost entirely by going off task.

## Data sources

All mechanics and rates are taken from the [OSRS Wiki](https://oldschool.runescape.wiki) — chiefly [Template:Revenants/Drops](https://oldschool.runescape.wiki/w/Template:Revenants/Drops), [Template:WildernessSlayerDropTable](https://oldschool.runescape.wiki/w/Template:WildernessSlayerDropTable), [Krystilia](https://oldschool.runescape.wiki/w/Krystilia), and [Turael/Slayer assignments](https://oldschool.runescape.wiki/w/Turael/Slayer_assignments) — with source comments in the code. Live prices come from the [wiki's real-time prices API](https://prices.runescape.wiki/), with a bundled snapshot fallback. The page runs a self-check panel that re-derives every hardcoded rate from the wiki formulas.

Single self-contained HTML file — no build step. Open `index.html` locally or serve it statically.
