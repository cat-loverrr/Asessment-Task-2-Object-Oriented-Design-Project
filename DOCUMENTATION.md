# Assessment Task 2: Object-Oriented Design Project: Car Comparison Game
## By Isabella Usacheva


## Part A - Data Selection and Game Attributes (10 marks)
### Using car listings as insipiration:
- Select 6 attributes for your game (e.g price, km, power)
- Rank them from most powerful to least powerful in the game mechanics
- Explain:
    1. Why each attribute was chosen
    2. What makes an attribute fair or unfair in gameplay
## Part B - Class Design (10 marks)
### Design the object-oriented structure of your game.
### Required classes:
- Car
- Card
- Deck
- Player
- Game
### For each class:
- List attributes
- List methods
- Describe its role in the system
## Part C - Class Diagram (10 marks)
### Create a UML class diagram including:
- All classes
- Attributes and methods
- Relationships (association, aggregation, inheritance if used)
### Must include:
- Clear structure
- Correct relationships
- AT least 2 annotated design decisions
## Part D - Game Mechanics Design (10 marks)
### *Explain*  how the game works:

Each player should have three or more cards in their hand, unless there are no cards left in the draw pile (if there is less than 3, draw another card. The draw pile is shared between the players). Each player picks a card from their hand, and sets the other two cards down.The person left to the dealer picks an attribute first, and announces both the attribute and their value. The game will go clockwise from then on, until each player has announced their value. The player with the highest value will give their card to the player with the lowest value, and if you meet neither of those conditions, you will keep your card. Once the round ends, the losing player (player who recieved an extra card) will announce the new attribute. If there is a draw at any moment, everyone will put their cards at the bottom of the deck, shuffle the deck, and draw a new card. The game ends once there is no draw pile, and someone runs out of cards. 

The game is balanced as everyone picks a card at the same time, and they are each limited to that singular card. If you are the 'losing player', you will have an advantage in the next round to pick the attribute to avoid losing multiple times in a row. One unfair advantage is what happens during a draw; if you were bound to lose, your card gets put inside the pile regardless, and you get to pick a new card, which is unfair to the people which would've won. Making a set of rules to avoid this is extremely complicated due to the possibility of outcomes depending on how many players there are (e.g. 2 players is fair, 3 players the person who isn't in a draw could keep their card, 4 players if the top two people were in a draw they gave a card each to the lowest two scoring players, 4 players if the middle two people draw it doesn't matter), however, this is possible and will be implemented as an advanced version to the game.

### Advanced Gameplay
# PUT IN EXTRA RULES

### Must include: 
- *Explanation* of game balance
- *Identification* of at least one unfair advantage and a proposed solution to fix it
- *A modelled **structure chart***
## Part E - Interface and Card Design (5 marks)
### Create:
- A card design (Top Trumps style)
- A basic game interface sketch
### Must include:
- **Labels** and **annotations** explaining design choices
- Clear layout of information
- **Storyboard** and/or walk through
## Part F - Social, Ethical, and Legal Implications (5 marks)
You must **critically analyse** how your car comparison game immpacts individuals, society, and the environment. Using your designed system, respond to the following:
### 1. **Individual Impact**
- How could your game influence user behaviour or decision-making?
- Could it encourage bias (e.g. favouring expensive or high-performance cars)?
- What responsibilities do you have as a designer to present fair information?
### 2. **Social Impact**
- How might your game reinforce stereotypes or inequalities (e.g. wealth, status, access to vehicles)?
- Does your system favour certain types of users or cars?
- How could your design be made more inclusive or fair?
### 3. **Environmental Impact**
- How could your game influence attitudes towards fuel use, emissions, or sustainability?
- Does your attribute selection promote or ignore environmental considerations?
- What changes could you make to encourage more environmentally responsible thinking?
### 4. **Legal Considerations**
- What legal issues could arise from using real-world car data (e.g. ownership, copyright, accuracy)?
- What responsibilities do you have when displaying or using data inspired by platforms like carsales.com.au
- How would you ensure your system avoids misleading users?