Pixel Invaders

A Space Invaders-style arcade shooter that runs entirely in the browser — no installs, no plugins, just open the page and play.

Play it here: https://claude.ai/artifact/6u6ZBd2gerdHTHHyYrP8L4

Pixel Invaders screenshot

Gameplay

Pilot a ship along the bottom of the screen and shoot down waves of descending enemies before they reach you. Each cleared wave spawns a faster one, so the challenge ramps up the longer you survive.

Score points for every enemy destroyed
3 lives — lose one if an enemy hits you or reaches your row
Wave counter tracks progress as enemies speed up
Game over screen with one-click restart
Controls
Action	Key	Touch
Move left	← or A	◀ button
Move right	→ or D	▶ button
Shoot	Space	● button

Touch controls appear automatically on phones and tablets.

Tech

Built with plain HTML5 Canvas and vanilla JavaScript — no frameworks, no build step, no dependencies. The whole game lives in a single index.html file.

requestAnimationFrame game loop for smooth, frame-based updates
Axis-aligned bounding box (AABB) collision detection for bullets vs. enemies and enemies vs. player
Classic "step and drop" enemy movement pattern
CSS custom properties for theming, with a dark neon-arcade look
Running it locally

No build tools needed. Just clone the repo and open the file:

bash
git clone https://github.com/<your-username>/pixel-invaders.git
cd pixel-invaders
open index.html   # or just double-click it
Hosting it yourself

Since it's a single static HTML file, you can host it anywhere for free:

GitHub Pages: Settings → Pages → deploy from the branch containing index.html
itch.io: zip the file and upload as an HTML5 project
Netlify / Vercel: drag-and-drop deploy, no config needed
License

Free to use, modify, and remix.
