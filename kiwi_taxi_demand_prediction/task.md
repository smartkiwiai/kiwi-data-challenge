# Kiwi - Taxi Demand Prediction
## Problem Definition

Kiwi is a 8x8 grid shaped city. And in this fun city, we have recorded the number of times people call taxis from each grid from `2023-04-01` to `2026-03-31`. Our goal is to predict the number of taxi calls for each grid for each day in the next 2 months `(2026-04-01 to 2026-05-31, inclusive)`.

As *Kiwi* is an imaginary city, the data is synthetic (obtained through a simulation). It is provided in sparse format.

We have data for all days in the 3-year period except for one time when our app was broken where we couldn’t collect any data. The app was broken between 2024-04-10 and 2024-04-23.

## Data

[train.csv](data/train.csv)

### Data Format

**x:** x coordinate of the grid, an `integer` between 0 and 7.

**y:** y coordinate of the grid, an `integer` between 0 and 7.

**date:** date in `yyyy-mm-dd` format.

**count:** this is our target, an `integer` indicating the number of times people call taxis.

## Submission

We expect you to submit your `submission.csv` and the code which generates your `submission.csv` file.

`submission.csv` should have the same format as `train.csv` and contain your predictions of the number of taxi calls for each grid in *Kiwi* for each day between `2026-04-01` and `2026-05-31`, inclusive. The target `count` should be an `integer`.

## Evaluation

`MAE` will be used as the evaluation metric. You will be evaluated based on your score and your code quality. 

### Disclaimer

This challenge comes with a twist. In order to improve your score, you will need to be able read the hidden stories the data is trying to tell you. Therefore; please don’t hesitate to provide any code or any of your findings for all the experiments you did.
