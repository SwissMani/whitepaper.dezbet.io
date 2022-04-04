---
order: 1015
icon:
---
![](/static/headers/DezBet_Game_Concepts_ENG.png)

# 5. Game Concepts

|||1v100 Normal
This is a medium-paced game. The chance of winning is $\frac{1}{x}, x \in [1, 100]$, and the winnings will total $y\cdot [x]$, y being the bet amount minus fees. Each player will select a number between 1 and 100 (each number available for selection only once), and after there are 100 players in the game or the timer runs out, an algorithm chooses the winning number at random, from only the numbers that the players have selected. 
|||

|||NFT Jackpot
This is another medium-paced game. The chance of winning: $$\frac{y}{x}$$, where $$x$$ is the total jackpot value and $$y$$ is the bet value, and the winnings will be the sum of all jackpot entries.  It will function similarly to other jackpot games and progressive slot machines, enabling the player to win NFTs of both high and low values. The player will choose the number of NFTs or units to bet – the value staked determining the value that is available to win – and a VRF to initiate the game. The VRF selects the winner. Players' odds remain the same, however, not changing with the amount of the bet. The entire jackpot is available to win at any time.
|||

|||Coin Flip
This is a fast-paced game. The chance of winning:  $$P(ChosenSide) = P(CS) = \frac{1}{2} = 50\%$$, and the winnings will total $$2x$$ of the amount bet. It is a familiar game, played by two people, in which each player gets one half of the odds. The VRF then chooses the winning half of the bet. It is a winner-take-all game.
|||

|||Lottery
This is a medium-paced game. The chance of winning is $$\frac{16!}{(16-5)!} , \frac{24!}{(24-5)!}, 5\frac{32!}{(32-5)!}$$, and the winning total is the sum of the entries. Unlike other lotteries, which take place on a schedule, this lottery will take place whenever the first player buys a ticket. The contract then begins a timer, after which the VRF will determine the winner. Because there is no lottery authority, the winner gets everything, minus the nominal DezBet fee. If no one wins the jackpot, then it rolls over into the next lottery.
|||

