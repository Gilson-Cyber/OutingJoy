# OutingJoy v8

Nationwide family discovery prototype for GitHub Pages.

## v8 improvements
- Venue website is preferred when OpenStreetMap provides one.
- If no venue website is available, “Find official site” opens a targeted Google search instead of dumping the user onto an OpenStreetMap record.
- Visible full-screen loading state while nearby places are being fetched.
- Price tile on each card:
  - Free / usually free when supported by source data
  - Parsed per-person and family-of-four estimate when source data actually includes a numeric admission charge
  - “Verify price” otherwise
- Military filter now surfaces:
  - places explicitly tagged with a military benefit, and
  - museums/attractions where users are prompted to check programs such as Blue Star Museums.
- Military candidate listings are clearly labeled “CHECK MILITARY BENEFIT” so OutingJoy does not invent discounts.
- All seasonal hours, admission, parking, and access should be verified before traveling.

## Publish
Upload `index.html`, `README.md`, and `GITHUB_UPLOAD_INSTRUCTIONS.txt` to the root of the GitHub repository.
GitHub Settings → Pages → Deploy from a branch → main → /(root).
