# linkedin-content

Research and drafting workspace for Achal Tiwari's LinkedIn posts. Four
scheduled cloud routines write here; nothing is published automatically. The
finished post is copied into LinkedIn by hand.

## Pipeline

| Routine | Cadence (UTC) | Writes |
|---|---|---|
| `linkedin-trend-miner` | daily 01:00 | `trends/YYYY-MM-DD.md` |
| `linkedin-post-writer` | daily 02:30 | `posts/YYYY-MM-DD.md`, appends `posted_log.md` |
| `linkedin-hook-analyzer` | Sundays 15:00 | `hook_playbook.md` |
| `linkedin-peer-watch` | Tue and Fri 17:00 | `peer_insights.md` |

The miner runs 90 minutes before the writer so each day's post starts from a
shortlist that has already been fact-checked.

## Files

- `trends/` one file per day: candidate stories, verified facts, source links,
  and a note on why each is or isn't something Achal can add a real POV to.
- `posts/` one file per day: the finished, copy-paste-ready post plus the
  image brief.
- `posted_log.md` every angle already used. The writer reads this first and
  must not repeat one. This is the file that makes "don't repeat yourself"
  actually enforceable.
- `hook_playbook.md` opening lines that earn the click, and ones to retire.
- `peer_insights.md` what comparable Indian PM and AI-builder voices are
  posting, and the format gaps worth owning.

## House style

Plain, human business English. No em dashes or en dashes: use commas, colons
or full stops. No corporate hype. Truth only, never fabricate a stat, a quote
or a claim.
