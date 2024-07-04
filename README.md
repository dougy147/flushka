Write your own cards and use a simple terminal-based flashcard system to memorize them.

```console
$ cat card.txt
#maths,trigonometry
=Q=
What is the pythagorean theorem?
=A=
a^2 + b^2 = c^2
-----

$ ./flushka card.txt
Q> What is the pytagorean theorem?
#-- press Enter to display answer --
A> a^2 + b^2 = c^2

was your answer correct (y/n)? n
```

TODO:

* box system for classification and spaced learning
* small database (cards will need identifiers)
* shuffling/theme selection
