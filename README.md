# Alchemy — potion prototype

Play: https://georgeburda.github.io/alchemy-proto/

A reskin of the Idol Gems prototype in a potions & alchemy theme. The math is the same (RTP ≈ 92%, bonus 1 in 200 spins, fixed bet 1). It's play money only.

- **Base game:** 4 conveyor belts drop ingredients onto 5 scale pans. The weights are 1g / 3g / 10g, and 1g pays 0.05 on a winning line. Essence drops (an ingredient with a glowing droplet) fill the jars. The jars are visual only.
- **Bonus:** a rack of 12 flasks. Potions of the bonus color pour into the cauldron. The others change color every spin. The bonus runs until the rack is full. Each ingredient has its own modifier.
- **Controls:** tap anywhere to spin. Tapping during an animation skips it.
- **Cheats:** tap a jar to trigger its bonus on the next spin. Long-press the balance to open the debug panel.
- **URL params:** `?bonus=rose|herb|moth|feather|crystal|scale` (or pink/mint/…), `?seed=N`, `?turbo=1`.

Single self-contained `index.html`.
