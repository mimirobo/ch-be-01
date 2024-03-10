# Music Contest Platform - Code Challenge


## Problem Statement:

A music streaming platform specializing in music contests is hosting a contest for singers.
Each singer can submit multiple songs to the contest.

The platform features a leaderboard page that ranks singers based on their scores, 
which are calculated using the formula:

```Singer's Score = Sum ( (0.1 * listens_count) + (1.50 * likes_count) )```

- *listens_count*: the number of times when the music is played by a user

- *likes_count*: the number of times when a user hit the like button for the music

**Example:**
Consider a music contest where `Singer A` has submitted three songs with the following statistics:
- Song 1: # of listens = 100, # of likes = 50
- Song 2: # of listens = 80, # of likes = 40
- Song 3: # of listens = 120, # of likes = 60

Singer A's total score would be calculated as follows:

```Singer A's Score = (0.1 * 100 + 1.50 * 50) + (0.1 * 80 + 1.50 * 40) + (0.1 * 120 + 1.50 * 60) = 255```


**Propose solutions to:**
1. Display the leaderboard upon request 
2. and identify the name of a single song that contributes the most to each singer's score.

The leaderboard's output example:
1. Singer A, hot song: Song 3
2. Singer B, hot song: Song X
3. ...


Constraints:
- 2 < # of Singers < 100
- 0 < # of songs for each singer < 10
- 0 < # of Listens < 1K
- 0 < # of Views < 1K
