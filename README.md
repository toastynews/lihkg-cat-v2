# lihkg-cat-v2
Scraped forum threads from LIHKG for categorization task. Formatted to use with BERT. Compared to v1, the number of categories increased from 18 to 20, and the number of training examples increased from 300 to 500. The minimum length for each example has also increased to make the task more solvable.

## Description
The files contain the concatenation of the subject and first post from forum threads in LIHKG. 
The labels are the categories. These are self-selected from the original poster of the thread.
Not all categories are present in the data set. The following are the ids and their corresponding
catgegories.

|category|台|
|-------:|--|
|1|吹水台|
|4|手機台|
|5|時事台|
|6|體育台|
|7|娛樂台|
|8|動漫台|
|9|Apps台|
|10|遊戲台|
|11|影視台|
|14|上班台|
|15|財經台|
|16|飲食台|
|17|旅遊台|
|18|學術台|
|21|音樂台|
|25|健康台|
|30|感情台|
|31|創意台|
|33|政事台|
|36|寵物台|
