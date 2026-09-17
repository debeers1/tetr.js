# Tetr.js — 40G JDB & Dig! JKnack

A browser-playable customization of [Farter’s Dig Mod](https://github.com/farteryhr/tetr.js), retaining the original authors’ credits and MIT license.

[**Play the game**](https://debeers1.github.io/tetr.js/)

## Added modes

- **40G JDB:** instant gravity, Marathon level-40 timing, no entry delay, and a 300-line finish.
- **+1 Dig! JKnack:** original Dig garbage patterns with 20G gravity and timing progression; endless until top-out. Garbage continues rising during entry delay.
- Original **20G** remains available. The earlier custom 30G menu entry has been removed; its replay support remains for compatibility.

Choose a mode in the menu to play. Controls and handling can be customized in the game. Each browser stores its own preferences.

## Hosting

This is a static HTML/CSS/JavaScript game. Publish the root of the `gh-pages` branch with GitHub Pages. No installation or account is needed to play.

The legacy upstream leaderboard uses an external HTTP service and is not supported on this HTTPS-hosted copy. The custom modes do not submit scores. Local replay export/import is supported. Historical navigation links belong to the original site.

## Upstream project

# tetr.js

[Have a try](http://farter.cn/tetr.js) in your browser.

### Default Controls:

- **Rotate Left:** Z
- **Rotate Right:** X
- **Rotate 180:** Shift
- **Hold:** C
- **Hard Drop:** Space
- **Shift Left:** Left Arrow
- **Shift Right:** Right Arrow
- **Restart:** R

## Current mechanics and features

- Tetris Guideline compliant
    - Colors
    - Random generator, first bag never spawns Z, S, or O piece first.
    - SRS
    - Gameover by lock out or block out
    - Hold
    - Piece preview
- Game statistics like PPM, Time, etc.
- Multiple mino skins
- Stack outline
- Configurable gravity
- 60 FPS
- Fast code and drawing
- DAS and DAS delay settings
- Configurable controls
- Adjustable game size
- Ghost piece color and transparency
- Responsive design
- Preload das preservation during countdown
- Finesse faults counter.
- Farter's Dig mod:
    - Dig modes
    - Mobile design
    - Replays
    - Leaderboards

## Planned future mechanics and features

- More game modes (ultra, etc)
- More rotation systems
- Training mode, 2step trainer, patterns, etc
- Stats logging
- Sound effects
- T-spin and twist detection
- Custom mino skins (or at least a selection)

## TODO misc

- Help page
- Feedback button
