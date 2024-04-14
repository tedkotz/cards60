Alternative deck design
=======================

Being a highly composite number a 60 card deck should allow for a greater variety of games than the standard 52-card deck.

For example, it can be evenly dealt between 2,3,4,5, or 6 players allowing for trick taking games with other than 4 players.

- 52 can be evenly dealt between 2,4,13,26
- 56 can be evenly dealt between 2,4,7,8,14,28
- 60 can be evenly dealt between 2,3,4,5,6,10,12,15,20,30
- 64 can be evenly dealt between 2,4,8,16,32
- 68 can be evenly dealt between 2,4,17,34
- 48 can be evenly dealt between 2,3,4,6,8,12,16,24

52 cards
--------
Just for reference in case a reminder is needed on how a 52-card deck of playing
cards work.

#### Suits (4ths)
- Clubs
- Diamonds
- Hearts
- Spades

#### Ranks (13ths)
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9
- 10
- Jack
- Queen
- King
- Ace (or 1)

#### Colors (1/2)
- Red
    - Diamonds
    - Hearts
- Black
    - Clubs
    - Spades


60 Compatible
-------------
Every card from the standard 52-card deck has an equivalent so you can easily filter
down to a 52-card deck is needed. 2 more ranks are added to get to 60 cards 1s and Maids.
The ten can also be abbreviated as the 0 in the corner, but with 10 icons.

#### Suits (4ths)
- Clubs
- Diamonds
- Hearts
- Spades

#### Ranks (15ths)
- 1
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9
- 0 (10)
- J ack (Knave, Footman or Squire)
- M aid (Paige, Gillian, Damsel, Colleen, Colette, Mounted Lady, Cavalier or Knight)
- Q ueen
- K ing
- A ce

#### Colors (1/2)
- Red
- Black

#### Thirds
- Low 1-5
- High 6-0
- Faces J-A

#### Fifths
- Low      1-3
- Medium   4-6
- High     7-9
- Common   0-M
- Court    Q-A

60 Compromise
-------------
This is a split that highlights making the cards as divisible as possible.
There are only 12 Ranks, so we merge the Jack and 10.
The 5 suits are not divisible so the suits don't directly follow the colors.

#### Suits (5ths)
- Clubs
- Diamonds
- Hearts
- Spades
- Moons (or Crescents)

#### Ranks (12ths)
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9
- J ack (or 10)
- Q ueen
- K ing
- A ce (or 1)

#### Colors (1/2 and 1/4)
- Warm
    - Red (or Magenta)
    - Yellow
- Cool
    - Green
    - Blue (or Cyan)

|       |Clubs |Diamonds |Hearts |Spades |Moons |
|-------|------|---------|-------|-------|------|
|Red    |J47   |Q38      |K29    |A56    |A56   |
|Yellow |Q38   |K29      |A56    |J47    |K29   |
|Green  |K29   |A56      |J47    |Q38    |Q38   |
|Blue   |A56   |J47      |Q38    |K29    |J47   |

#### Thirds
- Low 2-5
- High 6-9
- Faces J-A

60 Decimalized
--------------
The ranks of the cards could be reduced down to just the 10 digits.
This then allows for there to be 6 suits, which is also a highly composite number
So it can be split into 2 different sub-groupings (of 2 or 3) maybe by color and
general shape?

#### Color & Suits
- Red
    - Diamonds
    - Hearts
    - Pentacles (or Stars)
- Black
    - Clubs
    - Spades
    - Moons (or Crescents)

#### Suit Classes (3rds)
- Rounded
    - Clubs
    - Hearts
- Sharp
    - Spades
    - Diamonds
- Astral
    - Pentacles
    - Moons

#### Rank
- 1
- 2
- 3
- 4
- 5
- 6
- 7
- 8
- 9
- 0 (10)

60 Factorised Options
---------------------
There are 4 prime factors in 60(2*2*3*5) so each could be it's own suit dimension.

#### Colors (1/2 and 1/4)
- Warm
    - Red
    - White (Yellow)
- Cool
    - Green
    - Black (Blue)

#### Class
- Worker
- Noble
- Royal

