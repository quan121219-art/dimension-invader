# Dimension Invader

A turn-based strategic card battle game for Windows. Destroy your opponent's three layers of defense (Lv1 → Lv2 → Lv3) before they destroy yours, using minions and spells with a growing mana economy.

> **Status: pre-alpha test build.** The current card set is generic test data (Slime / Goblin / Dragon, etc.) used to validate mechanics. Final card content and art will come once the core systems are stable.

## Download & Play

1. Open the **[Releases](../../releases)** tab at the top of this repo.
2. Download `DimensionInvader-windows-vX.Y.zip` from the latest release.
3. Extract anywhere.
4. Double-click `DimensionInvaderUnity.exe`.

> **Note**: Windows SmartScreen may warn that the .exe isn't signed. Click **More info → Run anyway**. The game requires no installation, makes no registry changes, and never asks for admin rights.

### System Requirements

- Windows 10 / 11 (64-bit)
- ~150 MB free disk space
- GPU with DirectX 11 support
- Recommended resolution: 1920×1080 or higher

## How to Play

### Goal
Destroy all three of your opponent's defense walls — or empty their deck.

### Card Types
- **Minion** — summoned onto the field (up to **5 slots**) to attack.
- **Spell** — one-shot effect (damage, heal, draw, AOE, …) that resolves immediately, then goes to the void.
- **Field** — a long-lasting card placed in its own zone (1 per player); has a passive/per-turn effect.

### Turn Phases
1. **Draw Phase** — Gain +1 max Cost (cap 10), draw 1 card. Player 1 skips draw on turn 1.
2. **Main Phase** — Play minions, cast spells, set field cards.
3. **Attack Phase** — Each non-rested minion may attack one enemy minion, or, if no standing enemy minions, the active defense. *(No attacks on turn 1.)*

### Field rule (5 slots)
- Field has 5 minion slots.
- If your field is full and you want to summon another minion, you'll be prompted to **discard 1 of your own minions** to make room.

### Hand & deck rules
- Hand has **no upper size limit** — bank cards until you can afford them.
- Deck builder caps each card at **max 4 copies** and deck size at **60 cards**.
- Cast a spell with a discard cost (e.g., **Mind Tap**) → a picker opens so you choose which card to discard.
- Cast a "look-top-N" effect (e.g., **Scry**) → a picker shows the revealed cards and lets you pick one, or **Take none** (all go to bottom of deck).
- Cast **Revive** → a picker opens showing all minions in your void; pick one to summon.
- Click any **Void Zone** to inspect what's been discarded.

## Modes

| Mode | Description |
|---|---|
| **vs AI** | Pick difficulty (Easy / Intermediate / Hard) + your deck + the AI's deck (a difficulty preset or any deck you built). |
| **Player vs Player** | Two players take turns on the same machine (local hot-seat). Online multiplayer is planned for a future release. |
| **Deck Builder** | Create and save custom decks (max 60 cards, max 4 copies per card). |

## What's not in this build yet

The following mechanics are designed and queued; they're not yet wired into gameplay:

- **Block** — cards tagged with Block (Shield, Counter Spell, Decoy, Sentinel) currently show their effect text but don't trigger reactively yet.
- **Field card passive effects** — The Ceremony / Healing Spring / Mana Surge Field sit in the field zone correctly but their per-turn effects aren't applied.
- **Attack-target arrow + block dialog** — coming with the block mechanic.

## License & Disclosure

Personal learning / entertainment project. Source code is **not publicly available**.

Built with Unity 6 (6000.4.8f1).

## Changelog

See the **Releases** tab. Each release describes new mechanics shipped in that build.
