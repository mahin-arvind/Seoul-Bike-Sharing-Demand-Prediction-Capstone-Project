# Bike-Sharing-Demand-Prediction-Capstone-Project
The bike sharing system, much like other transport services like public buses, trains and cabs
caters to a group with fluctuating demands affected by a variety of factors. Predicting this
demand can prove to be efficacious as it allows one to stock bikes in docking stations
according to user demands in advance. This allows bike sharing systems to become not just
an economical and healthy mode of transport, but also a reliable mode of transport.
In this project, the Seoul Bike Share Demand dataset was used to understand bike share use
trends, apply machine learning techniques to predict the number of bikes rented at any given
hour and provide reasonable explanations from the best predicting model to understand
factors affecting bike share demands.
The efficiency of standard machine learning techniques namely Linear Regression, Nearest
Neighbors, Decision Trees, Random Forests, Bagging, Boosting and Stacking were
implemented and their performances were compared.

  ● From Exploratory Data Analysis, we found that the bike rentals follow an hourly trend
where it hits the first peak in the morning and the highest peak next, in the evening. It
was also found that these trends are prominent only during weekdays and working
days, leading us to make a safe assumption that office-goers make a notable
contribution in bike sharing demand. In addition, seasons were observed to have a
notable effect on bike rentals, seeing high traffic during the summers and a significant
low during the winters.

  ● During model deployment, the above mentioned models were trained and evaluated.
The metrics used for evaluation were R2, RMSE and MAE. The top three models were
CatBoost, LightGBM and Random Forest. Their results were further optimized using
hyperparameter tuning. These three tuned models were used in a Stacking Ensemble.
The CatBoost and the Stacked Ensembled produced the highest R2 scores of 0.9369
and 0.9380, with a root mean squared error of 162.01 and 160.59 respectively.

  ● It was found that the top performing models made predictions based on the weather
and time of the day as high weightage was given to seasons, temperature recorded
and hour of the day. This confirms the trends observed during the exploratory data
analysis stage of the project.
