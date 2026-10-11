# Ping Pong Scoreboard

A live, two-player table tennis scoreboard you can play online with a friend — no accounts, no app installs.

**How it works**

1. One of you opens the page and taps **Host a new match**. You'll get a 5-character room code.
2. Share that code (or the copy-link button) with your friend.
3. They open the page, tap **Join a match**, and enter the code.
4. Once connected, the host fills in both names and the match format, then taps **Start match**.
5. Either of you can tap either player's side to add a point — it syncs instantly to the other screen.

The board enforces real ITTF table tennis rules: games to 11, win by 2, serve switches every 2 points (every point once it's 10-10), and a reminder to switch ends when the deciding game reaches 5.

Connections are peer-to-peer (via [PeerJS](https://peerjs.com/)) — no backend server, no sign-up, nothing stored outside your two browsers. Close both tabs and the match is gone, so finish your game before closing the page.

Live at: https://jreebuman.github.io/ping-pong-scoreboard/
