# simonsays
Simon Says(SS) is a webbased memory game where you have to copy the sequence that SS makes.
reference to the RL item https://www.youtube.com/watch?v=1Yqj76Q4jJ4

reference freecodecamp https://www.youtube.com/watch?v=n_ec3eowFLQ
Recommended to be played on a tablet 
## DOCUMENTATION
### APPROACH / first thoughts
1. HTML
- take a html5 boilerplate
- add bootstrap5
- divide the window with 4 equal square
2. CSS

3. JS
- sequence generation: 
  - push start
  - start session
  - generate an array with 20 keys with the random 4 buttons/colors [1, 2, 4, 2, 3, 4, 1, 1, 3, 2, 2]
  - if input sequence is wrong -> play game over sound
  - stop session
- register the onclick events
- play sound
- delay between buttons => 3 seconds
### GAMEPLAY FEATURES
- on every round the level of difficulty changes by adding additional sequence by color/sound
- each round has the same amount of sequence (ex. Round 4 with have 4 sequences)
- getting the wrong sequence will result in a game over.
- multiple players: tdb

### OPTIONS
- SOUND ON/OFF
- CHANGE COLORS
- AMOUNT SEQUENCE
- MULTI PLAYER
- 
