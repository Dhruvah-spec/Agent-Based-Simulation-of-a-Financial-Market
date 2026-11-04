## Objective
### This project aims to reproduce commonly observed stylized facts in financial markets - fat tails, volatility clustering and long memory - through an agent-based model featuring network based interactions between traders and investors who submit orders via a limit order book. The emergence of the stylized facts will be traced to the interactions between the trader/investor decision rules, network topology and limit order book mechanism.

## Model
### The model consists of a population of 'investors' and 'traders' sitiuated within a social network. Each agent holds either a 'buy' or 'sell' opinion. At every tick, agents update their opinion based on their decision rule. Traders copy the local majority of their neighbours' opinion while investors copy the global minority of the whole network.
