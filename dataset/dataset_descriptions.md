# Dataset Description

## Data format

_Each sample in the train and test set has the following information:_

- The `text` of a tweet
- A `keyword` from that tweet (although this may be blank)
- The `location` the tweet was sent from (may also be blank)


## Target to be predicted
_**I am predicting whether a given tweet is about a real disaster or not._** <br>
`1`: Is a real disaster <br>
`0`: Isn't a real disaster 

## Files
**train.csv** - the training set <br>
**test.csv** - the test set <br>
**sample_submission.csv** - a sample submission file in the correct format


## Columns
`id` - a unique identifier for each tweet <br>
`text` - the text of the tweet <br>
`location` - the location the tweet was sent from (maybe blank) <br>
`keyword` - a particular keyword from the tweet (maybe blank) <br>
`target` - in train.csv only, this denotes whether a tweet is about a real disaster (`1`) or not (`0`)