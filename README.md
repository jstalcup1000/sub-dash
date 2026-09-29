# Sub Dash

A small 2D endless-runner inspired by the Chrome dino game, except you're piloting a submarine through the ocean.

## How to play

Open `index.html` in a browser (no install or build step needed).

| Control | Action |
|---|---|
| Hold **Space** / **↑** / **W** / click | Blow ballast and rise |
| Release | Sink |
| **↓** / **S** | Dive faster |
| Phone: hold the **top half** of the screen | Rise |
| Phone: hold the **bottom half** of the screen | Dive |
| **E** or the **Use pearl** button | Spend a pearl for a 3-second shield |
| **1** / **2** / **3** or the buttons under the game | Easy / Normal / Hard |
| **P** | Pause |
| **M** | Mute |

Dodge rocks, icebergs, mines, jellyfish, and sharks (watch for the red **!**). The sub speeds up over time, and the ocean gets darker the deeper into the run you go. Your best score is saved in the browser, separately for each difficulty.

## Pearls

Glowing pearls sometimes float in the open water between obstacles. Swim through one to collect it (you can hold up to 3; they reset each run). Press **E** or tap **Use pearl** to spend one for 3 seconds of invincibility, like a star in Mario: mines, jellyfish, and sharks get smashed, and you pass straight through rocks and icebergs. The rainbow shield blinks just before it runs out, and it won't drop while you're still inside a rock.

## Difficulty

Difficulty sets the sub's top speed: Easy tops out at 52 knots, Normal at 72, Hard at 95. Easy also never reaches the tightest obstacle spacing. You can switch difficulty on the title or game-over screen, but not during a run.

## Project layout

Everything lives in a single file, `index.html`: HTML, CSS, and the game's JavaScript (drawn on an HTML canvas, with sound generated in code).
