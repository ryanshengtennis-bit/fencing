# Fencing Arena

A browser-based fencing game featuring Sabre, Foil, and Épée, with realistic weapon rules and Easy, Medium, and Hard opponents.

Bouts are first to 15 touches with a nine-minute clock.

## Play

[Open Fencing Arena](https://en-garde-fencing-arena.echristina-wang.chatgpt.site)

## Controls

- `A` / `D`: retreat and advance
- `J`: attack; one deliberate double-tap converts it to a lunge (extra taps are ignored until recovery)
- `K`: parry
- `L`: use the weapon's special move once the 24-second charge is full
- `Enter`: start the bout

Special moves: Sabre Mask Hit (2/5 chance), Foil Feint–Disengage (3/5 chance), and Épée Flèche (3/5 chance).

Each special begins with a half-second action freeze, then plays its own weapon-specific animation.

The game is a self-contained static website in `dist/index.html`.
