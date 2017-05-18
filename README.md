# Mafia

## Description
This is an online Mafia game where players are automatically given roles to play the game Mafia. Players are given time to discuss about who is mafia and vote on the person to kill. The person who is blamed as the mafia is given time to defend him or herself. The narration is done automatically, with various storylines. Depending on the number of the players, number of roles differ, too.

## Mockups

### Home
![home](public/images/Mafia_home.png "home")

### Profile
![profile](public/images/Mafia_profile.png "profile")

### Directions
![directions](public/images/Mafia_directions.png "directions")

### Players
![players](public/images/Mafia_players.png "players")

### Chat
![chat](public/images/Mafia_chat.png "chat")

## Architecture

### Libraries
We're using React.js to compartmentalize the application, and also to make React Router available to us. We're planning to use Redux for storing the in-game information in global state, like current players, score, and who's in the graveyard.

We need a backend framework, and since we don't really know any better, we're going to use MongoDB with Mongoose and Express.

## Setup

TODO: how to get the project dev environment up and running, npm install etc

## Deployment

TODO: how to deploy the project

## Authors

- Annie Ke '19
- Nitasha Kochar '19
- Sia Peng '20
- Adam Rinehouse '19
- Andy Yoon '19

## Acknowledgments

Thanks to [Tim Tregubov](https://github.com/timofei7) for [this great walkthrough](http://cs52.me/assignments/sa/starterpack/) on building the frontend starterpack, as well as for [the backend starter](https://github.com/dartmouth-cs52/express-babel-starter).
