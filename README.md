# CCFA_Exam
Repository to hold code for the final exam of CCFA-661. The prompt is to run various experiments to get best results on the Amazon Review Dataset. We are using the following for the experiments:
- [XGBoost with Bag of Words](Final_Exam_1.ipynb)
- [XGBoost with Word2Vec](Final_Exam_2.ipynb)
- [Neural Network with Bag of Words](Final_Exam_3.ipynb)
- [Neural Network with Word2Vec](Final_Exam_4.ipynb)
## Results
Following are the results for the models, a detailed report can be accessed [here](Final_Exam.pdf)
### XGBoost with Bag of Words
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.88      | 0.08   | 0.15     |
| 1     | 0.77      | 1.00   | 0.87     |
### XGBoost with Word2Vec
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.78      | 0.65   | 0.71     |
| 1     | 0.89      | 0.94   | 0.92     |
### Neural Network with Bag of Words
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0.0   | 0.77      | 0.75   | 0.76     |
| 1.0   | 0.92      | 0.93   | 0.93     |
### Neural Network with Word2Vec
| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0.0   | 0.76      | 0.71   | 0.73     |
| 1.0   | 0.91      | 0.93   | 0.92     |
