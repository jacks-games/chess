# ♟️ Jackies Schach

### Real chess, with a coach who shows you what is safe. ⭐

# [▶ PLAY](https://jacks-games.github.io/chess/)

![Jackies Schach: a chess board with a pawn selected and two green dots showing where it can go](screenshot.png)

> 🇩🇪 This one speaks **German** — the others are in English.

## 🎮 How to play

### 1️⃣ &nbsp; Tap one of your pieces ♙
Only your own pieces light up.

### 2️⃣ &nbsp; Look at the dots
| | |
|---|---|
| 🟢 | Safe square — nobody can take you there |
| 🔴 | Careful! Something can take you there |
| 🟡 | The coach thinks this is a good move |

### 3️⃣ &nbsp; Tap where you want to go
Your piece moves. Then it is the other side's turn.

### ⭐ &nbsp; Collect XP
Good moves earn stars. Win games in a row and your **streak** 🔥 grows.

## 🧑‍🏫 The coach

Before you move, the coach shows up to three ideas with stars — ⭐ good, ⭐⭐ better, ⭐⭐⭐ best — and what the other side might do next. You can guess first, then look.

## ⚙️ You can change

| | |
|---|---|
| 💪 **Stärke** | how strong the opponent is |
| 💡 **Tipps** | coach ideas on or off |
| 🐢 **Gegnerzug** | how fast the other side moves |

## 🎯 What you get better at

- 🧠 &nbsp; Thinking one move ahead
- 👀 &nbsp; Spotting what is in danger
- ♟️ &nbsp; All the real rules — castling, en passant, promotion

## 🎈 More games for Jack

[📖 Words](https://github.com/jacks-games/words) · [🥅 Match](https://github.com/jacks-games/match) · [✏️ Letters](https://github.com/jacks-games/letters) · [🔢 Numbers](https://github.com/jacks-games/numbers) · [♟️ Chess](https://github.com/jacks-games/chess)

👉 &nbsp; All of them together: **[jackbenn.ing](https://jackbenn.ing)**

---

<details>
<summary><b>For grown-ups</b> — what it enforces</summary>

Full FIDE move legality: legal moves only, check, checkmate, stalemate, castling, en passant and promotion are all validated, and the engine self-tests its rule set on load (the *Regeltest* badge). Threefold repetition and the fifty-move rule can be claimed; fivefold repetition and the seventy-five-move rule end the game automatically. Over-the-board tournament rules — touch-move, clocks, an arbiter — are not part of it.

The danger highlighting is the teaching device: before committing, a child can see which destination squares are attacked. Coach suggestions are ranked and paired with the likely reply, so the habit being built is "what happens next", not "what looks nice".

One self-contained `index.html`, no build step, no dependencies, no accounts, no tracking. XP and streaks live in `localStorage`.

Source of truth for all of Jack's games is the [jackbenn.ing repo](https://github.com/google814/Jack); this repo is a copy so the game has its own page and link.

```bash
python3 -m http.server 8000
```
</details>
