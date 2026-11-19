# Flappy Bird

A fast, polished Flappy Bird-style browser game built with plain HTML, CSS and JavaScript. No frameworks, no build step, no dependencies.

## Features

- Tap / click / Space to fly through the pipes
- Day, sunset and night cycle as your score grows
- Collectible coins with a persistent wallet
- Bird shop with 6 skins, each with a unique power:

| Skin | Power |
|---|---|
| Classic | Shield: 1 free hit per run |
| Ninja | Slow-Mo: pipes move 18% slower |
| Fire | Blaze: every 7 pipes, a 3s unstoppable dash |
| Golden | Magnet: nearby coins are pulled to you |
| Angel | Float: lower gravity, easier flying |
| Rainbow | Double: 2 points per pipe + 2x coins |

- Daily bonus coins
- Custom music: pick any audio file from your device (saved in the browser), plus a built-in tune and a volume slider
- Sound effects, particles, screen shake, medals and a saved best score
- Works on mobile and desktop, fixed 60 Hz game speed on every device

## Run locally

Just open `index.html` in a browser.

## Deploy with GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your game will be live at `https://<your-username>.github.io/<repo-name>/`.

## Controls

| Action | Mobile | Desktop |
|---|---|---|
| Fly | Tap anywhere | Click, Space or Up arrow |
| Shop / Music | Buttons at top right | Same |

## License

MIT. See [LICENSE](LICENSE).
