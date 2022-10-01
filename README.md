# Football_WithML

                                                                        Dataset that i used :
https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017


    Augmentation is a technique of raising the dataset with supplementary data, this data being images or text data which improves the algorithms’ performance. In case there aren’t enough data, a subset is artificially created using data augmentation techniques in order to improve the learning algorithms’ performance. 
                                                                        Process description
    After establishing the countries with the most victories, it has been decided that for a more precise and real increase of the dataset it should be artificially increased the dataset. There were implemented three types of artificial augmentations: 
The first 50 strongest countries will play away matches against the other countries, with the initial conditions: the strongest country will score between two to six goals and the weakest team wil score between zero and two goals. 
    The weakest fifty countries will play away against the other countries on the condition that the weak teams will score between 0 and 2 goals and the rest of the teams will score between two and six goals. 
The strongest fifty countries will play between them and it will result an equal score and they will score between zero and three goals. 
In case that after the augmentation process it has resulted the fact that the team that plays at home is the same with the team that plays away, the instances in question have been eliminated.

                                                                           ML Alghoritms and metrics

In this application we have used several classification algorithms such as: Random Forrest, Logistic Regression, Decision Tree, MLPC, etc. Also, to check the results and performance of the algorithms, we used some metrics such as: Confusion Matrix, Accuracy, F1-score, etc.
