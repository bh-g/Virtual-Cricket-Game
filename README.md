# Virtual-Cricket-Game
A cricket game application built using the C++ programming language
Project features:
1.There are two teams team A and team B
a. Each team has 4 players which are selected by the user from the given pool of 11 players
b. The sequence in which the players are selected for each team decide the batting and bowling sequence for that team.
2. There are innings of 6 balls each:
a. In each innings, only one bowler from the bowling team bowls all the 6 deliveries and at a time one batsman from the batting team bats until he is declared out.
b. The first player from the bowling team will be always selected to bowl first and
the first player from the batting team will be always selected to bat first.
c. When a batsman is OUT, the next batsman from the batting team in sequence starts batting.
3. There is a toss functionality
a. The team who wins the toss decides to either bat or bowl first.
4. In each delivery, possible runs can be scored from 0 to 6.
5. OUT criteria: If a batsman scores 0 runs he will be declared OUT and the next batsman in sequence will start batting.
6. Match End criteria:
a. If runs scored by TeamA is greater than the opponent TeamB, then TeamA will win the game or vice-versa.
b. If runs scored by TeamA and TeamB are the same then the match will draw.
