# xle_a3

### The current fst file contains the combined grammars of lecture 8 (COMP, XCOMP) and lecture 9 (LDD).
### In the testsuite, I have provided 6 sentences: two for each phenomenon, whereby one parses correctly, while the other does not. These sentences are presented below:

COMP
* Toby thinks that Michael likes him - successful parse
* Toby thinks that Michael to like him - unsuccessful parse; given the verb 'think', the embedded phrase cannot have a non-finite verb.

XCOMP
* Jim persuaded Dwight to wait on the roof - successful parse
* Jim persuaded that Dwight wait on the roof - unsuccessful parse; complementizer 'that' can follow matrix verb, given the nature of the verb 'persuade'.

LDD
* Pam, Jan believes that Michael likes - successful parse
* Pam, Jan believes that Michael likes her - unsuccessful parse; cannot have word occupying object position of embedded clause, as that element has merely moved from where it was initially licensed


# For the shuffle operator grammar, I have appended both an adjective phrase AP, as well as the relevant adjectives ("big", "shy"). 
# When it came to parsing, I noted that in the parse trees, the correct parses resulted in the adjectives modifying the subject noun, which is the intended reading (i.e., "(the) big, shy gorilla eats (the) banana.").
# In the incorrect parses, however, where adjectives occur after the subject, this second adjective instead modifies the object noun (i.e., "(the) shy gorilla eats (the) big banana"), as opposed to having adjectives on either side of the subject. Ultimately, however, there is not enough data on this language's syntactic structure to ascertain the position that object adjectives occupy. I believe the parsing trees are in line with the rule that any adjectives modifying the subject noun must occur immediately to its left.
