# JJ's Memory Match

A bright, friendly memory matching game made for JJ — a 7-year-old playing on a phone. Built with Kiro.

## What the game is

Flip over cards two at a time and find the matching pairs. The cards hide fun **gaming emoji** — game controllers, consoles, and arcade/retro gaming symbols like 🎮 🕹️ 👾 🎲 🏆 📺. The emoji are picked at random every game, so it's a little different each time. Try to find all the pairs in as few moves as you can!

## Levels

The game has **5 levels** that get a little bigger and trickier as you go. Each level fits neatly on a phone screen, with the cards shrinking just enough so a full board always fits with no scrolling.

| Level | Pairs | Cards | Grid |
|-------|-------|-------|------|
| 1     | 6     | 12    | 3 × 4 |
| 2     | 8     | 16    | 4 × 4 |
| 3     | 10    | 20    | 4 × 5 |
| 4     | 12    | 24    | 4 × 6 |
| 5     | 15    | 30    | 5 × 6 |

- **Level select screen.** After you tap **Play!**, you pick a level from a list that shows each level's number, how many pairs it has, and your **best (fewest) moves** for that level.
- **Locked and unlocked.** You start with **Level 1 unlocked** and the rest **locked** (🔒). **Finishing a level unlocks the next one.** Locked levels can't be started until you earn them.
- **Saved per player.** Which levels you've unlocked and your best moves for each level are saved under your name, so every player builds up their own progress.

## How to play

1. Type your name in the big friendly name box on the start screen, then tap **Play!**
   - Your name is remembered for next time, so you don't have to retype it.
2. Pick a level from the **level select** screen (locked levels unlock as you finish earlier ones). Tap **Back** to return to the start screen.
3. Tap a card to flip it over (it gives a happy little pop and squish).
4. Tap a second card.
   - **Match!** 🎉 The two cards stay face-up with a happy green glow and a cheerful sound.
   - **No match?** The cards flip back over after a moment — remember where they were!
5. Keep going until all the pairs in the level are found.
6. Watch the **Moves** counter at the top to see how many tries you've used. The **⬅ Levels** button takes you back to the level select screen any time.
7. When you find every pair, a celebration banner and a burst of confetti/stars show your final move count. From there you can tap **Next Level** (once it's unlocked), **Play Again** to reshuffle the same level, **Level Select** to pick another level, or **Leaderboard** to see the best scores.

## Leaderboard

The game keeps a **Leaderboard** of the top 10 games, **fewest moves first**. You can open it from the start screen or from the win banner. Each entry shows the player's name, their move count (the moves used to finish that level), and the date.

- **Saved on the device.** Every finished game is saved right on the phone or computer using the browser's storage, so the board stays even after you close and reopen the game. Different players on the same device each appear under their own name.
- **Online family leaderboard.** When there's an internet connection, the Leaderboard screen also shows a shared **family** board so everyone's best games can compete across devices. Finished scores are submitted quietly in the background.
- **Offline fallback.** No internet? No problem. If the family server can't be reached, the game instantly falls back to the scores saved on the device and keeps working perfectly. Gameplay is never blocked or interrupted by the network.
- **Clear board.** On the Leaderboard screen there's a small **Clear board** option (with a "are you sure?" confirm step) so the family can reset the device's saved scores.

## Sound

Happy sound effects play as you tap, match, and win — all made with the browser's built-in Web Audio (no sound files to download). There's a **🔊 / 🔇 sound toggle** in the top-right corner; sound is **on by default** and your choice is remembered.

## Look and feel

A gentle animated background of drifting gaming shapes and stars sets the arcade mood without distracting from play. Cards flip, bounce, and pop, matched pairs celebrate, buttons squish when pressed, and winning sets off a confetti/star burst.

## How to open it

Just open **`index.html`** in any web browser — double-click the file, or drag it into a browser window. On a phone, open the file in your mobile browser.

That's it. No installation and no setup needed — the whole game lives in a single file. It works **completely offline**; the only time it reaches the internet is to share scores on the optional family leaderboard, and it falls back gracefully to the device's saved scores whenever there's no connection.
