# Chess (PWA)

Chess game that works in the browser and can be installed on a phone or computer.

## Features
- Play against the computer: Easy, Medium, Hard
- Two players on one device
- Light and dark mode
- Hint and single-step undo
- No timer
- Works offline after the first load

## Files
| File | Purpose |
|---|---|
| index.html | The whole game (board, rules, computer player) |
| manifest.json | App name, colours and icons for installing |
| sw.js | Service worker for offline use |
| icon-192.png, icon-512.png | App icons |

## Publish on GitHub Pages
1. Upload all files to the root of a GitHub repository (index.html must be at the top level).
2. Go to Settings > Pages, choose Deploy from branch, select `main` and `/ (root)`.
3. Open `https://<username>.github.io/<repo>/`.

## Make an Android/Windows app
Paste the GitHub Pages link into https://www.pwabuilder.com and download the package.

## Notes
- Pawn promotion is always to a Queen.
- In computer mode you play White. Undo takes back your move and the computer's reply together.
