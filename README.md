Some kind of flashcards parser.

```console
$ cat card.txt
#maths,trigonometry  # comma-separated themes
==Q
What is the pythagorean theorem?
==A
a^2 + b^2 = c^2

$ ./flushka card.txt
What is the pytagorean theorem?
a^2 + b^2 = c^2
```

TODO/IDEAS:

* show question => press key => show answer
* use feedback: correct answer = space card in time
* small database