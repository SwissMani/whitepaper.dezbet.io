---
order: 1015
icon:
---
![](/static/headers/DezBet_Game_Concepts_ENG.png)

# 5. Game Concepts

|||[!badge variant="primary" text="1-versus-All - 1vN"]
Time-based game which allows any number of players to join. It is based around an unbounded address pool which stores the addresses of participants. 

Each participant can enter the game by sending a designated amount of gas coins to the contract. After the timer expires, the job scheduler will call the winner-picking function, which in turn queries the VRF to get a random number. Modulo of this number will determine the winner, who takes all the collected funds within the contract, minus the platform fees. 
|||

|||[!badge variant="primary" text="NFT Jackpot"]
This is another medium-paced game. The chance of winning: $$\frac{y}{x}$$, where $$x$$ is the total jackpot value and $$y$$ is the bet value, and the winnings will be the sum of all jackpot entries.  It will function similarly to other jackpot games and progressive slot machines, enabling the player to win NFTs of both high and low values. The player will choose the number of NFTs or units to bet – the value staked determining the value that is available to win – and a VRF to initiate the game. The VRF selects the winner. Players' odds remain the same, however, not changing with the amount of the bet. The entire jackpot is available to win at any time.
|||

|||[!badge variant="primary" text="Coin Flip"]
This is a fast-paced game. The chance of winning:  $$P(ChosenSide) = P(CS) = \frac{1}{2} = 50\%$$, and the winnings will total $$2x$$ of the amount bet. It is a familiar game, played by two people, in which each player gets one half of the odds. The VRF then chooses the winning half of the bet. It is a winner-take-all game.
|||

|||[!badge variant="primary" text="Lottery"]
This is a medium-paced game. The chance of winning is $$\frac{16!}{(16-5)!} , \frac{24!}{(24-5)!}, 5\frac{32!}{(32-5)!}$$, and the winning total is the sum of the entries. Unlike other lotteries, which take place on a schedule, this lottery will take place whenever the first player buys a ticket. The contract then begins a timer, after which the VRF will determine the winner. Because there is no lottery authority, the winner gets everything, minus the nominal DezBet fee. If no one wins the jackpot, then it rolls over into the next lottery.
|||

