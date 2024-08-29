# LEC_2024Summer_Winner_Prediction

以LEC英雄聯盟夏季賽進行分析

dataset: LEC_SummerPlayoffs_2024.csv
資料分析&建立預測模型: LEC2024summer_data_analysis.ipynb
勝率預測: LOL_winner_prediction.ipynb

LEC2024summer_data_analysis.ipynb
會根據比賽隊伍的狀況進行分析與統計，主要呈現隊伍的集殺數、中立資源控制、推塔等等
也包含版本常選角色分析，與常用角色的勝率分析

跑過LEC2024summer_data_analysis.ipynb之後，會建立兩個模型檔案
dl_on_lol(ac88).h5 - 深度學習模型
reg_on_lol(ac94) - 以2元回歸建立的模型

兩個模型建立之後，才可執行 LOL_winner_prediction.ipynb 進行勝率預測
在本案例的模型建立中，僅選用整體隊伍狀況當中較有代表性的feature進行預測
二元回歸模型 94%準確率
深度學習模型 88%準確率

