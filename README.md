# Ninja Hattori



Ninja Hattori: Infiltrate the Tower is a fast-paced retro stealth game where you climb a massive 30-floor skyscraper like a true ninja! Leap across walls, duck through shadows, and dodge laser-sharp security cameras and patrol guards. One wrong move trips the alarm and sends you straight back down, so keep your cool, time your jumps, and sneak all the way to the roof!

---

## current status

Session 01 is done. The canvas is centered, the game loop runs with
delta capped so laggy frames don't break physics, and keyboard input
is wired up. No gameplay yet — just the engine scaffold.

---

## controls

- move: `A` / `D` or arrow keys (also `Q` for AZERTY)
- jump: `Space` or `W` / `Up`
- gamepad: left stick or D-pad works

---

## what works

- canvas centers itself and resizes to fit the window
- game loop runs every frame, delta capped at 50ms so tab switches
  and laggy frames don't break physics
- key presses are tracked and cleared when the window loses focus
- jump, left, right mapped to both keyboard and gamepad

---

## what is not done yet

- no player character
- no enemies or guards
- no levels
- no audio
- no menus

---


