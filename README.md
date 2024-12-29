# Workshop slide 2024-02-29

## Content Table

21 pages

- introduction
  - research question, background, story
  - works
  - main finding
  - contributions
- data
- model and estimation
  - timing
  - demand
    - private information: health perception
    - hetrogeneity in preferences
    - utility function
    - plan choice probability
  - supply
    - plan design problem
- counterfactual
  - equal-profit: no selection effect, all consumer has the same profit


## Feedback

- relationship between health perception and actual spending (mc)
  - show that health perception is better than actual spending, could use the sigma of both to compare
- the parameter set $vertheta$ should be more clear
- the MLE estimation formula should not include the weights in the weighted log likelihood
- the risk aversion could get involved in the preference of generosity, the interpretation of it could be mixed
- explain why people get more utility from the HMO than PPO, and the cost
- what is your contribution to the literature, other than just apply the BLP to MA market
- explain the negative of firm fixed effect: more bargaining power/more efficient
- the generosity measure: expected OOP, conditonal on one health condition, make it more clear
- speak faster
- do not spending too much time on the detail of toy model.
- FAQ: why gov allow the plan design which could lead to the selection problem.

## Thoughts

- introduction and motivation
  - managed competation in healthcare insurance: firm offer insurance, consumer choose plan, gov subsidize firm by pay capitation (compare to fee-for-service: gov offer insurance)
  - 'cream-skimming', firm select the healthy
  - to solve this, gov introduce risk adjustment, so that high-risk is compensated
  - however, predictive-based risk adjustment on the group level cannot fully solve 'cream-skimming' incentive
  - simplied case: healthy, sick (unobs), young, old (obs)
  - the risk adjustment on the group level (young/old) will overestimate the spending of healthy and underestimate the spending of unhealthy
  - firm wants to attract the healthy (not necessary the young)
  - if the consumer has more information about their health than the gov, the firm could still cream-skimming by encourage the consumer's self selection
  - this paper:
    - research question: how the plan strategic design affect the consumer's self selection, and what is the welfare implication of this, in the market of MA
    - mathod: build a structural model with private information to estimate the demand and supply, and use the counterfactual to evaluate the welfare
    - result: the selection problem leads to the inefficiency of the market, and the welfare implication is significant
    - contribution
- date: individual level, plan level, county level
- model: time, demand, supply
- result: demand, supply, counterfactual

feedback:
- the contributions: add the literature (cite some benchmark) and the new things you do
- counterfactual: add more about the idea of the new risk adjustment from the theorical paper.
- maybe show the gragph of previous risk adjustment and the new risk adjustment
- stat description of the data
- walfare changes: loser and winner
- color the main focus parameters
- hoteling problem of supply, hard to get the results (stern),
- add more about the estimation of demand and foc of supply, so audience could understand the result better
- add the first page on basic description of the Meidcare, and MA
- there are some winer and loser in the counterfactual, could be better to show who they are.
- the result should be after the model, not in the model (demand modell, supply model, demand estimation, supply estimation, counterfactual)

todo:

