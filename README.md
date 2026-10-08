# NotebookLM YT Video Generator

Browser-based video editor. Everything runs on your device; nothing is uploaded anywhere.

## What it does
- Trim the last N seconds of the main video
- Starting frame (image + music), ending frame (image)
- English or Hindi support page at the very end (5 sec)
- 10-second final audio over ending frame + support page
- Remembers your images/audio/support pages in the browser (not the main video)
- Output file keeps the main video's name

## Files (upload ALL to the repository root)
index.html, manifest.json, icon-192.png, icon-512.png, apple-touch-icon.png, favicon-64.png, README.md

## Publish on GitHub Pages
1. New repository -> name `nlm-yt-video-generator` -> Public -> Create.
2. Add file -> Upload files -> select all files above -> Commit changes.
3. Settings -> Pages -> Deploy from a branch -> main, / (root) -> Save.
4. Open https://YOUR-USERNAME.github.io/nlm-yt-video-generator/ after ~1-2 minutes.

## Update later
Open a file in the repo -> pencil icon -> edit -> Commit changes. Or Add file -> Upload files to replace it.

## Notes
- Export runs in real time and re-encodes the video (same resolution, high bitrate). Keep the tab open.
- "Choose folder" in settings works in desktop Chrome/Edge only.