#### Suits (5ths)
- Clubs
- Diamonds
- Hearts
- Spades
- Moons (or Crescents)

#### Even/Odd
By number

#### Suits (4ths)
- Rounded
    - Clubs
    - Hearts
- Sharp
    - Diamonds
    - Spades

#### Rank
- 1 Clubs
- 2 Diamonds
- 3 Hearts
- 4 Spades
- 5 Moons (or Crescents)
- 6 Moons (or Crescents)
- 7 Spades
- 8 Hearts
- 9 Diamonds
- 0 Clubs (10)


```
pandoc -f markdown_mmd+task_lists+emoji+autolink_bare_uris -t html --filter pandoc-plantuml Readme.md > readme.html
```

Game Rules
----------

### Terms
Pair
: 2 cards of the same rank aka 2-of-a-kind.

Triple
: 3 cards of the same rank aka 3-of-a-kind.

Quartet
: 4 cards of the same rank aka 4-of-a-kind or book.

Quintet
: 5 cards of the same rank. Only possible with wilds or multiple decks.

Eldest (Hand)
: Player to the left of the dealer, usually first player.

Play Order
: Standard play starts with the Eldest Hand and goes clockwise, with play passing to the left.

Fold
: Forfeit of the game surrendering to move on to next game or hand.

Rank
: Ordered Low to High: 1 2 3 4 5 6 7 8 9 0 J M Q K A.

Flush
: Set of cards, usually 5, all same suit.

Straight
: Set of cards all of consecutive ranks.

Straight Flush
: Set of cards both a straight and a flush.

Wild Cards
: Card treated as if it were any card. Wild cards should be agreed  upon before play starts.


#### Draw Lots (Cut for High Card)
Often used to determine
dealer, teams or first
player. Each player
reveals a random card
from the deck. High card
wins. Aces are high.
For teams, the top 2 are
a team, then the next 2
are a team, etc.

#### Blackjack or 21
*Classic casino game to get 21 without going over for 1+ Players*

Numerical cards are at
face values, face cards
at 10, and aces are
valued at 1 or 11. Deal 2
cards first-one revealed
to players. On your turn,
if you have less than 21
points revealed you may
"hit" being given another
face up card or "stand"
keeping you hand total.
Once all players have
chosen to "stand", fold
or busted (going over 21)
all cards are revealed.
Hand total closer to 21
without busting wins.
In casino variants, all
players play with revealed
cards against the house
hand, which wins ties, is
forced to hit on 16 or
less, and stay on 17 or
more. After all players
turns, the house hand is
fully revealed before it
"plays".

#### Bluff
*Lie to shed your cards first for 2-6 Players*

Deal deck fully out to
all players as their
hands. Standard play order
starting with Aces. On
your turn, you call out a
number of 1 or more cards
and rank up or down 1
from the rank called by
the last player and
discard that many cards
face down. If a
challenger calls your
"bluff" before the next
player plays cards, those
cards are revealed. If
the revealed cards don't
match what was called you
take the discard pile to
your hand. If they do
match, the challenger
takes them instead. You
win when you run out of
cards.

#### Crazy Eights / Switch
*Classic UNO-like game for 2-8 Players*

Deal players 5 cards.
Discard top card of deck.
On each turn, You must
draw cards until you can
play a card that matches
the suit or rank of the
last  discard, or a
Crazy 8 (declaring a new
suit to match). Playing a
2 the next player must
draw 2 cards, unless they
play a 2 instead the
player after them must
draw 4 etc. Playing a
Queen skips the next
player. Playing an Ace
reverses the direction of
play. First to shed their
hand scores cards in all
opponent's hands.
50 for 8s, face value for
numbers and 10 for others.
2 common additional rules:
4 works like 2, but draws
4 cards. When playing your
2nd to last card you must
announce it.

#### Go Fish
*Family classic for 2-8 Players*

Deal players 5 cards.
Remaining cards are the
pool. On each turn you
ask any another player
for their cards of a
particular rank. They
must hand over all cards
of that rank if possible.
If they have none, then
you must "go fish" and
draw a card from the
pool. If the card drawn
is the card asked for
reveal it and take
another turn. If at any
time you have a quartet,
and the cards must be
placed down face up. When
all quartets have been
completed, the player
with the most quartets wins.

