# NEXT Royale

The party game of NEXT: Valletta. Sixteen rounds across Valletta, in your browser.

**Play:** https://pierreobv.github.io/next-royale/

- `index.html` is the page: Play now, playing together, playing alone, the rounds and the FAQ.
- `play/` is the game (Godot 4.7, WebGL 2). The engine and the game data are gzipped and cut into parts of under 9 MB (`index.wasm.gz.*`, `index.pck.gz.*`); the page puts them back together in the browser.
- Online games go through the NEXT & Seek relay on Render, listed under their own tag (`royale`). A link with `?room=KQMT` opens the game ready to join game KQMT.
- `version.json` tells the Mac and Windows apps when a newer version is out.

Laptop or desktop with a keyboard, best in Chrome or Edge.
