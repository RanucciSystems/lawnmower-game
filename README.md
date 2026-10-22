# Mow the Field

A simple bird's-eye-view browser game: drive a ride-on lawnmower around a large,
overgrown farm field and cut all the grass. The HUD and minimap track how much of
the field you have mowed.

## Play

Open `index.html` in any modern browser. No build step or server required.

## Controls

| Key | Action |
| --- | --- |
| `W` / `↑` | Drive forward |
| `S` / `↓` | Reverse |
| `A` / `←`, `D` / `→` | Steer |
| `Shift` | Boost |
| `R` | Restart with a freshly generated field |
| `Esc` or ⚙ | Open settings |

Mow 100% of the field to finish. Your time and bump count are shown when you clear it.

## Obstacles

Each field is randomly generated with a pond, trees, rocks and hay bales. Running
into one at speed counts as a bump and knocks you back, so steer around them.
Patches under obstacles don't need cutting.

## Mower health

Every bump damages the mower, and harder hits do more damage. The health bar in
the HUD drops from green to yellow to red, the mower picks up dents and starts
belching black smoke, and at zero it breaks down. That's game over: a screen
shows how much you cleared and a Restart button starts a fresh field.

## Mowing stripes

Cut grass is shaded by the direction you were driving when you cut it, so mowing
back and forth in rows produces the alternating light and dark stripes of a
real field.

## Settings

The gear icon (or `Esc`) opens a panel where you can adjust steering sensitivity,
top speed, acceleration, and whether steering inverts while reversing. Settings
are saved in your browser.