#### Kings in the corner
*Solitaire like game for 2-7 Players*

Deal players 7 cards.
Place the deck in the
middle of the tableau.
Draw 4 cards placing 1 on
each side of the deck,
with open corner space. On
your turn, you may make
any number of valid
placements: King to an
empty corner. Card to an
empty side. Card to a side
such that is is place on
top of a card 1 rank higher
with opposite color. Move
an entire side pile as if
it was the bottom card of
the pile. End your turn by
drawing a card. First to
empty their hand wins.

#### Old Maid
*Match making game for 2-11 Players*

3 queens are removed from
a deck, the remaining
queen is the Old Maid.
Draw lots for dealer,
standard play order.
Deal out cards. On each
turn you play a matched
pair or draw a card from
the player on your left.
If you have no more cards
you win, removing you
from play. Play continues
to see who will be left
with the Old Maid.

#### Palace
*Shedding game with multiple levels to shed for 2-6 Players*

Deal each player 9 cards,
3 down-cards in a row,
3 up-cards face up on the
down-cards, and 3 hand
cards. The hand cards
must all be played before
up-cards which must be
played before down cards.
Before play begins player
may swap cards between
their hand and face up
cards, but they may not
even look at the face
down cards.

On your turn,
you must discard 1 or
more cards, all of the
same rank equal to or
higher rank than the last
card discarded or you
must take the entire
discard pile into your
hand. Down-cards are
played site unseen and if
the card played is less
than the last discard you
take the entire discard
pile into your hand. The
lowest rank card (a 1)
may be played on any
card, and any card may
follow it. 10s may be
played on any card, and
then the discard is
removed from the game.
The same player then goes
again starting a new
discard. If 4 cards of
the same rank are on top
of the discard pile
either all at once or
across multiple turns, it
is the same as a 10. The
last player to empty
their hand, up-cards and
down-cards loses.

#### Solitaire (Klondike)
*Players 1*

Deal 7 face down play
piles, each contains 1
more card from left to
right. The top card on
each pile is face up.
There are 4 initially
empty goal piles. The
goal piles can have the
lowest rank placed on them
when empty, then the next
rank up of the same suit.
The play piles face up
cards must remain stacked
as decrementing ranks with
alternating colors. You
can: Draw and discard
3(variant 1) cards. Move
the top discard to a
valid pile. Move the top
face up card from a play
pile to the appropriate
goal pile. Move any face
up card and everything on
top of it from a play pile
to another play pile. If
the top face down card in
a play pile has nothing on
top of it flip it over.
Anything may be played
face up to an empty play
pile. If all cards are in
the goal piles you win.

#### Spoons
*Fast paced card passing game for 3-15 Players*

N players need N quartet of
cards and N-1 spoons or
similar safe hand held
objects. Place the spoons
in the middle of all the
players. Shuffle and deal
out the cards, 4 each.
Turns occur concurrently
after dealing is done.
Each player discarding a
card to the left player,
getting one from the
right player. Once you
have a quartet, you may grab
a spoon. After any player,
grabs a spoon all player
may grab a spoon. The last
player without a spoon,
loses the hand. If the
first player who touched
a spoon did not have a
quartet, they instead lose
the hand. When you lose
the hand, you get one
letter in "S-P-O-O-N-S".
The first player to get
all 6 letters loses the
game.

#### War
*Simple Battle game to capture the whole deck for 2-6 Players*

Divide cards evenly
between all players,
discarding extras. For
each Battle, all players
reveal the top card of
their deck. The player
with the highest card
captures all other cards
putting them on the
bottom of their deck.
Ties result in a War
between tied players.
Each player in the war
plays an extra card face
down and then reveals a
card face up as in the
Battle. If a player runs
out of cards they lose
and are eliminated.

### Poker
In casual games dealer
usually rotates with
each hand.

#### Hand Ranks
The Poker hands from High
to Low, ties broken with
high cards, in the
largest set first.

