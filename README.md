# DON'T WAKE THE MOON! — Echo Timing Study

## Premises
**Temporality × Feedback.** The 2-second replay of recorded player positions determines when the echo holds a seal. A visible progress ring, unlock timer, shield countdown and patience hearts provide feedback about the consequences of actions over time. Because the echo repeats the player’s past, feedback helps the player plan their future route.

## Play
Open `index.html` in a browser or publish these files together on GitHub Pages. Choose **Quick Echo (0.5-second seal hold)** or **Patient Echo (2-second seal hold)** before starting. Arrow keys / WASD or labelled touch buttons move the star. Space pauses. Save five locked dreams before five patience hearts are lost. A cyan shield activates immediately for five seconds. The echo is immune to clouds; only the player loses patience. To unlock a dream, the echo must stand on the blue seal for the chosen duration; because the echo replays a 2-second-old path, the player must stand there first.

## Comparison to try (not a claim of results)
- **Change:** required uninterrupted echo hold on the blue seal: 0.5 vs 2 seconds.
- **Same:** 2-second echo delay, five dream positions, cloud placement and initial motion, shield duration, starting location, five patience hearts, controls, and scoring. Each new run resets the same seeded layout.
- **Start:** reload/restart each condition and begin from the same starting position; alternate condition order between participants.
- **Task:** attempt to collect five dreams without waking the moon.
- **Observe:** completed dreams, hearts lost, seal retries, routes and timing choices. Ask which mode changed their movement planning and why. Do not assume which mode will be harder.

## Live-edit settings
At the top of `script.js`, change the `DESIGN` object: `echoDelay`, `shieldDuration`, `maxPatience`, `prizeTarget`, `sealOpen`, etc. The comparison mode sets `DESIGN.sealHold` to `0.5` or `2` in `init()`.

## Credits / AI Use
I used ChatGPT to help develop and improve my game, including coding support, testing ideas, and making adjustments. I made design decisions based on how I wanted the game to work. For example, I changed the shield to activate immediately and reduced the number of clouds to five because the screen felt too crowded. The game uses original visuals and does not include external images or audio.

## Game link
https://delfinsaltuk.github.io/dont-wake-the-moon/

## Before submission
Read and cite two readings from the course lab bibliography in a 315–385 word `RATIONALE.md`. Test the game with someone new, record a real observation, and practise making a live code change for the presentation.

## In-stage status HUD update
- Patience hearts and Golden Dream progress now remain visible inside the game stage.
- Shield status is prominent: cyan glow, countdown to 0.1 seconds, progress bar, and an expiring warning in the final second.
- No gameplay rules or comparison conditions were changed.

## Five-cloud update
Exactly five interactive pink clouds appear at once: four moving hazards near the active seal and locked dream, and one roaming cloud. Clouds move faster than in the previous edition; no additional hazards spawn over time. The background decorative clouds are also reduced for readability. Both comparison modes use the same five-cloud layout and movement rules.
