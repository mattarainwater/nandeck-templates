Get nanDECK here: https://nandeck.com/

# Overview
nanDECK templates for two simple card types

Each deck consists of a .txt file for the deck itself, a .csv for it's data and images used in the cards themselves.

# Templates
## Cost Card Deck
A "cost" card with a name, image, rules text, cost and an optional "points" value in the bottom left. For games like MTG, Dominion, etc.

cost-card-deck.txt - the deck itself, contains the directives required to render the cards.

cost-data.csv - the data for the deck, contains the names, costs, etc. for each card

## Playing Card Deck
A "playing" card with a value, color, and symbol. For traditional-esque card games like Poker or Tichu.

playing-card-deck.txt - the deck itself, contains the directives required to render the cards.

playing-data.csv - the data for the deck, contains the values, color, symbols for each card

# Assets
Contains the images referenced in the .csv files for display on the cards

# Rendered
Contains the fully rendered cards built with nanDECK from the decks/data/assets.
