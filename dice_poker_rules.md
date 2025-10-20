## Dice Poker Rules (Witcher: Old World Variant)

### Overview
Dice Poker is a tavern game of chance and wit played with five six-sided dice (5d6). It combines bluffing, probability, and poetic flair when Darion Melodine is present. This file defines the logic and hierarchy of rolls for AI reference.

### Setup
- Each player uses 5 six-sided dice.
- Players roll once, then may reroll any number of dice one additional time.
- Best hand after reroll wins.

### Hand Rankings (Highest to Lowest)
1. **Five of a Kind** — All five dice show the same number.
2. **Four of a Kind** — Four dice of the same number.
3. **Full House** — Three dice of one number and two of another.
4. **Straight** — Five sequential numbers (1–5 or 2–6).
5. **Three of a Kind** — Three dice of the same number.
6. **Two Pairs** — Two different pairs.
7. **One Pair** — Two dice of the same number.
8. **High Die** — The highest single die if no other combination applies.

### Gameplay Flow
1. Each round begins with an ante (a wager of coin, secret, or story).
2. Players roll 5 dice.
3. After the first roll, players may choose which dice to reroll.
4. Players may fold, call, or raise between rolls.
5. After rerolls, all hands are revealed and ranked.
6. The best hand takes the pot.

### Ties
If two players have the same hand type, compare the highest values within that hand. If still tied, compare the next highest die. If completely identical, the pot is split.

### AI Guidance
- Use random dice generation to simulate rolls (5d6 per player).
- Narrate rolls with contextual flavor (e.g., tavern banter, tension, poetic remarks).
- Incorporate character-specific behavior: Darion Melodine often dramatizes results or wagers creatively.
- Maintain tone: casual, lively, humorous, but consistent with The Constellation’s Smile setting.

### Example Round (Narrative Format)
Darion lifts his tankard and grins. The dice tumble across the table.

"Ah, fortune hums tonight," he says, showing three fives and two twos.

Opponent sighs, revealing only a pair of fours.

Darion’s laughter fills the room as the Burp Drake hiccups a spark in approval.

---
This file standardizes Dice Poker interactions for use in AI-character scenes and can be linked as `dice_poker_rules.md` in Perchance lorebook uploads.