1. Quintet
2. Straight and Flush
3. Quartet
4. Full House=Triple & Pair
5. 5 card Flush
6. 5 card Straight
7. Triple
8. 2 Pairs
9. Pair
10. No Pairs, High card

#### Betting
A forced blind bet is
often played before
dealing to start the
winnings pot. Either a
fixed ante from all
players or the first 2
players must make a
small and big blind bet
that will be called in
the first betting round
after dealing.

A limit maybe be placed
on how much of an open
or raise a player can
do in a single round.

For each round of betting,
Before the first bet you
may Check, not place a
bet; or Open, make the
first bet. After the open
you may Fold, forfeit the
hand losing any bets;
Call, match the high bet
or go all-in; Raise,
increase the high bet.

A player wishing to call,
but with insufficient
stakes may go all-in,
betting all remaining
stakes. This caps the
high bet of main pot at
the all-in amount. Any
bets over this amount
are placed in a side pot,
and cannot be won by the
all-in player.

Once every player has
folded, called or checked,
betting is over.

If all other players fold,
the remaining player wins
and is not required to show
their hand.

#### Poker, 5-card Draw
*Classic poker for 2-8 Players*

Blind bets are placed.
Deal players 5 cards. Then
start the 1st betting
round with the Eldest. In
turn order each remaining
player discards and is
dealt a number of cards,
up to 3, 4 cards may be
discarded if the player
reveals an Ace. Then
start the 2nd betting
round with whoever opened
in the 1st round. In turn
order, each remaining
player reveals their hand.
Best hand wins.

#### Poker, 7-card Stud
*Vintage Stud for 2-8 Players*

Deal players 2 face down,
1 face up. Start the 1st
betting round with the
player showing the lowest
ranked card. Then, burn 1
and deal players 1 up-card.
Start the 2nd betting
round with the player
showing the highest ranked
poker hand. Burn 1 card
and deal players 1 up-card.
The 3rd betting round as
the 2nd. Burn 1 card and
deal players 1 up-card.
The 4th betting round as
the 2nd. Burn 1 card and
deal players 1 down-card.
The Final betting round as
the 2nd. Remaining players
reveal their hands.
Best 5-card hand wins.

#### Poker, Texas Hold 'em
*Increasingly popular poker for 2-20 Players*

Blind bets are placed.
Deal players 2 down-cards.
1st betting round.
Burn 1 card and deal the
flop, 3 common cards face
up. 2nd betting round.
Burn 1 card and deal the
turn, 1 common card face
up. 3nd betting round.
Burn 1 card and deal the
river, 1 common card face
up. Final betting round.
Remaining players reveal
their hands. Best 5-card
hand, made from hand and
common cards, wins.

#### Poker, 7-card Draft (New)
*Drafting version on poker for 2-8 Players*

Blind bets are placed.
Deal players 1 face up,
5 face down. Start the 1st
betting round with the
player showing the highest
ranked card.
Each player passes 4
down-cards to the left.
Each player passes 3
down-cards to the left.
Each player passes 2
down-cards to the right.
Each player passes 1
down-cards to the right.
2nd betting round.
Burn 1 card and
deal players 1 down-card.
Final betting round.
Remaining players reveal
their hands. Best 5-card
hand wins.

#### Poker, 5-card Commerce (New)
*Use a market to improve hands for 3-10 Players*

Blind bets are placed.
Deal players 5 cards.
Deal 1 face up market
cards. On your turn,
You may trade 1-5 cards
with the market or knock.
Then if the market has
less than 5, deal it 1.
Once a player knocks, all
other players get one
more turn to trade.
Final betting round.
Remaining players reveal
their hands. Best hand wins.

### Rummy Games
After dealing players
cards top card of the
deck is discarded.
Create melds of either
sets or Triples or
Quartets or runs of 3 or
more cards of the same
suit in rank order.

#### 500 Rummy
*Classic Rummy for 2-8 Players*

Aces may be played either
high or low. Deal players
7 cards. On your turn,
draw either the top card
of the stock or any card
from the discard. Then
lay down face up any meld
of matching cards or add
to any already played
meld. Finally discard a
card from your hand.
If you select a card
from the discard pile you
must be able to play that
card in a meld and also
take all card discarded
after it into your hand.
Hand immediately ends once
a player empties their hand.
Scoring: 5 points for 1-9,
10 points for J-K, 15
points for Ace. Add points
for a face up cards.
subtract points for cards
still in hand. Player who
went out deal next hand.
First to 500 wins. Last
to play breaks ties.

