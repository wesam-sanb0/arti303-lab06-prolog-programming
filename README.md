# ARTI 303 — Lab Assignment 06
## Prolog Programming

**Course:** ARTI 303 — Programming for AI
**Lab:** 06

### Files
| File | Description |
|------|-------------|
| `cars.pl` | Cars/trucks suggestion system with colour filter (Task 1) |
| `games.pl` | Interactive game-selection menu (Task 2) |
| `queries.txt` | Test queries and Prolog answers |

### Task 1 — Colour Matters
Added a new rule `can_buy/2` that takes a budget and a colour and suggests only vehicles matching that colour. Original `can_buy/1` was kept working.

### Task 2 — Game Selection Menu
Extended `games.pl` with:
- One more running game: **Baseball** (option 4)
- One more non-running game: **Chess** (option 3)

### How to Run
```prolog
?- consult('cars.pl').
?- can_buy(100000, red).

?- consult('games.pl').
?- menu.
