
## Dark-Fin Theme for Jellyfin

Now in beta. There is still polishing to be done here and there, and some areas of the UI haven't been completely finalized yet, but most of the main styling is present. PRs are welcomed - whether it be to make things more efficient, performant, or to polish the overall theme. Right now there may be quite a few bugs since I haven't had very many people testing it on different browsers and monitor setups.

Finity is a modern, minimal, and elegant theme for Jellyfin. Designed with clarity and immersiveness in mind, it introduces sleek typography, and a clean layout to elevate your media browsing experience.

> IMPORTANT

>This theme is meant to be used in conjunction with Jellyfin's included "Dark" user theme (found in your user settings). Using any other built-in Jellyfin theme is NOT supported at this time, and will almost certainly look terrible.

Finally, make sure to enable blurred placeholders for images and disable backdrops in your user display settings. Not doing so may cause several important aspects of the theme to not render correctly (such as the gradient mask for show backdrops)
Features

 -  Grid-style season view, aiming to somewhat emulate Plex's look
 -  Minimalist UI adjustments for improved readability and visual polish
 -  Customizable theme powered by CSS variables for colors, sizing, layout, and visibility
 -  Rubik font integration for sleek typography
 -  Hover effects, shadows, and lift transitions for a more dynamic, tactile feel
 -  Redesigned cards and buttons with rounded corners
 -  Collapsible, pill-styled tags

---
## ✨ Installation

add this to the top of your Jellyfin's custom CSS field:

> @import url("https://<!---->cdn.jsdelivr.net/gh/Marotinh0/Dark-Fin@main/Dark-Fin.css");

---
## 🔧 Compatibility

- Tested with Jellyfin 10.11.6
- Not guaranteed to be compatible with unofficial forks or third-party clients
- At the moment, primarily designed for desktop/web. Works on mobile devices, but a few things will look different - mobile needs some more work
