# StatMuse-style Mini Site (Player + Team)
- Player page with **inline Career Highs** (now shows 3PM high too), dark mode, collapsible Add Game, season & career totals.
- Team page that shows **roster with PTS/REB/AST averages** and a **team games** log (date, opponent, score, W/L).

## Files
- `index.html` — Player page. Use query params like `?player=kyle-denzin&team=pretty-good`.
- `team.html` — Team page. Use `?team=pretty-good` (or `duncles`, `sweaty-already`).

## Images
Drop PNGs into `assets/` and update filenames if needed:
- Logos: `pretty_good_logo.png`, `duncles_logo.png`, `sweaty_logo.png`
- Portraits: `kyle_portrait.png`, `levi_portrait.png`, `findlay_portrait.png`

## Storage
- Player stats per player×team live in **localStorage**: `sm_player_stats_v2`
- Team games live in **localStorage**: `sm_team_games_v1`
