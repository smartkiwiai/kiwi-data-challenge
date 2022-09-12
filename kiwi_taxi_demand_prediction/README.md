# Kiwi Taxi Demand Prediction
## Problem Definition

Kiwi is a 8x8 grid shaped city. We have recorded the number of times people call taxis from each grid from 2023-04-01 to 2026-03-31. Our goal is to predict the number of taxi calls for each grid for each day in the next 2 months (2026-04-01 to 2026-05-31, inclusive).

As *Kiwi* is an imaginary city, the data is synthetic (obtained through a simulation). It is provided in sparse format.

We have data for all days in the 3-year period except for one time when our app was broken where we couldn’t collect any data. The app was broken between 2024-04-10 and 2024-04-23.

## Data Format

### train.csv

**x:** x coordinate of the grid, an `integer` between 0 and 7.

**y:** y coordinate of the grid, `integer` between 0 and 7.

**date:** date in `yyyy-mm-dd` format.

**count:** this is our target, an `integer` indicating the number of times people call taxis.

## Evaluation

We expect you to send us a `submission.csv` as the same format as `train.csv`. We also want you to provide the code which generates your `submission.csv` file. The target `count` should be an `integer`. Evaluation metric used will be `MAE`. You will be evaluated based on your score and your code quality. Please don’t hesitate to provide any code or any of your findings for all the experiments you did.

## Disclaimer

this challenge comes with a twist. Instead of awarding prizes to the top finishers on the leaderboard, this playground competition was created to reward collaboration and collective learning.

We are encouraging you (with cash prizes!) to publish additional training data that other participants can use for their predictions. We also have designated bi-weekly and final prizes to reward authors of kernels that are particularly insightful or valuable to the community.
