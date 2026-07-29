# Fourth Move Forgets

FIFO tic-tac-toe for GitHub Pages.

Rules:

- Each side can only keep 3 live marks on the board.
- On the 4th placement, that side's oldest mark disappears.
- New marks must use an empty square, including when the oldest mark is about to disappear.
- Three in a row with the remaining marks wins the round.

Features:

- 2-player mode
- Tactical easy AI and search-based hard AI
- Persistent scoreboard in `localStorage`
- Mobile-friendly layout
- Keyboard controls: `A S D`, `F G H`, `J K L`, and `Space`

Pushes to `master` deploy through `.github/workflows/pages.yml` to GitHub Pages.
