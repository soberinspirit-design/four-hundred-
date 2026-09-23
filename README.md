# four hundred

A goal-setting and marking app for Substack or blog creativity — set your own four goals, a hundred each, then mark your progress as the week happens.

No build step, no server, no account — a single static page that stores your marks in the browser's local storage on your device.

## How it works

- Four goal cards, each with a name, unit, weekly target, and step amount — fully editable via the pencil icon.
- Defaults (`write` / `engage` / `share` / `reach`, target 100 each) are just a starting point for a Substack-style practice; rename and retarget them for any blog or creative habit.
- Tally buttons (`−1`, `+1`, or the big step button) mark progress against each goal.
- A combined bar shows the week's total against the sum of all four targets — 400 by default.
- A Monday–Sunday strip shows which days you touched any goal.
- **Keep a copy**: view the week as a decorative log, save it as a dated `.txt` file, or copy it to paste into notes or a Substack note.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Customize

Everything lives in `index.html` — the default goals are set in the `defaultGoals` array near the top of the script.
