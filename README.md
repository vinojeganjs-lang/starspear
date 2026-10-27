# Starspear

A 3D sci-fi action game that runs in the browser. Story by **Vinoth**.

**Play it:** https://vinojeganjs-lang.github.io/starspear/

Captain Arun flies the starship ARIA across the whole observable universe, 46.5 billion light-years end to end. He dodges satellites, asteroids and black holes, and falls through singularities into new worlds. Then the Krell shoot him down, and he fights on foot with a spear of starlight, all the way to the Krell Titan. At the edge of the universe he meets the friendly Lumen, and humans and aliens fly home to Earth together.

## Levels

1. Earth Orbit: satellites and debris
2. Asteroid Reach: rocks the size of mountains
3. Singularity Field: black holes that pull at the ship
4. Krell Frontier: alien drones attack
5. Krell Moon: on-foot battle in 3 waves
6. Citadel of the Krell: brutes and spitters
7. The Krell Titan: boss fight with a button-prompt finish
8. Lumen: the friendly aliens, then the trip home to Earth

## Controls

**In the ship:** arrows / WASD / mouse to steer · Space or click to fire · Shift to boost · on-screen arrows and Fire button on phones

**On foot:** WASD to move · J or click for an attack combo · K or right-click for a heavy slam · Space to dodge · F for Surya fury · E for a finisher

P pauses · M toggles sound

## Tech

One self-contained `index.html`. It uses three.js r128 loaded from a CDN, with bloom post-processing. Planets, nebulae, black holes and sound are all generated in code, so there are no asset files.
