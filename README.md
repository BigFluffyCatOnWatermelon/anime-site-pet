# Anime Site Pet (Tampermonkey)

A small self-contained anime-style site mascot for Twitch and most ordinary websites. The character is drawn using inline SVG, so the script does not download character assets or send data to external services.

## Install

1. Open the [raw userscript](https://raw.githubusercontent.com/BigFluffyCatOnWatermelon/anime-site-pet/main/anime-site-pet.user.js) with Tampermonkey installed.
2. If the install prompt does not appear, create a new userscript and paste the raw file contents.
3. Save, enable the script, and refresh the page.

## Controls

- Left-click the character: interact and trigger a reaction.
- Right-click the character: open settings.
- `Alt` + `Shift` + `P`: open settings.
- `Alt` + `Shift` + `H`: show/hide the character.

## Features in v0.1.1

- Autonomous actions: walk, run, jump, sit, sleep, dance, look around, blink, stumble, and recover.
- Pointer curiosity and occasional playful chases.
- Optional platform discovery on buttons, images, panels, and video elements.
- Twitch reactions to chat activity and video pause/play state.
- Persistent settings for size, speed, activity, reduced motion, speech bubbles, and interactions.
- Inline SVG character; no external assets, API calls, analytics, or chat messages.

## Notes

This is an early prototype. DOM layouts differ across websites, so platform behavior can be imperfect on some pages. The script runs on ordinary HTML pages and may not be able to inspect content inside cross-origin iframes. It does not control Twitch or send messages in chat.
