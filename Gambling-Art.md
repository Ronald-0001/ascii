# Discord Bot ASCII Collection

A small collection of ASCII interfaces and game assets used in an old Discord bot project.

The bot included several casino-style mini-games such as:

* Blackjack
* Dice Games
* Gambling / Betting Systems

The goal was to create game interfaces that looked visually appealing inside Discord code blocks while remaining fully text-based.

---

# Dice Board Interface

Used as the primary display for dice-based games.

Features:

* Player information section
* Total score display
* Multiple dice rendered in a fixed-size layout
* Designed to fit Discord monospace code blocks

```text
┌───────────────────────────┐
│ • Person                  │
│ • Total: XX               │
├───────────────────────────┤
│╭───────╮╭───────╮╭───────╮│
││       ││ #     ││ #     ││
├│   #   ││       ││   #   │┤
││       ││     # ││     # ││
│╰───────╯╰───────╯╰───────╯│
│╭───────╮╭───────╮╭───────╮│
││ #   # ││ #   # ││ #   # ││
├│       ││   #   ││ #   # │┤
││ #   # ││ #   # ││ #   # ││
│╰───────╯╰───────╯╰───────╯│
└───────────────────────────┘
```

---

# Playing Cards (CardsV2)

The second iteration of the card system.

## Design Goals

The original card designs were resized and redesigned to match the dimensions of the dice displays.

This made:

* Blackjack interfaces more consistent
* Dice games and card games visually compatible
* Layout calculations easier
* Overall UI more uniform

---

## Card Template

Base template used for generating all card faces.

```text
╭───────╮
│##    ?│
│  ???  │
│  ???  │
│?    ##│
╰───────╯
```

---

## Hearts

```text
╭───────╮
│##    ♥│
│ ( v ) │
│  \ /  │
│♥    ##│
╰───────╯
```

---

## Diamonds

```text
╭───────╮
│##    ♦│
│  / \  │
│  \ /  │
│♦    ##│
╰───────╯
```

---

## Clubs

```text
╭───────╮
│##    ♣│
│  ( )  │
│ (_+_) │
│♣    ##│
╰───────╯
```

---

## Spades

```text
╭───────╮
│##    ♠│
│  / \  │
│ (_+_) │
│♠    ##│
╰───────╯
```

---

## Card Back

Used whenever a card was hidden from the player.

```text
╭───────╮
│ /\ /\ │
│ \/ \/ │
│ /\ /\ │
│ \/ \/ │
╰───────╯
```

---

# Notes

These assets were originally created for a Discord bot where all game interfaces had to be rendered using plain text inside code blocks.

Despite the limitations, ASCII rendering allowed for surprisingly readable and interactive game UIs without requiring images, embeds, or external assets.
