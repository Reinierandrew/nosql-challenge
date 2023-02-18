I was  contracted by the editors of the food magazine __Eat Safe, Love__ to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

In the notebook NoSQL_setup I created the mongo database, added a new restaurant they sent to me, changed some datatypes and deleted the Dover documents as they were not interested in Dover.

In notebook NoSQL_analysis I did some analyses on the database to find the places with a hygiene score of 20 (41 places), the London places with a rating of 4 and 5 (33).

__NOTE:__ the answer given was 34 which I believe is wrong as of the 37 places there are 2 places with a rating of 2, one with a rating of 3 and 1 "Awaiting Inspection"

I found the top 5 establishments with rating value of '5' and lowest hygiene score, nearest to the restaurant added, "Penang Flavours"?

__NOTE:__ I removed an isntance of 'hygiene score' of NONE as that is technically not a score.

Finally I found the number of places in each Local Authority with a hygiene score of 0.
