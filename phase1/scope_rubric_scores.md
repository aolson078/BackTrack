# Scope Inclusion Rubric Scores

Scoring scale: 1 (low/poor) to 5 (high/strong).

| Feature Candidate | User Value | MVP Necessity | Eng Complexity (inverse weighted) | Risk (inverse weighted) | Dependency Impact (inverse weighted) | Total | Decision |
|---|---:|---:|---:|---:|---:|---:|---|
| Auth (email/OAuth/guest) | 5 | 5 | 3 | 4 | 4 | 21 | Include |
| Catalog search + filters | 5 | 5 | 3 | 4 | 4 | 21 | Include |
| Playback core | 5 | 5 | 3 | 4 | 4 | 21 | Include |
| Tempo/transpose/loop | 5 | 5 | 3 | 4 | 4 | 21 | Include |
| Favorites/playlists | 4 | 4 | 3 | 4 | 4 | 19 | Include |
| Free/Premium entitlements | 5 | 5 | 2 | 3 | 3 | 18 | Include |
| Offline downloads | 4 | 3 | 2 | 3 | 2 | 14 | Defer to late MVP phase gate |
| Multi-stem mixer | 3 | 1 | 1 | 2 | 2 | 9 | Defer (Post-MVP) |
| Community features | 2 | 1 | 2 | 2 | 2 | 9 | Defer (Post-MVP) |
| Desktop app | 2 | 1 | 1 | 3 | 1 | 8 | Defer (Post-MVP) |

## Decision Threshold
- **Include in MVP:** score >= 18
- **Conditional include:** 14–17 (requires phase-gate justification)
- **Defer:** <= 13
