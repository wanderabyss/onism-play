---
title: "Public README links show readable link text, never bare URLs"
author: Nikhil
date: 2026-11-12
branch: main
id: l-a077f75d
scope: repo
status: active
src: agent
touches:
  - README.md
---

## Decided
In the public repo's README, every link is markdown link text (e.g. [play.onism.ai](https://play.onism.ai), [Install guide](...), a mailto link for the contact address), because the user does not want raw URLs shown on the page.

## Tried and ruled out
Pasting the URL as plain text in the link list: the user corrected it right after the first push, so it had to be fixed in a second commit.

## Watch out
Applies to any new README bullet or section, otherwise the same correction repeats.

In the code: README.md in the wanderabyss/onism-play public repo (local copy ~/Movies/onism-play).
