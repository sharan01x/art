# corners

A pair of interactive grid pieces built in a single HTML file each. No frameworks, no build step — just geometry, chance, and the cursor.

The intention is to use digital space to create art that interacts with people. A little bit of play. Code can be expressive when used that way.

---

## corners

🔗 [Open `corners`](https://github.com/sharan01x/art/tree/main/corners)

A dark field of cream, rust, and shadow squares that breathe under your cursor. Each cell is a binary die roll: sharp or soft, square or circle. Merged blocks create rhythm at different scales, like a musical phrase that repeats at octaves.

Hover and the grid rebalances. There's no goal, just the pleasure of touching a surface that responds.

---

## corners-ball

🔗 [Open `corners-ball`](https://github.com/sharan01x/art/tree/main/corners-ball)

The mischievous twin. Same grid, but now the red circles are the only things anchoring the world in its cream state. Chase them away — turn every shape into something not-quite-circular — and the whole page flips. Background goes ink-dark, shapes go cream.

It's a conditional identity: the piece only knows who it is while the red circles exist. You're not just poking cells; you're negotiating with the piece about what mood it should be in.

---

## How they work

Both pieces share a language: geometry, chance, and the body (the cursor, the hand). No UI, no explanation, no loading screen. Just a grid that notices you.

- **Grid**: Pixel-perfect square cells, computed from viewport size with explicit track sizing — no stretching, no `1fr` surprises.
- **Merged blocks**: Square clusters only (1×1, 2×2, 3×3). No rectangles.
- **Hover**: Re-rolls border-radius for a random set of corners — smooth `0.5s` transition.
- **corners-ball inversion**: If no red circles remain on screen, the entire palette inverts. Cream becomes ink; ink becomes cream.

---

Built by [Sharan](https://github.com/sharan01x) with a little help from Hound.
