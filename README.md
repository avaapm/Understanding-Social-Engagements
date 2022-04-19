# Understanding Social Engagements
This repository contains the utilized dataset in the paper ["Understanding Social Engagements: A Comparative Analysis of User and Text Features in Twitter"](https://doi.org/10.1007/s13278-022-00872-1). This study mainly focuses on predicting whether given users engage with each other by reply, retweet, retweet with comment (quote) or like.

## Dataset

The dataset is composed of seven parts. Each .7z file contains corresponding .csv files. Each .csv file contain 2,000,000 instances except the last one (2,115,364). In total there are 14,115,364 instances. Description of columns of .csv files is as follows:

| Column Name  | Description |
| ------------- | ------------- |
| tweet_id  | Twitter ID of the tweet |
| engagee_id  | Twitter ID of the user who is owner of the tweet |
| engager_id  | Twitter ID of the user who is candidate to interact with the tweet |
| reply_timestamp | Timestamp of the reply if the engager user interacts with reply, else NaN |
| retweet_timestamp | Timestamp of the retweet if the engager user interacts with retweet, else NaN |
| retweet_with_comment_timestamp | Timestamp of the quote if the engager user interacts with quote, else NaN |
| like_timestamp | Timestamp of the like if the engager user interacts with like, else NaN |

It is possible that an engager user interacts with multiple ways (e.g., retweet and like at the same time).

## Citation
If you make use of this dataset, please cite following paper.

```bibtex
@article{toraman2022understanding,
  title={Understanding social engagements: A comparative analysis of user and text features in Twitter},
  author={Toraman, Cagri and {\c{S}}ahinu{\c{c}}, Furkan and Yilmaz, Eyup Halit and Akkaya, Ibrahim Batuhan},
  journal={Social network analysis and mining},
  volume={12},
  number={1},
  pages={1--16},
  year={2022},
  publisher={Springer}
}
```
