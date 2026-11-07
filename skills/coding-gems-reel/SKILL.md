---
name: coding-gems-reel
description: Create a vertical tech reel with a warm paper, yellow-highlight coding aesthetic, using a real GitHub demo or a concrete technical comparison. Use for repo discoveries, Git versus GitHub explanations, and practical AI/developer tools; inspired by the supplied NoteGems references.
---

# Coding Gems Reel

Create an original 1080×1920, 30 fps reel, usually 25–45 seconds and at most 60 unless requested otherwise. Adapt the NoteGems references' cream paper, marker highlights, cutout cards and clear teaching structure without copying their branding, script, voice or artwork. Read [reference notes](references/source-notes.md) when matching the supplied videos.

## Choose the teaching mode

- **Repo discovery:** one task → actual result → repository → how to start → one limitation. Two repos are appropriate only when their contrast is the lesson.
- **Comparison:** one confusing situation → A and B side by side → one worked example → a sentence explaining when to use each.

The user's channel covers tech, AI, repositories and Elon-related technology. Exclude celebrity/personal-life news and unrelated history. Elon stories belong here only when there is a concrete software or engineering lesson. Do not infer that every tech story belongs in this format.

## Evidence before script

Open the actual repository and relevant official documentation. Verify its purpose, license, setup, recent status, dependencies and any cost claims. Distinguish an open-source interface from open weights or free hosted inference. An independent implementation is not the original company open-sourcing its product.

Attempt a small, authorized local demonstration when feasible. Record inputs, outputs and failures. Never say “I tested” without performing the test. If execution is unavailable, show the documented flow and label it as such. Never invent stars, benchmarks or successful results. Write dated URLs and claim-to-source notes in `SOURCES.md`.

## Hook and story

Lead with the viewer's task or a visible misconception in the first two seconds. Prefer “Turn this receipt into spreadsheet rows” to “This repo is insane.” For a comparison, begin with a question that the demonstration can answer. Deliver the answer inside this reel.

Suggested pacing, adjusted to measured narration:

| Time | Picture and purpose |
| --- | --- |
| 0–2s | Finished result or concrete problem, one headline |
| 2–7s | Identify the tool or distinction |
| 7–25s | Two or three legible demonstration steps |
| 25–35s | Limitation and useful takeaway |
| Last 2–3s | One relevant action: try, save, or follow the series |

Use the requested language. Otherwise infer it from the supplied script; with neither specified, draft conversational Nepali with familiar English technical terms and state that assumption. Do not imitate a Hindi reference's language automatically. Keep product names and code in Latin. Shorten the script before accelerating the voice.

## Visual recipe

- Warm paper `#F5F0E6`, ink `#181818`, marker yellow `#F5D94F`, small purple accent `#8064C6`. Use subtle texture, not distressed text.
- One dominant demo/card per shot. Approximately 72–100 px main titles, 46–60 px explanatory labels, and 48–64 px captions at 1080 px width; inspect actual mobile-size readability.
- Flat outlined cards, slightly rotated cutouts and hand-drawn arrows. Keep a consistent frame; alternate code, diagram and real UI when the explanation calls for it.
- Crop and zoom the exact relevant interface region. Do not fit a whole repository page into a tiny rectangle. Never letterbox a landscape composition into the portrait master.
- Reserve the lower quarter for platform controls and caption clearance. Keep important copy inside the central 80%; check actual overlay collisions. Phrase captions use at most two lines and must not repeat the headline unnecessarily.
- For Nepali, use a real Devanagari font file, zero letter spacing and adequate matra padding. Animate words or phrases, never individual Unicode code points.
- Motion explains an action: cursor selection, card handoff, code diff or arrow reveal. Branding is quiet and uses the user's identity.

## Produce and verify

For a script-only request, deliver the script and shot plan. For a complete video, use the installed `hyperframes` skill and read its current contract plus `hyperframes-core`; use `media-use` for narration/assets and `hyperframes-animation` for motion. Resolve these skills from the current skill catalog or installed locations; if a required dependency is missing, report it and continue independent preparation. This skill's portrait format overrides generic landscape defaults. A complete-video request authorizes local production through MP4; announce direction and continue without extra creative approval gates. Do not publish.

Write `BRIEF.md`, `SOURCES.md`, `SCRIPT.md` and `STORYBOARD.md` in the video project. Measure narration before finalizing timings. Use deterministic seek-safe animation and real, attributed interfaces. Keep music below speech and use sparse action-linked effects. Do not clone a reference voice.

Run the current HyperFrames check and snapshot review. Inspect the opening, the most detailed UI, caption changes and ending at phone size. Listen to the full audio. Verify the rendered dimensions, duration and audio stream with ffprobe. Deliver the playable MP4, editable project, title, description and sources; include any untested claim/demo limitation. Never promise views or followers.
