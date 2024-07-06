Write your own cards and use a simple terminal-based flashcard system to memorize them.

```console
$ ./flushka card.txt
Q> What is the pythagorean theorem?
#-- press Enter to display answer --
A> a^2 + b^2 = c^2

was your answer correct (y/n)? n
```

Cards are placed inside boxes labeled from 1 to 4 by default.
Each box is assigned a probability of being selected.
Highest the label, lowest the chance.

For instance, for `n` boxes labeled from `i=1` to `n`, probability of box `i` = `(n-i+1) / (1+2+...+n)`

When your answer is correct, the current card is moved to the next box.

## Card syntax

```console
#maths,trigonometry  # comma separated themes
=Q=                  # question delimiter
What is 1 + 1?
=A=                  # answer delimiter
2
-----                # card delimiter when multiple cards in single file
```

TODO:

* theme selection
* avoid being asked twice
