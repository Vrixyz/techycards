# Techy cards

Techy cards is a card game for rustlang, bevy and tech enthusiasts: the perfect opportunity to kill time in between tech conferences!

![art/cover.png]

With quick games for less than 5 minutes, let's determine who pays the latte for the afterparty.

The goal of the game is to assemble technologist members, tools and techniques to score more points than your opponents.

The rules are simple:

- Draw a card.
- Play a card.

1 card at a time, turns are quick and easy, but will you keep track of the points until the 8th round ?

Get your tech ecosystem knowledge freshened up with these ice-breaker cards, get the best line up!

## Detailed rules

See [HOW_TO_PLAY.md](docs/HOW_TO_PLAY.md)

## Editions

Cards are grouped in "editions" of 60-120 cards, these editions are meant to:

- Be printed together, and played together.
- Have a theme, and/or a "star feature" with a unique twist to it.
- A "release" plan.

Current list of editions:

- 2024/09: Paris Rust Meetup #70
  - Themed edition on rust conferences, where most of members are "attendees".
- 2024/10: Launch
  - Star card: "open source", which both sides show the description, a reference to this game being open sourced, focused on bevy community.
- Next edition(s)
  - WIP

## Contributing

Techy cards is open source. That means you can print your cards and distribute them for the conference you're organizing! Contact me if you do <3

### Development process

[Affinity Publisher](https://affinity.serif.com/fr/publisher/) is used to create the card printables.

To create card files:

- Each edition lives within `editions/`, where you'll find some details about the edition, the sources, and affinity files used to generate the cards.
- Templates are in `/templates`
- Create cards using [data merge](https://affinity.help/publisher2/English.lproj/index.html?page=pages/Advanced/dataMerge.html&title=Data%20merge). The process is not fully automated as we need to edit the output `.afpub` to fix overflowing text, or adapt special cards (special back, emojis, text color...)
- All cards should ideally have some free space to write modifications on them.

To print:

- Print backs and fronts independently, here is current setup:
![print details](contrib_docs/print_details.png)
- Ideally color their back in black to limit the see-through
- Glue them together
- Laminate them, so players can use temporary markers on them.

Other techniques involve printing both back and front on the same paper, then folding it on itself. See https://youtu.be/WyMVRJu5yQ4?t=1186 for ideas.