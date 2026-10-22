# Daily Budget (web version)

A web version of the Daily Budget iPhone app. Same budget math, same calendar,
same paycheck planner. Backups use the same format as the iPhone app, so data
moves over when someone switches to the full app.

Not included (iPhone app only): widgets and bill/payday reminders.

## Put it online (free, GitHub Pages)

1. On github.com, create a new public repository, e.g. `dailybudget`.
2. Click "Add file" -> "Upload files" and drop in everything in this folder.
3. Go to Settings -> Pages. Under "Branch", pick `main` and `/ (root)`, then Save.
4. After a minute it's live at https://masonrichards-jpg.github.io/dailybudget/

## Install on iPhone

Open the link in Safari, tap Share -> "Add to Home Screen", then open it from
the home screen. Data is saved on each phone. Use Settings -> Export backup now
and then.

## Updating

Upload the changed files, and bump VERSION in sw.js (e.g. "dailybudget-v2") so
phones pick up the new version.
