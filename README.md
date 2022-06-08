# r/place analysis

To run this code, you need to download the [Reddit r/place data](https://www.reddit.com/r/place/comments/txvk2d/rplace_datasets_april_fools_2022/?utm_source=share&utm_medium=web2x&context=3) and load it into an SQL database. I loaded the full dataset into a single table named `pixels` with column names equal to the names of the columns in the data files:

* `timestamp`: A timestamp with time zone
* `user_id`: text
* `pixel_color`: text
* `coordinate`: text

For more analysis, see my full post at [here](https://alanjern.github.io/post/an-analysis-of-reddits-r/place/).
