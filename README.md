# Predict-Future-Sales
This is a repo for the in-class Kaggle competition - [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)

The main model I used for this competition is **LightGBM**. 

There is a magic feature which helped me improve my model a lot: for each sample, I determineD whether it is an appeared shop_item pair or a totally new item. This feature helped me reduce RMSE by around 0.4. Finally I achieved a score RMSE 0.89500 in the public leaderboard, ranked 114/3167 (top 5%, updated 2019/5/19).
