# Haggling Challenge
My submission for [hola! JS Challenge Summer 2018: Haggling](https://github.com/hola/challenge_haggling)


## Agent algorithm description
The agent accepts high offers (95%) or offers that were previously made by the agent. In the last round, the agent lowers the acceptance threshold to 50%. If the opponent has the last turn, the agent tries to find a past opponent's offers with 50% threshold.

## Counter offer strategy
The agent is trying to maximize the profit. Initially all items are considered "wanted" (even those with a zero price). Each round the agent is releasing least expensive items while taking items that the opponent doesn't want. The counter offer should be above 70%.
