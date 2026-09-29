# Streambox

A polished, responsive video-watching MVP that runs entirely in the browser.

## Features

- Search videos by title, creator, or category
- Category filtering
- Video cards with duration and metadata
- Full-screen-style watch modal with HTML5 playback
- Add local videos from your device (stored for the current session)
- Responsive dark UI with no build step required

## Run locally

Open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Notes

The demo catalog uses public sample videos and thumbnail images. A production version would add authentication, persistent uploads, transcoding, storage, and a backend API.
