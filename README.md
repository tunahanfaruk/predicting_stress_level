# predicting_mental health

this model predicts your mental health

-------------------------------------------------------------------------------------------------------------

for example you type "ı a  fine"

it prints:
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 30ms/step
status_Anxiety: ❌ (0.00)
status_Bipolar: ❌ (0.00)
status_Depression: ❌ (0.00)
status_Normal: ✔️ (1.00)
status_Personality disorder: ❌ (0.00)
status_Stress: ❌ (0.00)
status_Suicidal: ❌ (0.00)

---------------------------------------------------------------------------------------------------------------

accuracy:
                             precision    recall  f1-score   support

             status_Anxiety       0.81      0.66      0.73       778
             status_Bipolar       0.70      0.65      0.67       575
          status_Depression       0.66      0.66      0.66      3081
              status_Normal       0.93      0.84      0.88      3270
status_Personality disorder       0.58      0.47      0.52       240
              status_Stress       0.50      0.52      0.51       534
            status_Suicidal       0.59      0.62      0.60      2131

                  micro avg       0.72      0.70      0.71     10609
                  macro avg       0.68      0.63      0.65     10609
               weighted avg       0.73      0.70      0.71     10609
                samples avg       0.69      0.70      0.69     10609
                
--------------------------------------------------------------------------------------------------------------

general accuracy:
332/332 ━━━━━━━━━━━━━━━━━━━━ 1s 3ms/step - accuracy: 0.7047 - loss: 0.6957
Test Loss: 0.6887
Test Accuracy: 0.7093

--------------------------------------------------------------------------------------------------------------

data link:
https://www.kaggle.com/datasets/szegeelim/mental-health
