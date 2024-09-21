# Design doc

## Summary

Your objective is to make the best project, you’ll need to assemble a team, leverage the ecosystem crates and use techniques to your advantage to get a balanced outcome and take the final win!

## Key elements

### The role of the game

This game aims to offer a fun ice-breaker game for developer (rust / bevy) events, leveraging developer-themed and self-explanatory cards to have a quick on-boarding for new players, but still offer some depth to have a sense of "skill-based" game through deck building and decision making.
Recommended player age is 10+, as it can be heavy in simultaneous rules.

### Inspirations

- Inspired by [cabo](https://en.wikipedia.org/wiki/Cabo_(game)): multiple rounds

An opportunity to add strategy elements, such as deck building or score counting
Hidden cards, card swapping, to work on memory.

More flexibility, with the possibility of players joining during the full game.

- Inspired by [marvel snap](https://en.wikipedia.org/wiki/Marvel_Snap): 3 categories, from which points are counted: player with most points in most categories wins.

Decision making between balanced play or "abandoning" a category, bluffing

- Inspired by [witcher card game](https://en.wikipedia.org/wiki/Gwent:_The_Witcher_Card_Game): strategy between games, "lose the battle may be good"

Card pool changes slightly between games, where final shown cards (main vector of scoring) are removed from the pool.

This results in most cases in disadvantageing the winner, à la [Mario Kart](https://en.wikipedia.org/wiki/Mario_Kart), offering more balanced games.

- Inspired by [slay the spire](https://en.wikipedia.org/wiki/Slay_the_Spire) (and others…): discard pile

Can be advantageous or not depending on deck/play style
Inspired by [hearthstone](https://en.wikipedia.org/wiki/Hearthstone) (and others…): side effects
Effect on each turn
Improve cards (cards should be protected to be able to write on them with a marker)

## Categories

Each category is both a different angle of conversation, a color (RGB is dear to developers) and (hopefully) a playstyle.

### Techniques

Mostly Bevy and tech jargon, while some can lead to interesting discussion, this category is an opportunity to go wild in game design and add some "attack" cards without risking controversial association with their underlying identity.

Its color is red for a more aggressive take.

### Tools

Or "crates", these are excellent conversation starting points, as all players might not be familiar with these. Gameplay-wise, these tend to add long-term advantage.

Its color is green, for its "ecosystem" reference.

### Members

These are prominent individuals in the bevy ecosystem scene, great to foster networking and getting to know people. These tend to improve other cards or game knowledge.

Its color is blue, because it's often associated with trust and team.

## How to play

See [HOW_TO_PLAY](HOW_TO_PLAY.md).

## Development

See [README.md](/README.md).

## Cards

See [editions](/editions/).

## Future

- More cards (each edition should come with a flagship card.)
- First edition flagship card is "open source"
- Special rare cards to hand out at events or to real life members
- Get in touch with conferences organizers to distribute packs of cards / organize tournaments.
- Offer a way to purchase the cards (work with local printers, or drivethrucards.com or launchtabletop.com)
- Extra category (events, company/sponsors…)
- Game variants
  - Personas: starting with more cards, getting more points if winning a category…
  - Team up with another player
  - Draft / "bring your deck"
  - Tournament
  - King of the hill
  - Long play
