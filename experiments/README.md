# Pulse Analytics — Growth Experiments (Fastlane brief substitute)

No "Fastlane" MCP tool exists in this environment. Substitute used for asset production:
deterministic SVG/HarfBuzz/ffmpeg pipeline (same system that produced posts 1-2), not
ElevenLabs generative video, chosen because it guarantees exact Pulse brand fidelity
(canonical logo geometry, IBM Plex fonts, exact palette) with zero risk of generic-AI
artifacts. Reported here per the brief's own rule on not silently swapping tools.

## Experiment log

| Exp ID | Concept | Platform | Format | Publish (Cairo) | Hypothesis | Baseline (recent FB posts) | Status |
|---|---|---|---|---|---|---|---|
| exp01 | "عدد الأسهم مش هو التنويع" — 8 equal icons animate into real 38/22/12/8/7/5/4/4% concentration | Facebook | 7.6s vertical video, 1080x1920 | 2026-09-23 12:00 | Motion + a stated misconception ("انت مش متنوع زي ما فاكر") will beat this Page's static posts on watch-through, shares and comments | Posts 1-2 (2026-09-19/20): ~5-9 reach, 0-2 interactions each | Scheduled |
| exp02 | Same concept, 3-card static carousel version | Facebook | 3x 1080x1350 images | 2026-09-24 12:00 | Isolates whether the *contradiction* (not the motion) is what drives sharing — same idea, no video production risk | Same baseline as exp01 | Scheduled |

exp01 and exp02 intentionally run the same underlying idea in two formats, one day apart,
so the comparison isolates format (video vs. carousel) rather than concept.

## Selection notes (from the 5-concept experiment brief)
Produced: exp01 (video), exp02 (carousel) — both from concept "ده مش تنويع" (diversification contradiction).
Held back for now: concept #4 (product-proof video using real Pulse UI) — needs an actual
demo-mode screenshot pulled from the product before animating, to satisfy "don't invent
product functionality." Concepts #1 and #5 not produced this cycle (see chat reasoning:
#1 duplicates post 1's idea before we have a read on post 1; #5 was judged too content-free).

## Cadence note
These 2 posts are ADDITIONAL to the standing ~1 post/day relaunch cadence, not a
replacement. This is a temporary increase for the duration of this controlled experiment
(brief section 7 requires reporting, not silently absorbing, any cadence change).

## Measurement plan
Read FBPO metrics for both post IDs starting 24h after each goes live, compare against the
9-post baseline in performance-log.md. Flag BREAKOUT CANDIDATE only if reach/shares/comments
materially exceed that baseline with a plausible causal read tied to the creative — not on
volume alone.
