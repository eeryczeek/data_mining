# data_mining
**Eryk Ptaszyński 151950 and Filip Firkowski 151946**

Jupyter Notebook was used for this assignment. We used apriori to create association rules based on 4 attributes: genre, rating, release date and time of rating. We got a few interesting association rules this way for example:
| antecedents | consequences |
|--|--|
| Adventure, 1980-2000 | Action |
| Drama | High Score, 1980-2000 |
| Romance, Drama| Comedy|
| Children | Adventure, Animation |
| Adventure, Sci-Fi| Action |
*all rules present in the table have around 0.04 support*

We can see from those rules that some genres are popular in combinations with each other (Adventure, Action or Romance, Drama, Comedy). Rules also show that people like Dramas from 1980-2000. There are more rules present in rules.csv file. All rules pass treshold 0.024 support.
