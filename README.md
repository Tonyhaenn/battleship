# Battleship w/ Stakes

Early idea for a crypto battleship game
zk-snark where each player registers their ships in a X-Y grid
Players take turns? 
- How async / sync does this need to be? Could someone play all their moves before the other play plays?
- How to make sure the other player actually submits their moves?
-- Penalty for not playing?

Each user mints an NFT(?) for their battleship plan?

How to pair users?
- Totally async; no interaction
- Have a user post an NFT of the board & stake an amount of ETH
- Other users try to guess the positions of the ships on the board:
-- Each guess costs a small amount of ETH
-- Each miss, forfeits the guesser's ETH and grows the amount of ETH on the board
-- Each hit, gains the 2x the guesser's ETH?

Staked ETH on the board generates yield for the board owner?
When can the board owner withdraw the ETH?
- At any point? Boards with 0 ETH won't get any guessing?
- Only if someone hasn't submitted any guesses for NX blocks; need to make sure the board owner doesn't withdraw ETH while someone could be making a guesses?