# Rules For Young Programmers

Following Robert Schumann's [Rules For Young Musicians](https://jmm.people.si.umich.edu/blog/schumann%27s_rules_for_young_musicians.pdf) in merit and style, here's a set of maxims and aphorisms for aspiring and practicing programmers alike, in no particular order. As stated in the foreword to the original article:

> Once you have read them, you will find yourself reading them again and again, finding the wisdom they contain more absorbing and rewarding each time.

## I

The most important thing is to cultivate the sense of Seeing. Take pains early to embrace understanding while sightreading, as reading code makes the most of the programmer's work.

## II

Each code editor has syntax highlighting – use it to spot functions, control statements and loops before you see them.

## III

Develop a strict discipline of writing your code in a consistent manner. For a seasoned programmer, every indentation or empty line matters and makes sightreading easier.

## IV

Lehman's classification of [S-programs, P-programs and E-programs](https://users.ece.utexas.edu/~perry/education/SE-Intro/lehman.pdf) is a very useful concept. They are highly correlated with [Clear, Complicated and Complex](https://cynefin.io/wiki/Cynefin_Domains) domains in the Cynefin framework.

## V

Strive to write S-Programs well and beautifully; it is necessary for a practicioner to be able to write rock solid, fast and small programs, rather than a mediocre large system.

## VI

Algorithms are good examples of S-Programs. If you're looking for a next exercise, try to implement and then understand the inner workings of an algorithm in the language of your choosing.

## VII

In real life, scaffolding doesn't stay with the building when it's completed. Don't fool yourself, it's a wrong metaphor. A better one would be of a skeleton.

## VIII

A young programmer practices program designs that can be understood by other programmers; you'll keep the rest of your career practicing designs that can be understood by anyone.

## IX

If you believe there's only one way to accomplish a certain task, only one framework, only one language or only one programming paradigm, then it's the same as believing there's only one way to structure a sentence with given meaning in the English language.

## X

Avoid mixing up declarative and imperative code. It's like answering the question "Where are you going for holidays?" with "Well, for starters I'm going to check the oil level in my car engine".

## XI

Don't confuse divergent meanings of the `=` symbol across paradigms. A mathematician might say this determines equality between two sides. A functional programmer might say it's about binding a name to a value. An imperative programmer will say that's assignment operator that mutates the program state.

## XII

Acquaint yourself early with the idea that any program you wrote will be studied by others and it's your responsibility to teach them to orient themselves in your code. Each program constitutes an act of teaching.

## XIII

Never write tests for how the code was written. Write tests for how it's going to be used.

## XIV

A good metaphor for the reactive programming paradigm is electricity. You are not interested in the principles that make the current flow inside the wire, you expect to just connect the wires to make things work.

## XV

Acquire early a skill to compare and concatenate paths by eye. Many programmers spent hours just to find out their program is not pointing to the right file, directory or a network address.

## XVI

Learn to seek for the precise terminology and use it deliberately. For example, a procedure and a function may seem similar, but there's a consequence in the meaning and application of each one.

## XVII

Develop understanding of [The principal programming paradigms](https://www.info.ucl.ac.be/~pvr/paradigmsDIAGRAMeng108.pdf) from the book "Concepts, Techniques, and Models of Computer Programming". This will make you appreciate the paradigm you are working with even more and draw deeper connections between the worlds of declarative and imperative programming.

## XVIII

The prevalence of classes in languages such as Java spoils the mind and depletes the diversity found in other languages and paradigms. Break out of that spiral by noticing that OOP is built on the foundation of only three elements: a procedure, a closure and a state cell, and thus, there is no mysticism in using classes.

## XIX

Learn to use divide and conquer strategies when debugging the code. If you know there's a bug somewhere between line A and B in your code, develop hypotheses which will introduce point C inbetween A and B, which can be then validated. That way you'll be able to discover whether the bug is in (A, C) or (C, B).

## XX

Develop understanding of multiple languages and paradigms in addition to knowing a few of them expertly.

## XXI

Many face dread when taking over someone's program. Do not let it overcome you. The moment you reach a conclusion that some code should not be changed no matter what, you become slave to the mistakes of the past.

## XXII

It's a programmer's responsibility to introduce quality to the code. If you don't devote a bit of time for that, nobody does.

## XXIII

One might believe that constraints only impose restrictions on the thing being constrained. But an outdoor concrete bench, while still preventing you going straight through it, enables sitting as a new possible pattern of behaviour. Similarily, [constraints](https://cynefin.io/wiki/Constraints) shaping the reality of your program not necessarily just reduce the set of options at hand.

## XXIV

Learn to appreciate functions, especially the pure ones. They are often simpler to concpetualize, because they drop order to favour relations and can be considered in separation to the rest of the program.

## XXV

Within the Cynefin framework, the act of writing a program lies in the [Complicated domain](https://cynefin.io/wiki/Cynefin_Domains), as the outcome (the program being complete or not) can be easily predicted with a high degree of accuracy by an expert. The consequences of the aforementioned is that the act of program writing can both be mastered by one and replicated by many.

## Contributors

- Michał Moroz <michal@makimo.pl>
- Mateusz Papiernik <mateusz@makimo.pl>