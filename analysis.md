# Analysis

## Layer 9, Head 11

**Observed Pattern:** *Attributive adjectives and determiners attending to head nouns*

This attention head appears to specialize in linking attributive adjectives and determiners to their corresponding head nouns. For example, in the sentence *"The \[MASK] dog chased the old lady"*, the tokens "old" and "the" show heightened attention toward the noun "lady", a typical adjective-noun and determiner-noun relationship. Similarly, "the" and "\[MASK]" focus on "dog". In another example, *"The small book is too \[MASK] to not be outdated"*, both "small" and "\[MASK]" direct attention to "book", again indicating a syntactic pattern of modifier-head alignment.

**Example Sentences:**

* *The \[MASK] dog chased the old lady.*

  **Top Predictions:** big, little, old
* *The small book is too \[MASK] to not be outdated.*

  **Top Predictions:** small, large, old

<br>

## Layer 2, Head 7

**Observed Pattern:** *Finite-verb cues to the masked predicate*

This head seems focused on identifying the syntactic and semantic cues that relate to the masked main verb of a clause. In the sentence *"My friend's uncle \[MASK] to eat"*, the masked token shows strong attention to "’s", "uncle", and "eat", which are all structurally and semantically tied to the predicate. In the second sentence, *"The small book is too \[MASK] to not be outdated"*, the head links the auxiliary verb "is" with the masked token, suggesting a mechanism for maintaining verb phrase cohesion and tense agreement.

**Example Sentences:**

* *My friend's uncle \[MASK] to eat.*

  **Top Predictions:** refused, refuses, wanted
* *The small book is too \[MASK] to not be outdated.*

  **Top Predictions:** small, large, old
