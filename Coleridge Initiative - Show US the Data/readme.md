# Coleridge Initiative - Show US the Data competition

Competition site: https://www.kaggle.com/c/coleridgeinitiative-show-us-the-data/overview

Leaderboard: https://www.kaggle.com/c/coleridgeinitiative-show-us-the-data/leaderboard

The best submission scored 0.281 and ended up at 73rd position in the Private Leaderboard which was my first Silver medal.

<u> Best Solution: </u>

* Ensemble: Roberta model trained for 2 epoch and Bert base trained for 1 Epoch.
* Get common predictions from both the models (intersect the predictions).
* Remove predictions which are <= 2 words other than these ('adni', 'cccsl', 'ibtracs', 'slosh model')
* Along with the predictions add the String match of train_labels and extra labels shared by @mlconsult.
