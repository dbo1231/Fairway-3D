# Fairway Greens — Realistic Mini Golf

A GitHub Pages-ready Three.js mini-golf game with terrain-aware rolling, wind, rough, sand, water hazards, a cup-lip check, three designed holes, audio generated in-browser, and responsive controls.

## Publish to GitHub Pages

1. Create a new GitHub repository and upload **the contents** of this folder (not the folder itself).
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push to the `main` branch. The included workflow installs dependencies, builds the game, and deploys it.
5. Open the URL displayed in the Pages deployment after the workflow finishes.

The Vite configuration automatically detects your repository name for GitHub Pages.

## Local development

```bash
npm install
npm run dev
```

## Controls

- Drag backward from the ball and release to putt.
- Press `R` to reset to the tee.
- Press `V` to change camera view.
- Press `M` to toggle sound.

## Notes

The game is fully self-contained except for the Three.js npm package and a Google font. No copyrighted texture or audio packs are included.
