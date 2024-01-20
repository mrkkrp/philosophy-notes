# How to argue: logic

* Logic is the discipline that sorts out good arguments from bad arguments.
* Aristotle is considered to be its founder.
* Plato (following Protagoras) made important distinctions between parts of
  speech, distinctions that form part of the basis on which logic is built.
  * ‘Walks runs’ is not a sentence, nor is ‘Lion stag’.
  * The simplest kind of sentence is something like ‘Theaeteus flies’ and
    only something with this kind of structure can be true or false.

## Aristotle's syllogistic

A *syllogism* is a discourse in which from certain things laid down
something different follows out of necessity.

For example:

```
              Every Greek is human.
              Every human is mortal.
Therefore,    Every Greek is mortal.
```

The example syllogism above contains 3 sentences in the indicative mood and
each such sentence is called by Aristotle a *proposition*. The third
proposition in the example—the one preceded by ‘therefore’—is called by
Aristotle the *conclusion* of the syllogism. The other two propositions we
may call *premises*, though Aristotle does not have a consistent technical
term to differentiate them.

* Propositions that begin with *every* are called by Aristotle *universal*,
  more precisely *universal affirmative*, whereas there are also *universal
  negative* propositions, e.g. ‘No Greeks are horses’.
* Contrasted with universal propositions there are *particular*
  propositions, e.g. ‘Some Greeks are bearded’.
* In propositions of all these kinds something is *predicated* of something
  else, e.g. mortal is predicated of human, and horse of Greek in another.
* The presence or absence of a negative sign determine whether these
  predications are affirmations or negations respectively.
* The items that enter into predications in propositions are called *terms*.
  It is a feature of terms, as conceived by Aristotle, that they can either
  figure as predicates themselves or have other terms predicated of them.
  Thus, in our example, human is predicated of something in the first
  sentence and has something predicated of it in the second.
* The term that is the predicate of the conclusion is the *major* term
  (‘mortal’ in the example).
* The term of which the major is predicated in the conclusion is the *minor*
  term (‘Greek’ in the example).
* The term that appears in each of the premises is the *middle* term
  (‘human’ in the example).

Aristotle introduces the practice of using schematic letters to bring out
patterns of argument:

> If A belongs to every B, and B belongs to every C, A belongs to every C.

Aristotle sets out to consider inference for every case (figure) depending
on the position of the middle term (S = minor term, M = middle term, P =
major term):

```
              (1)    (2)    (3)
              S-M    M-S    S-M
              M-P    M-P    P-M
Therefore,    S-P    S-P    S-P
```

A. was mainly interested in syllogisms of the first figure, which he
regarded as alone being ‘perfect’, by which he probably meant that they had
an intuitive validity that was lacking to syllogisms in other figures.

Predication occurs in all propositions, but it comes in different forms in
the 4 different kinds of proposition:

* universal affirmative
* universal negative
* particular affirmative
* particular negative

Thus the predication S-P can be either ‘All S is P’, ‘No S is P’, ‘Some S is
P’, or ‘Some S is not P’. Within each figure, therefore, we have many
possible patterns of inference. Triads of these different kinds were, in
later ages, called ‘moods’ of the syllogism. Aristotle sets himself the task
of determining which of the possible moods produces a valid inference. He
addresses it by trying out the various possible pairs of premises and asking
whether any conclusion can be drawn from them. If no conclusion can be
validly drawn from a pair of premises, he says that there is no syllogism.

For example, if B belongs to no C, and A belongs to some B, there cannot be
a syllogism. No valid argument has true premises and a false conclusion, but
of course there can be valid arguments from false premises to false
conclusions, and invalid arguments for true conclusions.

There are 3 rules that apply to syllogisms in all figures:

1. At least one premise must be universal.
2. At least one premise must be affirmative.
3. If either premise is negative, the conclusion must be negative.

These rules are of universal application, but they take more specific form
in relation to particular figures. The rules peculiar to the first figure
are:

4. The major premise (the one containing the major term) must be universal.
5. The minor premise (the one containing the minor term) must be
   affirmative.

If we apply these rules we find that there are 4 and only 4 valid moods of
syllogism in the first figure:

```
Every S is M     Every S is M     Some S is M      Some S is M
Every M is P     No M is P        Every M is P     Every M is not P
Every S is P     No S is P        Some S is P      Some S is not P
```

Syllogisms in other figures can be converted to figure 1 by a process A.
calls ‘conversion’.

Syllogistic is only a fragment of logic. It deals only with inferences that
depends on words like ‘all’ or ‘some’, which classify the premises and
conclusions of syllogisms, not with inferences that depend on words like
‘if’ and ‘then’, which instead of attaching to nouns, link whole sentences.
These were formalized later in antiquity. Aristotle's syllogistic also could
not cope with inferences in which words like ‘all’, ‘every’, ‘some’ occurred
not in subject place but somewhere in the grammatical predicate, e.g. ‘every
boy loves some girl’ or ‘nobody can avoid every mistake’. It took more than
12 centuries before such inferences were satisfactorily formalized.

## Aristotle's de interpretatione

The *de Interpretatione* is principally interested like the *Prior
Analytics*, in general propositions beginning with ‘every’, ‘no’, or ‘some’.
Its main concern is not to link them to each other in syllogisms, but to
explore the relations of compatibility and incompatibility between them.

* Two statements that cannot be both true together are *contraries*. They
  can, however, be both false. (‘Every man is white’ and ‘no man is white’.)
* Two statements that cannot both be true and both be false together are
  *contradictory*. (‘Every man is white’ and ‘some man is not white’.)
* Universal affirmative is contradictory to the corresponding particular
  negative; a universal negative is contradictory to a particular
  affirmative.
* Two corresponding particular affirmatives are neither contrary nor
  contradictory to each other: ‘some men is white’ and ‘some man is not
  white’ can be, and in fact are, both true together. The propositions
  cannot, however, both be false together. Later followers called this the
  relationship of *subcontrariety*.

```
Universal affirmative                           Universal negative
‘Every man is white’       <-- contrary -->     ‘No man is white’
             \                                       /
              \                                     /
               X            Contradictory          X
              /                                     \
             /                                       \
Particular affirmative                          Particular negative
‘Some man is white’        <-- subcontrary -->  ‘Some man is not white’
```

## Aristotle's categories

A. lists 10 things that can appear in the predicate of a sentence:
substance, quantity, quality, relation, place, time, posture, vesture,
activity, passivity. A. makes a classification of extra-linguistic entities,
things specified as opposed to signs that specify them.

*First substance*—strictly so called, primarily and *par excellence*—is that
which is neither said of a subject nor is in a subject, e.g. such-and-such a
man, such-and-such a horse.

*Second substances* are the species and genera to which the primary
substances belong. Thus, such-and-such a man belongs in the species human,
and the genus of this species is animal; so both human and animal are called
second substances.
