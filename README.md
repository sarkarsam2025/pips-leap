# Pip's Leap

A simple, original side-scrolling platform game that runs in the browser. Help Pip run, jump, stomp the Grumbles,
collect gems, ride the moving clouds and reach the EXIT.

**Play it:** https://sarkarsam2025.github.io/pips-leap/

## Controls
- **Keyboard:** Arrow keys or A / D to move. Space, W or the up arrow to jump (hold for a higher jump). M mutes the sound.
- **Phone / tablet:** on-screen buttons.

## How it's built
Everything is in one file, `index.html`: plain HTML and JavaScript with a canvas. There's no build step and nothing to install.

- **Change the level:** edit `buildLevel()`. Helpers like `ground()`, `plat()`, `pillar()`, `stairs()`, `gems()`,
  `spikes()`, `enemy()` and `cloud()` take tile positions (row 0 is the top, the ground is rows 15-16).
- **Change how it feels:** tweak the physics numbers near the top (`GRAV`, `JUMP_V`, `MAX_SPEED`, ...).

## Suggesting changes
Make a branch, commit your change and open a pull request. Every change to `main` redeploys the game page automatically.
