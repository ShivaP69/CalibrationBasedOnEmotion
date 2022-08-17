# CalibrationBasedOnEmotion
This code is implemetation of folowing paper: پیشنهادات کالیبره شده براساس احساسات استخراج شده از متون مرتبط با آیتم ها

A very brief summary of the work done in the mentioned paper, which is released In Farsi at the IKT2021 International Conference.

Recommender systems are used to create items for users based on their interests. Based on user history, his interests are identiﬁed in

these systems, and suggestions are proposed. The goal of recommender systems usually is maximising accuracy in predicting

the right user's interest. However, in recent years the issue of fairness of the results of the proposed list has received much attention.

Calibration can produce fair outcomes proposed to the user. Its purpose is to cover the full range of user interests. In all articles

related to the calibration of recommender systems, calibration has been done by genre. In this article, the idea of using emotional

distribution extracted from texts related to items is suggested as an alternative to genre distribution in order to calibrate suggestions to

the user. Although the proposed approach is post processing and does not depend on the recommender baseline model, we used a

deep collaborative model as our baseline model based on the better performance of this model in predicting the interest of the user. The

model was based on movielens data set and evaluated based on various criteria. The performance of the proposed model showed that

if the recommendations are calibrated based on emotions, the recall measure will increase signiﬁcantly compared to when we use the

genre for calibration. In addition, according to the new criteria used to measure calibration error, it also has a very small calibration error.