#### Gin Rummy
*Popular Gin for 2-8 Players*

Aces are played low. Deal
players 10 cards. On your
turn, Draw either the top
card of the stock or the
last discard. Then discard
a card from your hand. If
you selected, a card from
the discard pile you may
not discard the same card.
You may knock to end the
hand and score if you have
10 or less points of
deadwood, cards not in a
meld. If only 2 cards are
left to draw, the hand
ends without scoring.


Knocking player scores
the points of his opponent's
dead wood less his own. Aces
are valued at 1 point,
face cards at 10, and
numerical cards are at
face values. If an opponent has
the same or less deadwood
points then -25 point
undercut penalty.
If you have all 10 cards after
discard in a meld get +25
point gin bonus. If you
have all 11 cards in a meld
get +31 point big gin
bonus. Player
who knocked deals next
hand. First to 100 wins.

### Trick Taking Games
In team games, teammates
sit opposite each other.
Deal cards evenly between
all players. Contract
bidding may occur. A trump
suit may be declared.
First player plays a lead
card to start the trick.
Each player plays a card.
If they have one the card
must be of the same suit
as the lead card. Trick
is taken by the player
with the highest trump
card or that matches lead
suit, if no trump was
played. The player who
took the trick, leads the
next trick. After playing
all the cards, the hand
is scored. No talking or
communication between the
team members is allowed.

#### Hearts
*Force your opponents to take point cards for 2-6 or 10 Players*

No trumps, or bidding.
Teams optional.
Lowest Clubs(1C) leads
first. Avoid taking
tricks with hearts, 1
point each, or the queen
of spades, 13 points. No
leading a point card
until one is played.
Taking all the hearts
and the queen, gives
all points to each
opponent instead.
500 points loses.

#### Spades
*Popular bridge variant with contracts for 2-6 or 10 Players*

Usually teams of 2.
Trump is always spades.
Eldest bids and leads
first. Each player
bids number of tricks
they will take. May bid
blind, without looking at
their cards. May bid nil,
will take no tricks. Team
bids and tricks are added
together before scoring.
If you do not meet the bid
-10 points for each bid.
If you meet the bid, +10
points for each trick bid
and +1 for each overtrick.
If nil is bid, and met
exactly +100 points
otherwise -100 points.
If bid was blind, and met
exactly +100 points
otherwise -100 points.
500 points wins.
-200 points loses.

#### Trumps
*Popular Whist variant where players set the rules for 4, 6, or 10 Players*

Draw lots for teams of 2
and dealer. Eldest calls
trump and leads any card.
Par is number of tricks
divided by number of
teams rounded up. First
team to par scores: 1 for
simple victory, 2 for
perfect par, where
opponents take no tricks,
3 for perfect par if not
the Eldest's team.
7 points wins.

#### Whist
*Classic trick taking team game for 4, 6, or 10 Players*

Teams of 2. No bidding.
The last card dealt is
revealed to all player and
is the trump suit. Eldest
leads any card. Par is
the number of tricks in
the hand divided by the
number of teams. The team
with the most tricks taken
scores 1 for each trick
taken in excess of the par
score. 5 points wins.






## TODO Games

#### Cassino

#### Cribbage

#### Fool / Full Durak

#### Pyramid (work in progress)
*Players 1+*

create a card pyramid
base level = 9 - number of players (min 4)
take all the aces and kings out of the deck, deal one to each player.
shuffle rest of deck deal 5 cards to each player.
Turn

1. Build. Placing a card from your hand on one of
    1. A blank spot in your base level.
    2. on top of two adjacent card
    3. if you can't build once you lose and are eliminated. discard your have and pyramid.
2. Discard a card or Build again
    1. if you can't Build again you must discard a card.
3. Draw 2 cards from
    1. draw pile, if empty grab the discard pile keeping the same order
    2. at random from another player's hand they then draw a card.



