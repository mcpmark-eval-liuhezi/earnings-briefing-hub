# earnings-briefing-hub

Home for the quarterly Apple earnings briefing review — replacing the old ad-hoc email threads.

## Contents

- `digest.md` — the quarterly digest: fact-check verdicts, note index, schedule conversions, and the digest header date.
- `.github/workflows/briefing.yml` — manually triggered workflow (echoes "briefing hub online") as a hub health check.
- `briefing_extracts.pdf` — appendix: the "Figure 1" pages extracted from the research note. This artifact is produced in the analyst workspace alongside the source note; only the digest is committed to the repo.

## How to run the briefing check

1. Go to **Actions** → **Briefing**.
2. Click **Run workflow** on `main`.
3. Confirm the job log prints `briefing hub online`.
