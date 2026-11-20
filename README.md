# Project demos

Project index: https://neverwinla.github.io/

## MIMIC Universe

Live site: https://neverwinla.github.io/mimic-universe/

A self-contained trajectory viewer exported from `mimic-universe`.
The page replays recorded thinking and SQL character by character, then reveals tool responses and result rows. It supports play/pause, seeking, speed control, fullscreen, task filtering, complete model inputs and evaluation.

Click **播放轨迹** beside the task title to start. Display timing is chosen for readability; original runtime statistics are shown separately.

```text
index.html                 # Project index; forwards legacy #run= links
mimic-universe/index.html  # MIMIC Universe trajectory viewer
```

Update `mimic-universe/index.html` and push to `main` to deploy the viewer. Add future projects in separate folders and link them from the root `index.html`. GitHub Pages serves the repository root; no build dependencies are needed.

Task links use `/mimic-universe/#run=aki__variant_2`. Old root links such as `/#run=aki__variant_2` automatically forward to the new path, preserving query parameters and the selected task.
