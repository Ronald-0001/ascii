# Bot Expressions

To give the bot more personality, a collection of text-based facial expressions was created and used throughout the project.

Unlike traditional Discord bots that only returned plain text responses, this bot maintained a simple mood system and could display different expressions depending on context.

The expressions were used across multiple features including:

* Casino and gambling games
* Win/loss messages
* Error responses
* Cooldowns and command restrictions
* Administrative actions
* General chat interactions

The goal was to make the bot feel less like a command processor and more like a character users could interact with.

---

## Positive Expressions

### Happy :}

```text
^-^
```

### Smile :D

```text
^‿^
```

### Glad :)

```text
o‿o
```

### Excited XD

```text
≳‿≲
```

### Blessed X)

```text
≲‿≳
```

---

## Neutral Expressions

### Wink ;)

```text
o‿-
```

### Shocked oo

```text
◯_◯
```

---

## Negative Expressions

### Annoyed --

```text
-_-
```

### Frown :(

```text
o︵o
```

### Mad >:

```text
≳︵≲
```

### Sad X(

```text
≲︵≳
```

---

## Example Usage

### Successful Command

```text
^-^
Your daily reward has been claimed.
```

### Lucky Win

```text
≳‿≲
JACKPOT! You won 25,000 credits!
```

### Cooldown

```text
-_-
You must wait 30 seconds before using this command again.
```

### Error

```text
o︵o
Unable to find that player.
```

### Unexpected Event

```text
◯_◯
You rolled three sixes in a row?!
```

---

# Design Notes

These expressions were intentionally designed to:

* Fit inside Discord code blocks
* Remain readable in monospace fonts
* Use minimal characters
* Convey emotion instantly
* Work consistently across all bot features

Together with the card and dice ASCII assets, they formed a lightweight visual identity for the bot while remaining completely text-based.
