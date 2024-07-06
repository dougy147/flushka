Write your own cards and use a simple terminal-based flashcard system to memorize them.

```console
$ ./flushka card.txt
Q> What is the pytagorean theorem?
#-- press Enter to display answer --
A> a^2 + b^2 = c^2

was your answer correct (y/n)? n
```

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

* box system for classification and spaced learning
* small database (cards will need identifiers)
* shuffling/theme selection
