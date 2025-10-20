# Slot-Machine-Python
A simple Python slot machine game! Players top up balance, spin the reels, win prizes, and withdraw winnings. Features input validation, balance tracking, and random outcomes using random.choice(). 
__________________________________________________________________________________________________________________________________________________________________________________________________________________
This Python script is a simple slot machine game. It starts by importing the random module to randomly select symbols for the reels. The game uses a list of symbols and defines a fixed stake of $5, which is the minimum balance required to play. The player’s balance starts at $0 and can be topped up using the top_up function, which ensures only positive amounts are added.

The withdraw function allows the player to take money out at the end of the game, validating the requested amount against the current balance. The spins function generates a random outcome for three reels using random.choice.

The main function contains the game loop. Players can press P to play or Q to quit. If their balance is insufficient, they are prompted to top-up. Each spin deducts the stake and evaluates the reels to determine winnings: a jackpot of $20 for three matching symbols, $5 for two consecutive matches, and $1 for matching the first and last symbol.

On quitting, players can choose to withdraw, with validation ensuring they cannot withdraw more than they have. The program is modular and uses if __name__ == "__main__": so it can be imported without automatically running.
__________________________________________________________________________________________________________________________________________________________________________________________________________________
