# Aurelius Atelier watch website

Standalone static website using the supplied watch frame ZIP. No framework, build step, server, database or paid service is required.

## Upload to GitHub Pages

Upload the contents of this folder to the repository root that GitHub Pages serves. Keep `index.html`, `styles.css`, `app.js`, and the `assets` folder together. The eight supplied frames must be at `assets/frames/frame-0001.jpg` through `frame-0008.jpg`.

## Animation

The hero section is a tall scroll journey. Its stage stays pinned while the supplied frames advance from assembled to disassembled and back as the visitor scrolls. Scrolling upward reverses the sequence. The arrow buttons step through frames; Pause rotation freezes the smooth interpolation so the visitor can inspect a frame. The browser preloads the frames and draws them to a responsive canvas.

The animation uses the actual provided images. It does not fake a 3D watch model. Because the source ZIP contains eight frames, the motion has eight visual steps; supplying more frames later will make the movement smoother.

## Included interactions

- Sticky scroll-controlled watch assembly animation
- Reverse scrolling and reduced-motion support
- Previous, next and pause controls
- Product collection cards
- Responsive mobile layout and collapsible-style mobile navigation presentation
- Private enquiry form with validation and confirmation feedback
- Keyboard focus states and skip link

## Customise

Replace the Aurelius name, copy, product prices and contact wording in `index.html`. Replace the three CSS product illustrations with real watch photos by editing each `.card-image` block and adding local image files. Do not describe sample prices as live prices until they are confirmed. The enquiry form is front-end only and does not send email; connect it to a secure form service or backend before using it for real customers.

## Local preview

Open `index.html` directly for the basic experience. If your browser blocks local image loading, serve the folder with XAMPP by placing it in `C:\xampp\htdocs\watch-website` and opening `http://localhost/watch-website/`. GitHub Pages serves it directly.
