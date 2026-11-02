---
name: setup
description: Set up, run, and help customize the blixvip/NullMotion application.
disable-model-invocation: true
---

Help the user work with https://github.com/blixvip/NullMotion.

This is an unofficial helper. It does not embed the application inside Claude.

Check that the current session has local filesystem and terminal access.
If unavailable, explain that a local Claude Code session is required.

Reuse the user's existing NullMotion folder when provided.
Otherwise, agree on a writable project location and clone:
https://github.com/blixvip/NullMotion.git

Never overwrite an existing directory or modify the installed plugin cache.

Read README.md, AGENTS.md, package.json, and relevant documentation.
Check the documented prerequisites before running commands.
The current project requires Node.js 22 or newer.
Reuse installed tools that already meet the requirements.

Check whether the application is already running.
Otherwise, start it using the documented command.
On Windows PowerShell, use npm.cmd start.
Report the actual local URL and any startup errors.

Explain how to play included examples and export an MP4.
For custom references, branding, or animation changes, inspect the
relevant source and implement the user's requested changes.
Distinguish existing features from functionality requiring new code.
Preserve licenses, attribution, and unrelated user changes.

Run appropriate checks after changes.
Never claim a video was generated or exported without verifying the output.
