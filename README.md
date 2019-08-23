# Object-oriented design for Pig in Java

## Description

Design and implement an object-oriented version of the game [Pig](<https://en.wikipedia.org/wiki/Pig_(dice_game)>).

## Normal Mode

A version of the game Pig implemented in Java. 

Two players are trying to reach 100 points first. On a player's turn, they roll a die over and over until they roll a 1 (a "pig") or they choose to hold. If they hold, they add the sum of their rolls to their score. If they roll a 1, they get no points. After a 1 is rolled or the player holds, the other player takes their turn.

The first player is chosen randomly. (For example, you could flip a coin or both roll a die and pick the higher roll.)

In this implementation, there will be one human player and one computer player. The computer player will always hold until it roll a total of 20 points.


### Example 

```
You will be player 2.
Enter nothing to roll; enter anything to hold.
Player 1 score: 0
Player 2 score: 0
It is player 1's turn.
Roll: 5
Roll: 3
Roll: 5
Roll: 1
Turn total: 0
New score: 0
Player 1 score: 0
Player 2 score: 0
It is player 2's turn.
Roll: 6
Turn total: 6 	Roll/Hold? (Enter)
Roll: 5
Turn total: 11 	Roll/Hold? (Enter)
Roll: 6
Turn total: 17 	Roll/Hold? (Enter)
Roll: 2
Turn total: 19 	Roll/Hold? (Enter)
Roll: 2
Turn total: 21 	Roll/Hold? h
Turn total: 21
New score: 21
Player 1 score: 0
Player 2 score: 21
It is player 1's turn.
Roll: 5
Roll: 6
Roll: 3
Roll: 5
Roll: 1
Turn total: 0
New score: 0
Player 1 score: 0
Player 2 score: 21
It is player 2's turn.
Roll: 6
Turn total: 6 	Roll/Hold? (Enter)
Roll: 6
Turn total: 12 	Roll/Hold? (Enter)
Roll: 2
Turn total: 14 	Roll/Hold? (Enter)
Roll: 6
Turn total: 20 	Roll/Hold? h
Turn total: 20
New score: 41
Player 1 score: 0
Player 2 score: 41
It is player 1's turn.
Roll: 3
Roll: 3
Roll: 6
Roll: 4
Roll: 4
Turn total: 20
New score: 20
Player 1 score: 20
Player 2 score: 41
It is player 2's turn.
Roll: 3
Turn total: 3 	Roll/Hold? (Enter)
Roll: 3
Turn total: 6 	Roll/Hold? (Enter)
Roll: 2
Turn total: 8 	Roll/Hold? (Enter)
Roll: 2
Turn total: 10 	Roll/Hold? (Enter)
Roll: 4
Turn total: 14 	Roll/Hold? (Enter)
Roll: 2
Turn total: 16 	Roll/Hold? (Enter)
Roll: 4
Turn total: 20 	Roll/Hold? h
Turn total: 20
New score: 61
Player 1 score: 20
Player 2 score: 61
It is player 1's turn.
Roll: 5
Roll: 1
Turn total: 0
New score: 20
Player 1 score: 20
Player 2 score: 61
It is player 2's turn.
Roll: 3
Turn total: 3 	Roll/Hold? (Enter)
Roll: 3
Turn total: 6 	Roll/Hold? (Enter)
Roll: 5
Turn total: 11 	Roll/Hold? (Enter)
Roll: 2
Turn total: 13 	Roll/Hold? (Enter)
Roll: 6
Turn total: 19 	Roll/Hold? h
Turn total: 19
New score: 80
Player 1 score: 20
Player 2 score: 80
It is player 1's turn.
Roll: 3
Roll: 1
Turn total: 0
New score: 20
Player 1 score: 20
Player 2 score: 80
It is player 2's turn.
Roll: 2
Turn total: 2 	Roll/Hold? (Enter)
Roll: 2
Turn total: 4 	Roll/Hold? (Enter)
Roll: 4
Turn total: 8 	Roll/Hold? (Enter)
Roll: 2
Turn total: 10 	Roll/Hold? (Enter)
Roll: 3
Turn total: 13 	Roll/Hold? (Enter)
Roll: 6
Turn total: 19 	Roll/Hold? (Enter)
Roll: 5
Turn total: 24 	Roll/Hold? h
Turn total: 24
New score: 104
```

