# The Universe of You 💗

A small story-driven friendship adventure made by Durga for Banshika.

## Play locally
Open `index.html` in a modern browser. An internet connection is needed for the Three.js and Google Fonts CDN assets.

## Publish with GitHub Pages
1. Create a **public** repository named `the-universe-of-you` on GitHub.
2. Upload the contents of this folder (make sure `index.html` is at the repository root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait a minute or two. GitHub will show your game URL, usually:
   `https://YOUR-USERNAME.github.io/the-universe-of-you/`

## Add “Dilruba Dilkashi”
The game intentionally does not include a copyrighted song file. On the final screen, choose an audio file from your device using **Add the song “Dilruba Dilkashi” from your device**. Use an audio file you have the right to use. The file is played locally and is not uploaded by the game.

If you want the song to play for every visitor automatically, you would need to add an audio file you have permission to distribute to `assets/music/` and update the audio setup in `index.html`. Browsers may still block autoplay until the player interacts with the page.

## Personalization
The current version includes Banshika and Durga in the story and final letter. Edit the text in `index.html` to customize the messages, memories, and puzzle.

## Notes
- Responsive layout for phones and desktops.
- Includes an ambient Three.js starfield and floating crystal.
- Requires WebGL for the 3D background; the story UI still works if WebGL is unavailable.
- Do not put private photos, phone numbers, addresses, or other sensitive information in a public repository.
