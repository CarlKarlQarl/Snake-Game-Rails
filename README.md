# Snake
This is the repository for the back-end of this Snake game. It is built with Ruby on Rails and stores scores from the Snake game. Each score has the initals of the player and the points they scored. Honestly, there's not much to say here, I just needed a nice place to keep some numbers. The front-end is able to GET all the scores so it can display it on the scoreboard, and POST new scores.
# Links
- Deployed and Playable: https://snake-game-react-77b60.firebaseapp.com/
- Front-end Repo: https://github.com/CarlKarlQarl/Snake-Game-React
- Back-end Repo: https://github.com/CarlKarlQarl/Snake-Game-Rails
- Local repos (because I'm going to forget): 
    - /Users/flatironschool/Flatirons/4Mod/playground/array-of-array-of-squares
    - /Users/flatironschool/Flatirons/4Mod/playground/snake-highscores
# Known Bugs and Future Changes
- This one may be too hopeful by far, but I'd like to find something to block POST sent from Postman. Not naming any names, but a colleague definitely filled the leaderboard with bogus scores. I played around with the cors.rb for a while, but I'm not sure that is the solution to stopping those. In the meantime, the addition of some data validation could block some of the absurdly high scores.