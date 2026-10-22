# Yashaswini Jain · My Powerpuff Universe

A Powerpuff Girls inspired personal portfolio following the structure of https://thezeroquotient.com/portfolio: a full-screen click-to-enter scene, an animated reveal, a profile sidebar, rounded content panels, tabbed experience, side quests, and a visitor interaction.

The implementation uses an original pink heart and Townsville-style skyline instead of the reference's Pokémon imagery. It follows the reference's interaction and layout structure; it is not an exact copy of its artwork. The user’s new photo is shown with CSS cropping; clothing and facial features are unedited.

## Run and deploy

No build or dependencies are required. Serve the repository root with any static server (for example `npx serve .`). For GitHub Pages, choose Settings → Pages → Deploy from a branch → main / root. All local URLs are relative and support subdirectory hosting. Direct entry to `#details` skips the intro. Without JavaScript, the profile content is visible.

## Content and assets

- `index.html`: profile, experience, projects, interests, contributions, explorations and education.
- `style.css`: responsive scene and profile layout, heart, skyline, clouds and motion.
- `script.js`: intro navigation, keyboard-accessible experience tabs, project filters and visitor superpowers.
- `assets/portrait-new.jpeg`: user-selected personal photo, originally jito.jpeg.
- `assets/resume.pdf`: latest available résumé (21 September 2026), carried forward from the user's updated portfolio.
- `assets/favicon.svg`: original heart-theme companion icon.

The visitor wall saves the last 12 superpowers in localStorage on the visitor's device. It is not a shared public guestbook and has no backend, analytics or account system. Storage failure is handled with session-only feedback. Fonts are loaded from Google Fonts with local fallbacks.

Reduced-motion preferences, visible keyboard focus, skip-intro navigation, semantic tabs, keyboard arrow navigation, live filter counts, descriptive image text and responsive layouts are included.

## Credits

Design reference: https://thezeroquotient.com/portfolio. Prior portfolio/content source: https://github.com/yoshjayn/Portfolio-React. Personal portrait and résumé supplied by the user. Original HTML/CSS/JavaScript implementation; no source or artwork copied from the reference. An unofficial fan-inspired project, not affiliated with Powerpuff Girls rights holders.

## Townsville animation update

The portrait has a centered, capped 3:4 frame across responsive widths. Clouds continuously drift in both scenes. Generated Blossom, Bubbles and Buttercup sprites fly left-up, straight up and right-up, with color trails, and depart together when entering the profile. Reduced-motion preferences show a static trio and stationary clouds. Character sprite: assets/powerpuff-trio.png, produced with the built-in image generator. No changes to the user's photograph.
`nThe profile now uses assets/portrait-cartoon.png: the user-approved cartoon interpretation of the supplied photo, generated with the built-in image tool. Original personal photo remains in assets/portrait-new.jpeg for archival/reference use.
`nThe entrance now uses an original CSS Chemical X bottle: bubbling green liquid, glass highlights, a stopper-pop and burst animation on entry. It replaces the huge heart. The user chose this entrance concept.
