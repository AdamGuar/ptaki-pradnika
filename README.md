# Ptaki Prądnika Czerwonego

An interactive HTML presentation about birds found in Prądnik Czerwony, a district of Kraków, Poland. Created for kindergarten children.

## Features

- 12 bird species + a surprise guest 🐿️
- Photo gallery for each bird with multiple shots
- Bird call audio for each species
- Fun facts written for young children
- Bonus slide: Introduction to camera anatomy (body vs. lens)
- Keyboard and touch/swipe navigation
- Fully static — works on GitHub Pages with no backend

## Navigation

| Action | Control |
|---|---|
| Next photo | `→` or click |
| Previous photo | `←` |
| Next bird | `Space` / `Enter` / `↓` |
| Previous bird | `↑` |
| Play bird sound | 🔊 button |
| Swipe left/right | touch devices |

## Credits

### Bird Sounds
All bird audio files sourced from:
**[avibirds.com — Bird Sounds & Calls](https://avibirds.com/bird-sounds-calls/)**

### Bird Photography
All bird photographs are licensed under the **Creative Commons (CC)** license.

## Running Locally

No build step needed. Simply serve the folder with any static HTTP server, for example:

```bash
python -m http.server 8765
```

Then open `http://localhost:8765` in your browser.

## Hosting on GitHub Pages

1. Push the repository to GitHub (must be **Public**)
2. Go to **Settings → Pages**
3. Set source branch to `main`, folder to `/ (root)`
4. Save — your site will be live at `https://<username>.github.io/<repo-name>`
