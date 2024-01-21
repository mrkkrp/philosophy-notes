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

## Aristotle on time and modality

A. nowhere puts forward a theory according to which tensed sentences are
incompletely explicit expressions of timeless propositions. There is, for
A., nothing in the nature of the proposition as such that prevents it from
changing its truth-value. Logicians in later ages distinguished between
propositions that can, and propositions that cannot, change their
truth-value, calling the former *contingent* and the latter *necessary*
propositions. The roots of this distinction are to be found in A., but he
speaks by preference of predicates, or properties, necessarily or
contingently belonging to their subjects. He discusses propositions such as
‘A must be B’ and ‘A can be not B’: propositions later called by logicians
‘modal propositions’.

In the *de interpretatione* A. introduces the topic of modal propositions by
saying that whereas ‘A is not B’ is the negation of ‘A is B’, ‘A can be not
B’ is not the negation of ‘A can be B’; its negation is ‘A cannot be B’. In
the straightforward categorical statement, whether we take the ‘not’ as
going with the ‘is’ or the ‘B’ makes no practical difference. Is the modal
statement, whether we take the ‘not’ as going with the ‘can’ or the ‘B’
makes a great difference.

```
It is necessary for A to be B               It is necessary for A not to be B
It is impossible for A not to be B  <-----> It is impossible for A to be B
             \                                            /
              \                                          /
               X                                        X
              /                                          \
             /                                            \
It is possible for A to be B                It is possible for A to be B
It is not necessary for A not to be B       It is not necessary for A to be B
```

In *Prior Analytics* A. explores the possibility of constructing syllogisms
out of modal propositions, but it is universally considered a failure. The
reason for the lack of success is A.'s indecision about the best way to
analyze modal propositions.

If modal words modify predicates, there is no need for a special theory of
*modal* syllogisms. For these are only ordinary assertoric syllogisms of
which the premises have peculiar predicates. On the other hand, if modal
words modify the whole statements to which they are attached, there is no
need for a special modal *syllogistic*, since the rules determining the
logial relations between modal statements are independent of the character
of the propositions governed by the modal words. The necessary basis for a
modal logic is a logic of unanalyzed propositions such as was developed by
the Stoics.

## Stoic logic

For Diodorus Cronos a proposition is possible iff it either is or will be
true, is impossible iff it is false and will never be tru, and is necessary
if it is true and will never be false. ‘The Persian Empire has been
destroyed’ was untrue but possible when Socrates was alive; after
Alexander's victories it was true and necessary. For Diodorus, as for
Aristotle, a special necessity applies to the past.

It is a feature of D.'s definition of possibility that there are no
possibilities that are forever unrealized: whatever is possible is or will
be one day true. This appears to involve a form of fatalism: no one can ever
do anything other than what they in fact do.

The Master Argument:

1. Past truths are necessary.
2. Nautilus will not ever be seen.
3. It has always been the case that Nautilus will not ever be seen. (A
   plausible consequence of 2.)
4. It is necessary that Nautilus will not even be seen. (From 3 and 1.)
5. It is impossible that Nautilus will ever be seen. (Necessarily not =
   impossible that.)

Only what will happen can happen.

This argument is flawed by an ambiguity in the premise that past truths are
necessary. What is a past truth?

* If it means a true proposition in the past tense, then there is no
  guarantee that it is necessary.
* If it is a proposition that is made true by an event in the past, then
  past truths are indeed necessary; but a proposition such as 3 is not a
  past truth and hence does not entail 4.

Diodorus' pupil Philo defines the conditional. ‘If p, then q’, he said, was
false in the case in which *p* was true and *q* false and true in the 3
other cases.

On the other hand, there are passages suggesting that at least some Stoics
took a different view of the truth-conditions. Chrysippus is reported as
saying that in ‘If p then q’ the connective declared that *q followed from
p*. A conditional is true when the contradictory of its consequent conflicts
with its antecedent. For instance, ‘If it is day, it is light’ is true
because ‘It is not light’, the contradictory of the consequent, conflicts
with ‘It is day’. A conditional is false when the contradictory of its
consequent does not conflict with the antecedent, such as ‘If it is day,
Dion is walking’ because ‘Not: Dion is walking’ does not conflict with ‘It
is day’.

Stoics introduced a new term, *lekton*, literally *thing said*. The *lekton*
plays an important part in the Stoic treatment of the distinction between
signs and what they signify. The Stoics said that three items are linked
together, the signification, the signifier, and the topic. The signifier is
a sound, such as ‘Dion’, the signification is the matter that is portrayed
by it, the topic is the external object such as Dion himself. Of these three
items two, the sound and the topic are material, but one is intangible, the
matter signified, i.e. the *lekton*, which is what is true or false.

The *lekton* is what said by the sentence, namely that ‘Dion is walking’.
This is not a tangible entity like Dion himself, or the name ‘Dion’, or the
whole sentence ‘Dion is walking’. Whether the sentence is true or false
depends on whether the matter it portrays obtains or not, i.e. on whether
Dion is or is not walking. On this bases we can say that a *lekton* is the
content of a sentence in the indicative.

Stoics realized the importance of scope when they were treating negations.
‘It is day and it is light’ was not contradictory to ‘It is day and it is
not light’. The contradictory must be formed by attaching the negation sign
at the beginning so that it governs the whole proposition.

The criterion for the invalidity of an inference was analogous to the one
Chrysippus offered for the truth-value of a conditional. An inference was
valid if the contradictory of the conclusion conflicted with the conjunction
of the premises; if it did not conflict, then the inference was invalid. A
typical invalid inference was ‘If it is day, it is light. But it is day.
Therefore Dion is walking.’ Nowadays we are accustomed to distinguish valid
inferences and sound inferences. An inference may be valid but unsound if
one or more of its premises is untrue. The Stoics made a similar
distinction, but used the Greek word for ‘true’ to correspond to ‘sound’ and
‘false’ to correspond to ‘unsound’. An inference was unsound if either it
was invalid or it contained some falsity in its premises.

Inferences came in various forms, called ‘moods’:

(A) If 1 then 2; but 1; therefore 2.
(B) If 1 then 2; but not 2; therefore not 1.
(C) Not both 1 and 2; but 1; therefore not 2.
(D) Either 1 or 2; but 1; therefore not 2.
(E) Either 1 or 2; but not 2; therefore 1.

All valid inferences, Chrysippus believed, can be reduced to these forms.
