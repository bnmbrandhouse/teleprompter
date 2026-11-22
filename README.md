# Teleprompter

A free, browser-based teleprompter that follows your voice.

- **Voice mode:** the script advances as you read.
- **Auto mode:** scrolls at a speed you choose.
- **Manual mode:** scroll with the wheel, touch, or arrow keys.
- Text size from small to very large, horizontal and vertical mirroring, custom text and background colors.
- Import a script from TXT, DOCX, or PDF. Files are read in your browser and never uploaded.
- Selfie camera behind the text, with recording to a file on your device.

## Use it

Open `index.html` in Chrome or Edge (voice following needs the browser speech recognition). Or deploy the folder to any static host.

## Deploy

This is a static site with no build step. On Vercel, import the repository and deploy with the default settings.

## Notes

- Voice recognition is handled by the browser and may send audio to its speech service.
- PDF and Word import load PDF.js and Mammoth from a CDN.
- Recordings capture the camera only, not the prompter text.
