# Zain's Random Project Ideas

A modern, Minecraft-atmosphere project homepage built with plain HTML, CSS and JavaScript.

## Personalise the hero background

Add your own images to the `assets` folder:

- `assets/minecraft-background.jpg` — your Minecraft landscape screenshot with shaders. This is the large full-screen hero background.
- `assets/skin.png` — optional transparent PNG render of your Minecraft skin. It is layered over the landscape on the right. If your skin is already part of the background screenshot, remove the `<img class="player-skin" ...>` line from `index.html`.

The About section also uses the landscape image as its background.

## Add your projects

Open `index.html`. Duplicate an `<article class="project-card">` inside `#projectGrid`, then edit:
- `data-category` (`web`, `game`, or `other`)
- project name and description
- project link
- status label

Update the contact email (`hello@example.com`) to your own address.

## Publish with GitHub Pages

1. Put `index.html`, `style.css`, `app.js`, and the `assets` folder in your repository root.
2. Add your two images to `assets` using the exact filenames above.
3. Commit and push.
4. In GitHub, open **Settings → Pages**.
5. Select **Deploy from a branch**, choose your main branch and `/ (root)`, then save.

The design uses Google Fonts (DM Sans and Space Mono); system fallbacks are included.
