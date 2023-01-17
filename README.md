# lotto_longshot
This is a small program that simulates a lottery, similar to the Lotto 6/49 in Canada.
I created this for two reasons:
1 - To learn the Rust programming language, and
2 - To show the statistical futility of playing lotteries.
### Usage Notes
- This is a text-only program that runs in a terminal.
- The user gets to choose 6 numbers between 1 and 49, or they can let the system
do a 'quick pick' to generate a random selection for them.
- The user can specify how many games to simulate, and the system will keep
track of how many times they got 0, 1, 2...6 correct.
- At the end the program will produce some summary statistics.
- If the user chooses 200 or fewer games, the system will show the details
of each game.
- There is no limit to the number of games to simulate (unsigned 64-bit integer).
- This was created using Rust 1.65.0 on Ubuntu Linux 22.04.
