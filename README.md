# Dimension Invader

A turn-based strategic card battle game for Windows. Face off against an AI (or a second local player) using minions and spells, with one goal: destroy your opponent's three layers of defense before they destroy yours.

## Download & Play

1. Open the **[Releases](../../releases)** tab at the top of this repo (next to "Code").
2. Download `DimensionInvader-windows-vX.Y.zip` from the latest release.
3. Extract it anywhere.
4. Double-click `DimensionInvaderUnity.exe`.

> **Note**: Windows may show a "Windows protected your PC" SmartScreen warning because the .exe is not code-signed. Click **More info → Run anyway**. The game requires no installation, makes no registry changes, and never asks for admin rights.

### System Requirements

- Windows 10 / 11 (64-bit)
- ~150 MB free disk space
- GPU with DirectX 11 support (essentially any 2015+ machine)
- Recommended resolution: 1920×1080 or higher

## How to Play

### Goal
Destroy all three of your opponent's defense walls (Lv1 → Lv2 → Lv3) — or empty their deck.

### Card Types
- **Minion**: summoned onto the field (max 3 slots) to attack.
- **Spell**: one-shot effect (damage, healing, draw, etc.) that resolves immediately, then goes to the void.
- **Defense**: three walls. The outermost (Lv1) starts face-up; the next is revealed only after the current one is destroyed.

### Turn Phases
1. **Draw Phase** — Gain +1 max Cost (capped at 10), draw 1 card. (Player 1 skips draw on turn 1.)
2. **Main Phase** — Play minions and cast spells.
3. **Attack Phase** — Each non-rested minion can attack one enemy minion or, if there are no standing enemy minions, the active defense. *(No attacks allowed on turn 1.)*

### Tips
- Hand has **no upper limit** — feel free to bank cards until you can afford them.
- Click any **Void Zone** to inspect every card that's been discarded.
- Cast **Resurrect** and a picker opens so you can choose exactly which minion to bring back from your void.
- AI difficulty changes its decision-making:
  - **Easy** — plays cheap cards, attacks randomly.
  - **Intermediate** — balanced minion/spell mix.
  - **Hard** — greedy on high-cost spells, targets the weakest enemy minion.

## Modes

| Mode | Description |
|---|---|
| **vs AI** | Pick a difficulty + your deck + the AI's deck (a difficulty preset or any deck you built). |
| **Player vs Player** | Two players take turns on the same machine (local hot-seat). Online multiplayer is planned for a future release. |
| **Deck Builder** | Create and save custom decks — no card-count limit. |

## License & Disclosure

This game is built for personal learning and entertainment. The source code is **not publicly available**.

Built with Unity 6 (6000.4.8f1).

## Changelog

See the **Releases** tab for the full version history.
