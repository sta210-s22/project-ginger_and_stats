# data

Place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## name of data file

### details.csv

Data of 21631 observations of 23 variables

|variable         |description | class |
|:----------------|:-----------|:------ |
|`num`             | Game number | double |
|`id`               | Game ID | double |
|`primary`          | Primary name of the game | character
|`yearpublished`    | Year published | double |
|`minplayers`       | Minimal number of players | double |
|`maxplayers`       | Maximal number of players | double |
|`playingtime`      | PLaying times (minutes) | double |
|`minplaytime`      | Minimal playing time (minutes) | double |
|`maxplaytime`      | Maximal playing time (minutes) | double |
|`boardgamecategory`| Category | character |
|`boardgamemechanic`| Mechanic | character |
|`boardgamefamily`  | Boardgame family | character |
|`boardgameexpansion`| Expansion| character |
|`boardgameimplementation`| Implementation | character |
|`boardgamedesigner`| Designer | character |
|`boardgameartist`  | Artist | character |
|`boardgamepublisher`| Publisher | character |
|`owned`| Number of people own the board game | double |
|`trading`! Number of people trading the board game | double |
|`wanting`| Number of people want to have the board game | double |
|`wishing`| Num wishing | double |

### ratings.csv

Data of 21831 observations and 10 variables. 

|variable      |class     |description |
|:-------------|:---------|:-----------|
|`num`           |double    | Game number |
|`id`            |double    | Game ID |
|`name`          |character | Game name |
|`year`          |double    | Game year |
|`rank`          |double    | Game rank |
|`average`       |double    | Average rating  |
|`bayes_average` |double    | Bayes average rating|
|`users_rated`   |double    | Users rated |
|`url`           |character | Game url |
|`thumbnail`     |character | Game thumbnail  |
