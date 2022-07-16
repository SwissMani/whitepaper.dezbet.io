---
order: 1015
icon:
---
![](/static/headers/DezBet_Game_Concepts_ENG.png)

# 6. Games (MVP)

DezBet will support conventional casino games over time, which will operate in a decentralized manner. 
DezBet will also host a variety of slots, table games, lotteries, and similar games. The main focus will be
on the games that are already popular, developing a handful of own DezBet games as well, in order to attract 
players who are looking for something new and unique. Note that because we are taking on none of 
the risk associated with the bets, there is never any possibility that DezBet will encounter liquidity 
problems. We are not taking any of the funds that become winnings for the players. Instead we connect 
players P2P meaning they act as their own bank generating on demand liquidity. To get started, players 
simply initiate a game on the blockchain. They make an initial request to the network, while the game 
initiates the functions required, such as the verifiable randomness function (VRF). While processing the 
game, DezBet will refer to a data feed known as an oracle. This is the trusted source of information 
that communicates the outcome of the game so that the smart contracts can be executed based on 
the external conditions of the game. 

|||[!badge variant="primary" text="1-versus-All - 1vN"]
This is a medium paced game. The chance of winning is 1 /x, X E[1, 100], and the winnings will total 
y · [x], y being the bet amount minus fees. Each player will select a number between 1 and 100 
(each number available for selection only once), and after there are 100 players in the game or timer runs
out, an algorithm chooses the winning number at random, from the numbers that the players have
selected.
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

