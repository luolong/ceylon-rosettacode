# Rosettacode: Playing cards in Ceylon

[http://rosettacode.org/wiki/Playing_cards#Ceylon](http://rosettacode.org/wiki/Playing_cards#Ceylon)

## Task description

Create a data structure and the associated methods to define and manipulate a deck of [playing cards][1].

The deck should contain 52 unique cards.

The methods must include the ability to make a new deck, shuffle (randomize) the deck, deal from the deck, and print the current contents of a deck.

Each card must have a _pip_ value and a _suit_ value which constitute the unique value of the card.

[1]: http://en.wikipedia.org/wiki/Playing-cards#Anglo-American-French

## Implementation

**Code:**
[run.ceylon](run.ceylon)

**Output:**

    New deck (52 cards): 
      2 of ♣, 3 of ♣, 4 of ♣, 5 of ♣, 6 of ♣, 7 of ♣, 8 of ♣, 9 of ♣, 10 of ♣, J of ♣, Q of ♣, K of ♣, A of ♣
      2 of ♥, 3 of ♥, 4 of ♥, 5 of ♥, 6 of ♥, 7 of ♥, 8 of ♥, 9 of ♥, 10 of ♥, J of ♥, Q of ♥, K of ♥, A of ♥
      2 of ♠, 3 of ♠, 4 of ♠, 5 of ♠, 6 of ♠, 7 of ♠, 8 of ♠, 9 of ♠, 10 of ♠, J of ♠, Q of ♠, K of ♠, A of ♠
      2 of ♦, 3 of ♦, 4 of ♦, 5 of ♦, 6 of ♦, 7 of ♦, 8 of ♦, 9 of ♦, 10 of ♦, J of ♦, Q of ♦, K of ♦, A of ♦
    
    Shuffeled deck (52 cards): 
      4 of ♠, 2 of ♦, 5 of ♣, 9 of ♠, 4 of ♥, 7 of ♥, 10 of ♦, 5 of ♠, 3 of ♥, K of ♥, 6 of ♣, 9 of ♦, 6 of ♦
      4 of ♣, 8 of ♣, 4 of ♦, Q of ♥, 6 of ♥, J of ♥, 8 of ♦, 5 of ♥, 5 of ♦, J of ♣, A of ♥, J of ♦, 2 of ♣
      7 of ♠, Q of ♦, A of ♣, Q of ♣, 6 of ♠, Q of ♠, K of ♠, 7 of ♦, 7 of ♣, 3 of ♦, 2 of ♠, 8 of ♥, A of ♦
      2 of ♥, 9 of ♣, 8 of ♠, 10 of ♥, 3 of ♠, 10 of ♣, 9 of ♥, 10 of ♠, 3 of ♣, J of ♠, K of ♣, K of ♦, A of ♠
    
    Deal three hands: 
    - Dealt 5 cards to hand 1 : 4 of ♠, 2 of ♦, 5 of ♣, 9 of ♠, 4 of ♥
    - Dealt 5 cards to hand 2 : 7 of ♥, 10 of ♦, 5 of ♠, 3 of ♥, K of ♥
    - Dealt 5 cards to hand 3 : 6 of ♣, 9 of ♦, 6 of ♦, 4 of ♣, 8 of ♣
    
    Deck (37 cards) after dealing three hands: 
      4 of ♦, Q of ♥, 6 of ♥, J of ♥, 8 of ♦, 5 of ♥, 5 of ♦, J of ♣, A of ♥, J of ♦, 2 of ♣, 7 of ♠, Q of ♦
      A of ♣, Q of ♣, 6 of ♠, Q of ♠, K of ♠, 7 of ♦, 7 of ♣, 3 of ♦, 2 of ♠, 8 of ♥, A of ♦, 2 of ♥, 9 of ♣
      8 of ♠, 10 of ♥, 3 of ♠, 10 of ♣, 9 of ♥, 10 of ♠, 3 of ♣, J of ♠, K of ♣, K of ♦, A of ♠
