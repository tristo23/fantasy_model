fantasy_model
Predictive model for AFL Fantasy

Model 1

Outputs: 
- forecast for scores in future weeks (perhaps aiming at at a next 3rd average)
- net present total of forecast scores for the season

Need to determine:
- Discount rate/approach to discounting future scores - injury risk, uncertainty, position changes, opportunity cost (? already implicit?)
- Likely useful variables - Last 3 ave, last round, Opposition, venue, last 5 average, season average, position, last yr round score (same 3rd of season average), age, games played
- Do we need to train the model with years of scores? Is this a secondary Machine learning approach?

Steps

- Create dataset with possible variables
- Determine best R approach to forecast
- Determine whether machine learning (Keras) or other option for a machine learning approach. Dataset would be long with each score having a game number, age, position, etc..



Model 2

Outputs:
- Forecast for next season total and average scores
- Positional value ranking/quantification

Need to determine
- Likely useful variables - last season average, last 3rd season average, age, experience, position, average games played per year for the past few years
- 
