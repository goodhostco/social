# goodhostco/social

Public hosting for rendered @goodhostco social media (overlay images, carousel slides, reels), served by GitHub Pages so Instagram can fetch them by URL. Kept out of the website repo so posting never triggers a Netlify deploy.

- Written only by `/marketing-daily` and `/marketing` (rules in the private `goodhostco/web` repo, `marketing/`).
- Layout: `gen/<YYYY-MM-DD>-<slug>/NN.jpg`, `reels/<YYYY-MM-DD>-<slug>.mp4`.
- Files older than 21 days are pruned; Instagram keeps its own copy.
