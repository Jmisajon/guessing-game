# guessing-game

This is a simple networked guessing game implemented in Python using sockets. The game allows clients to connect to a server, choose a difficulty level, and guess a randomly generated number within a specified range. The server tracks scores for each player and displays a leaderboard at the end of each game.

Client-Server Architecture: The game follows a client-server model where the server manages game logic and communication with clients.

Scalability: The server is designed to handle multiple client connections concurrently using TCP sockets.

Difficulty Levels: Players can choose from three difficulty levels - easy, medium, and hard, each with a different range of numbers to guess from.

Score Tracking: The server keeps track of each player's score, which is the number of attempts taken to guess the correct number.

Leaderboard: At the end of each game, the server displays a leaderboard showing the scores of all players.
