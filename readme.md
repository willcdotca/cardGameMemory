# Collaborative Build
## Card Game
****Concentration**** is also known as:

    - Memory
    - Matching Pairs
    - Match Match
    - Match Up  
    - Pelmanism 
    - Shinkei-suijaku 
    -  Pexeso 
    - and potentially More

###Participants 
As of Feb 1 2021 - Mar 31 2021

    - ljtechdotca
    - tid (will need to look up tid's full name)
    - willcdotca

##Objective of collaborative build:

    - Built within one html file using html, css, and javascript
    - See the same things from different perspectives
    - Learn by reference to similar concepts and ideas
        - I did X when attempting A, I see you did Y instead and it looks more effeicient. I'll attempt to adopt Y instead of X.
    - Very basic in terms of web technology potential
        - Starting at ground level and mastering the basics of web technologies
        - Frameworks are great, but knowing how to use the language before stringing together near incoherant strings is better.
    - Better interpretation of skill level when pooled with other developers
        - Learn of personal strengths and weaknesses.
    - Competitive has its place but the tenacity that competing takes changes the dynamic of the learning experience. 
        - The goal remains focused on developing a personal best
            - ie. How to reach, if only for a moment, a person best
        - [Does competition increase or decrease personal growth?]
            - Hmmmmm




    
Reference:

- [Wikipedia: Concentration Card Game](https://en.wikipedia.org/wiki/Concentration_(card_game))

#Day 4 Notes:

Is today the day to rebuild everything that has already been built?
###Terminology:
- **Face**:
    - Ace
    - Two through Ten
    - Jack
    - Queen
    - King
- **Suit**: 
    - ♠
    - ♣
    - ♥
    - ♦
- **Color**: 
    - Red 
    - Black
    - (Any?)
- **Game**:  
    - One or more **Player**s 
    - Match two **Card**s 
    - Until all **Card**s in the **Deck** are paired
- **GameType**: 
    - **Host** selects **Game** settings to determine the rules
    - Modifies **Deck** quantity, composition, layout, and pair eligibility
- **Deck**: All **Card**s included at the beginning of a **Game**  [Standard fiftytwo card deck of playing cards](https://en.wikipedia.org/wiki/Concentration_(game_show))
  unless GameType permits otherwise
- **Card**: A single unit of a **Deck** 
- **Component**: Any tag element created by the **Game**, 
  or preexisting within the body of the page on loading of the page
- **Player**: The human, or AI, that receives a point for every valid pair of **Card**s 


###Components
- article#playerForm  
    - input#playerName
    - select#gameType
    - input[type="checkbox"]#gameType
    - button#playerButton
    
- ul#currentPlayers  
    - a#playerName.value
    
- article#cards  
    - a.card      
        - .dataset.suit 
        - .dataset.face 
        - .dataset.color 
      
- Game Controls  
    - Start New Game
    - Restart Current Game
    - Save Game
    - Load Game
    
###Game Types:
- Zebra: 
  
    - Faces match
    - Colors !match
    - Suits N/A

- Double Deck
  
    - Faces match
    - Colors N/A
    - Suits match
    - Double the quantity of the deck

- Jokers (Toggle)

    - Add Two Jokers per deck
  

        
        













































