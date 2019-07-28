# diamonds
Kaggle Diamonds Competition

https://www.kaggle.com/c/datamad0619/overview

Competition description
The goal of this competition is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.). This is an academic competition created for the students of Iron Hack Data Analytics Bootcamp 0619.
￼
Features
* id: only for test & sample submission files, id for prediction sample identification
* price: price in USD
* carat: weight of the diamond
* cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
* color: diamond colour, from J (worst) to D (best)
* clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
* x: length in mm
* y: width in mm
* z: depth in mm
* depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
* table: width of top of diamond relative to widest point (43--95)

Evaluation
The evaluation metric chosen for this competition is the RMSE (Root Mean Squared Error):
* https://en.wikipedia.org/wiki/Root-mean-square_deviation

Submit results
* Submissions are limited to 5 times a day.
* The test set is divided into a public part (with which the public leaderboard is calculated, accessible during the competition) and another private part, with which the final positions are calculated, after the end of the competition.
* Predictions will be sent in the format indicated in the sample_submission.csv file in the data section.
