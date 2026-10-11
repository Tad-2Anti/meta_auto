# Meta Instagram Agent

Local-first Instagram content system for Meta (Reels, carousels, Stories).

Adapted from [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) (MIT). Skills write drafts; you approve and post. Future: automated video edit/create skill (user will supply).

**Nothing auto-posts.** Official Meta Content Publishing API requires a developer app, Professional account, linked Page, and approved token. Browser automation risks account action. Design is human-in-the-loop.

## Today (2026-10-11)

- Content plan for the week
- Competitor / inspiration list (research in progress)
- First Reel script + caption + beat sheet (ready to film or generate)
- Voice profile starter
- Placeholder for video automation skill

## Structure

```
content/
  plan-week-of-2026-10-12.md
  competitors-inspiration.md
  first-reel-2026-10-11.md
  voice.md
skills/          # future: drop video-edit skill + adapted ig-* skills
scripts/         # future: Python tools (hookscore, beats, caption, humanize)
```

## Next

1. Film or generate the first Reel from `content/first-reel-2026-10-11.md`.
2. Post manually on Instagram (or via approved Meta API once credentials are ready).
3. Supply the video automation skill; we integrate it here.
4. Connect Meta Business / Instagram Professional for insights or publishing if desired.

## Philosophy

- Reels for discovery (non-followers).
- Hook in first 2s, payoff + loop.
- Score hooks, time beats, lint captions, humanize drafts.
- Rank inspiration by outlier multiple (views / account median), not raw views.
- 4–5 posts/week, ≥3 Reels.
