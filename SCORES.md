# Word

english_0
100%
5/5 [01:25<00:00, 20.71s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.90      0.97      0.93     10771
    offensive       0.93      0.82      0.87      6423

     accuracy                           0.91     17194
    macro_avg       0.92      0.89      0.90     17194
 weighted_avg       0.91      0.91      0.91     17194

======================
LR
               precision    recall  f1-score   support

not_offensive       0.93      0.97      0.95     10771
    offensive       0.95      0.88      0.92      6423

     accuracy                           0.94     17194
    macro_avg       0.94      0.93      0.93     17194
 weighted_avg       0.94      0.94      0.94     17194

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.90      0.98      0.94     10771
    offensive       0.96      0.82      0.88      6423

     accuracy                           0.92     17194
    macro_avg       0.93      0.90      0.91     17194
 weighted_avg       0.92      0.92      0.92     17194

======================
RF
               precision    recall  f1-score   support

not_offensive       0.94      0.97      0.95     10771
    offensive       0.95      0.89      0.92      6423

     accuracy                           0.94     17194
    macro_avg       0.94      0.93      0.93     17194
 weighted_avg       0.94      0.94      0.94     17194

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.94      0.97      0.95     10771
    offensive       0.94      0.89      0.91      6423

     accuracy                           0.94     17194
    macro_avg       0.94      0.93      0.93     17194
 weighted_avg       0.94      0.94      0.94     17194

======================



english_1
100%
5/5 [00:15<00:00, 3.62s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.93      0.31      0.46       833
    offensive       0.88      1.00      0.93      4124

     accuracy                           0.88      4957
    macro_avg       0.90      0.65      0.70      4957
 weighted_avg       0.89      0.88      0.85      4957

======================
LR
               precision    recall  f1-score   support

not_offensive       0.90      0.73      0.81       833
    offensive       0.95      0.98      0.97      4124

     accuracy                           0.94      4957
    macro_avg       0.92      0.86      0.89      4957
 weighted_avg       0.94      0.94      0.94      4957

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.90      0.53      0.67       833
    offensive       0.91      0.99      0.95      4124

     accuracy                           0.91      4957
    macro_avg       0.91      0.76      0.81      4957
 weighted_avg       0.91      0.91      0.90      4957

======================
RF
               precision    recall  f1-score   support

not_offensive       0.88      0.64      0.74       833
    offensive       0.93      0.98      0.96      4124

     accuracy                           0.92      4957
    macro_avg       0.91      0.81      0.85      4957
 weighted_avg       0.92      0.92      0.92      4957

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.83      0.76      0.79       833
    offensive       0.95      0.97      0.96      4124

     accuracy                           0.93      4957
    macro_avg       0.89      0.87      0.88      4957
 weighted_avg       0.93      0.93      0.93      4957

======================

CNN_word
               precision    recall  f1-score   support

not_offensive       0.80      0.87      0.83       833
    offensive       0.97      0.96      0.96      4124

     accuracy                           0.94      4957
    macro_avg       0.89      0.91      0.90      4957
 weighted_avg       0.94      0.94      0.94      4957

CNN_char
               precision    recall  f1-score   support

not_offensive       0.61      0.66      0.63       833
    offensive       0.93      0.92      0.92      4124

     accuracy                           0.87      4957
    macro_avg       0.77      0.79      0.78      4957
 weighted_avg       0.88      0.87      0.87      4957

CNN_hybrid
               precision    recall  f1-score   support

not_offensive       0.82      0.77      0.79       833
    offensive       0.95      0.97      0.96      4124

     accuracy                           0.93      4957
    macro_avg       0.89      0.87      0.88      4957
 weighted_avg       0.93      0.93      0.93      4957
CNN_word_embedding
               precision    recall  f1-score   support

not_offensive       0.77      0.91      0.83       833
    offensive       0.98      0.94      0.96      4124

     accuracy                           0.94      4957
    macro_avg       0.87      0.93      0.90      4957
 weighted_avg       0.94      0.94      0.94      4957
CNN_char_embedding
               precision    recall  f1-score   support

not_offensive       0.65      0.57      0.61       833
    offensive       0.92      0.94      0.93      4124

     accuracy                           0.88      4957
    macro_avg       0.78      0.75      0.77      4957
 weighted_avg       0.87      0.88      0.87      4957
CNN_hybird_embedding
               precision    recall  f1-score   support

not_offensive       0.75      0.74      0.75       833
    offensive       0.95      0.95      0.95      4124

     accuracy                           0.92      4957
    macro_avg       0.85      0.84      0.85      4957
 weighted_avg       0.91      0.92      0.91      4957
Ensemble_All
               precision    recall  f1-score   support

not_offensive       0.88      0.75      0.81       833
    offensive       0.95      0.98      0.97      4124

     accuracy                           0.94      4957
    macro_avg       0.92      0.86      0.89      4957
 weighted_avg       0.94      0.94      0.94      4957
Ensemble_Word
               precision    recall  f1-score   support

not_offensive       0.87      0.70      0.78       833
    offensive       0.94      0.98      0.96      4124

     accuracy                           0.93      4957
    macro_avg       0.91      0.84      0.87      4957
 weighted_avg       0.93      0.93      0.93      4957
Ensemble_char
               precision    recall  f1-score   support

not_offensive       0.89      0.51      0.65       833
    offensive       0.91      0.99      0.95      4124

     accuracy                           0.91      4957
    macro_avg       0.90      0.75      0.80      4957
 weighted_avg       0.91      0.91      0.90      4957



filipino
100%
5/5 [00:19<00:00, 4.66s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.80      0.75      0.78      2596
    offensive       0.73      0.78      0.76      2251

     accuracy                           0.77      4847
    macro_avg       0.77      0.77      0.77      4847
 weighted_avg       0.77      0.77      0.77      4847

======================
LR
               precision    recall  f1-score   support

not_offensive       0.82      0.86      0.84      2596
    offensive       0.83      0.79      0.81      2251

     accuracy                           0.83      4847
    macro_avg       0.83      0.82      0.82      4847
 weighted_avg       0.83      0.83      0.82      4847

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.79      0.83      0.81      2596
    offensive       0.79      0.75      0.77      2251

     accuracy                           0.79      4847
    macro_avg       0.79      0.79      0.79      4847
 weighted_avg       0.79      0.79      0.79      4847

======================
RF
               precision    recall  f1-score   support

not_offensive       0.91      0.91      0.91      2596
    offensive       0.89      0.89      0.89      2251

     accuracy                           0.90      4847
    macro_avg       0.90      0.90      0.90      4847
 weighted_avg       0.90      0.90      0.90      4847

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.74      0.80      0.77      2596
    offensive       0.75      0.67      0.71      2251

     accuracy                           0.74      4847
    macro_avg       0.74      0.74      0.74      4847
 weighted_avg       0.74      0.74      0.74      4847

======================

CNN_word
               precision    recall  f1-score   support

not_offensive       0.90      0.84      0.87      2596
    offensive       0.83      0.89      0.86      2251

     accuracy                           0.86      4847
    macro_avg       0.86      0.87      0.86      4847
 weighted_avg       0.87      0.86      0.86      4847

CNN_char
               precision    recall  f1-score   support

not_offensive       0.70      0.73      0.71      2596
    offensive       0.67      0.63      0.65      2251

     accuracy                           0.68      4847
    macro_avg       0.68      0.68      0.68      4847
 weighted_avg       0.68      0.68      0.68      4847
CNN_hybrid
               precision    recall  f1-score   support

not_offensive       0.86      0.93      0.89      2596
    offensive       0.91      0.82      0.86      2251

     accuracy                           0.88      4847
    macro_avg       0.88      0.87      0.88      4847
 weighted_avg       0.88      0.88      0.88      4847
Ensemble_All
               precision    recall  f1-score   support

not_offensive       0.93      0.87      0.90      2596
    offensive       0.86      0.92      0.89      2251

     accuracy                           0.89      4847
    macro_avg       0.89      0.89      0.89      4847
 weighted_avg       0.89      0.89      0.89      4847
Ensemble_Word
               precision    recall  f1-score   support

not_offensive       0.94      0.81      0.87      2596
    offensive       0.81      0.94      0.87      2251

     accuracy                           0.87      4847
    macro_avg       0.87      0.87      0.87      4847
 weighted_avg       0.88      0.87      0.87      4847
Ensemble_char
               precision    recall  f1-score   support

not_offensive       0.84      0.83      0.83      2596
    offensive       0.81      0.81      0.81      2251

     accuracy                           0.82      4847
    macro_avg       0.82      0.82      0.82      4847
 weighted_avg       0.82      0.82      0.82      4847


chinese
100%
5/5 [00:10<00:00, 2.29s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.71      0.97      0.82      1175
    offensive       0.79      0.25      0.38       619

     accuracy                           0.72      1794
    macro_avg       0.75      0.61      0.60      1794
 weighted_avg       0.74      0.72      0.67      1794

======================
LR
               precision    recall  f1-score   support

not_offensive       0.79      0.90      0.84      1175
    offensive       0.74      0.55      0.63       619

     accuracy                           0.78      1794
    macro_avg       0.76      0.72      0.73      1794
 weighted_avg       0.77      0.78      0.77      1794

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.79      0.90      0.84      1175
    offensive       0.74      0.54      0.63       619

     accuracy                           0.78      1794
    macro_avg       0.77      0.72      0.73      1794
 weighted_avg       0.77      0.78      0.77      1794

======================
RF
               precision    recall  f1-score   support

not_offensive       0.78      0.87      0.82      1175
    offensive       0.68      0.54      0.60       619

     accuracy                           0.75      1794
    macro_avg       0.73      0.70      0.71      1794
 weighted_avg       0.75      0.75      0.75      1794

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.77      0.86      0.81      1175
    offensive       0.65      0.51      0.57       619

     accuracy                           0.74      1794
    macro_avg       0.71      0.68      0.69      1794
 weighted_avg       0.73      0.74      0.73      1794

======================

CNN_word
               precision    recall  f1-score   support

not_offensive       0.80      0.71      0.75      1175
    offensive       0.54      0.65      0.59       619

     accuracy                           0.69      1794
    macro_avg       0.67      0.68      0.67      1794
 weighted_avg       0.71      0.69      0.70      1794
CNN_char
               precision    recall  f1-score   support

not_offensive       0.68      0.92      0.78      1175
    offensive       0.55      0.19      0.28       619

     accuracy                           0.67      1794
    macro_avg       0.62      0.55      0.53      1794
 weighted_avg       0.64      0.67      0.61      1794
CNN_hybrid
               precision    recall  f1-score   support

not_offensive       0.79      0.75      0.77      1175
    offensive       0.56      0.61      0.59       619

     accuracy                           0.70      1794
    macro_avg       0.67      0.68      0.68      1794
 weighted_avg       0.71      0.70      0.70      1794

CNN_word_embedding
              precision    recall  f1-score   support

not_offensive       0.77      0.82      0.80      1175
    offensive       0.62      0.54      0.58       619

     accuracy                           0.73      1794
    macro_avg       0.70      0.68      0.69      1794
 weighted_avg       0.72      0.73      0.72      1794
CNN_char_embedding
               precision    recall  f1-score   support

not_offensive       0.69      0.85      0.76      1175
    offensive       0.49      0.27      0.35       619

     accuracy                           0.65      1794
    macro_avg       0.59      0.56      0.56      1794
 weighted_avg       0.62      0.65      0.62      1794
CNN_hybird_embedding
               precision    recall  f1-score   support

not_offensive       0.78      0.81      0.79      1175
    offensive       0.61      0.55      0.58       619

     accuracy                           0.72      1794
    macro_avg       0.69      0.68      0.69      1794
 weighted_avg       0.72      0.72      0.72      1794
Ensemble_All
               precision    recall  f1-score   support

not_offensive       0.80      0.82      0.81      1175
    offensive       0.64      0.61      0.63       619

     accuracy                           0.75      1794
    macro_avg       0.72      0.72      0.72      1794
 weighted_avg       0.74      0.75      0.75      1794

Ensemble_Word
               precision    recall  f1-score   support

not_offensive       0.78      0.82      0.80      1175
    offensive       0.63      0.57      0.60       619

     accuracy                           0.74      1794
    macro_avg       0.71      0.70      0.70      1794
 weighted_avg       0.73      0.74      0.73      1794
Ensemble_char
               precision    recall  f1-score   support

not_offensive       0.75      0.95      0.84      1175
    offensive       0.81      0.41      0.55       619

     accuracy                           0.76      1794
    macro_avg       0.78      0.68      0.69      1794
 weighted_avg       0.77      0.76      0.74      1794

korean
100%
5/5 [00:07<00:00, 1.64s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.76      0.44      0.55       729
    offensive       0.67      0.89      0.77       945

     accuracy                           0.69      1674
    macro_avg       0.71      0.66      0.66      1674
 weighted_avg       0.71      0.69      0.67      1674

======================
LR
               precision    recall  f1-score   support

not_offensive       0.67      0.52      0.58       729
    offensive       0.68      0.80      0.74       945

     accuracy                           0.68      1674
    macro_avg       0.68      0.66      0.66      1674
 weighted_avg       0.68      0.68      0.67      1674

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.67      0.51      0.58       729
    offensive       0.68      0.81      0.74       945

     accuracy                           0.68      1674
    macro_avg       0.68      0.66      0.66      1674
 weighted_avg       0.68      0.68      0.67      1674

======================
RF
               precision    recall  f1-score   support

not_offensive       0.59      0.56      0.57       729
    offensive       0.67      0.70      0.69       945

     accuracy                           0.64      1674
    macro_avg       0.63      0.63      0.63      1674
 weighted_avg       0.64      0.64      0.64      1674

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.65      0.33      0.44       729
    offensive       0.62      0.86      0.72       945

     accuracy                           0.63      1674
    macro_avg       0.64      0.60      0.58      1674
 weighted_avg       0.63      0.63      0.60      1674

======================

CNN_word
               precision    recall  f1-score   support

not_offensive       0.54      0.69      0.61       729
    offensive       0.70      0.55      0.62       945

     accuracy                           0.61      1674
    macro_avg       0.62      0.62      0.61      1674
 weighted_avg       0.63      0.61      0.61      1674
CNN_char
               precision    recall  f1-score   support

not_offensive       0.58      0.12      0.20       729
    offensive       0.58      0.93      0.71       945

     accuracy                           0.58      1674
    macro_avg       0.58      0.53      0.46      1674
 weighted_avg       0.58      0.58      0.49      1674
CNN_hybrid
               precision    recall  f1-score   support

not_offensive       0.56      0.62      0.59       729
    offensive       0.68      0.63      0.65       945

     accuracy                           0.63      1674
    macro_avg       0.62      0.62      0.62      1674
 weighted_avg       0.63      0.63      0.63      1674
CNN_word_embedding
               precision    recall  f1-score   support

not_offensive       0.61      0.53      0.57       729
    offensive       0.67      0.74      0.71       945

     accuracy                           0.65      1674
    macro_avg       0.64      0.64      0.64      1674
 weighted_avg       0.65      0.65      0.65      1674
CNN_char_embedding
               precision    recall  f1-score   support

not_offensive       0.57      0.07      0.12       729
    offensive       0.57      0.96      0.72       945

     accuracy                           0.57      1674
    macro_avg       0.57      0.51      0.42      1674
 weighted_avg       0.57      0.57      0.46      1674
CNN_hybird_embedding
               precision    recall  f1-score   support

not_offensive       0.60      0.58      0.59       729
    offensive       0.68      0.71      0.69       945

     accuracy                           0.65      1674
    macro_avg       0.64      0.64      0.64      1674
 weighted_avg       0.65      0.65      0.65      1674
Ensemble_All
               precision    recall  f1-score   support

not_offensive       0.60      0.71      0.65       729
    offensive       0.74      0.63      0.68       945

     accuracy                           0.67      1674
    macro_avg       0.67      0.67      0.67      1674
 weighted_avg       0.68      0.67      0.67      1674
Ensemble_Word
               precision    recall  f1-score   support

not_offensive       0.63      0.68      0.65       729
    offensive       0.74      0.69      0.71       945

     accuracy                           0.69      1674
    macro_avg       0.68      0.69      0.68      1674
 weighted_avg       0.69      0.69      0.69      1674
Ensemble_char
               precision    recall  f1-score   support

not_offensive       0.82      0.49      0.61       729
    offensive       0.70      0.92      0.79       945

     accuracy                           0.73      1674
    macro_avg       0.76      0.70      0.70      1674
 weighted_avg       0.75      0.73      0.71      1674

# Character

english_0
100%
5/5 [04:46<00:00, 80.37s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.87      0.97      0.91     10771
    offensive       0.93      0.76      0.83      6423

     accuracy                           0.89     17194
    macro_avg       0.90      0.86      0.87     17194
 weighted_avg       0.89      0.89      0.88     17194

======================

LR
               precision    recall  f1-score   support

not_offensive       0.93      0.97      0.95     10771
    offensive       0.95      0.87      0.91      6423

     accuracy                           0.93     17194
    macro_avg       0.94      0.92      0.93     17194
 weighted_avg       0.94      0.93      0.93     17194

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.90      0.98      0.94     10771
    offensive       0.96      0.81      0.88      6423

     accuracy                           0.92     17194
    macro_avg       0.93      0.90      0.91     17194
 weighted_avg       0.92      0.92      0.92     17194

======================
RF
               precision    recall  f1-score   support

not_offensive       0.91      0.98      0.94     10771
    offensive       0.96      0.83      0.89      6423

     accuracy                           0.92     17194
    macro_avg       0.93      0.90      0.92     17194
 weighted_avg       0.93      0.92      0.92     17194

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.93      0.96      0.95     10771
    offensive       0.93      0.88      0.91      6423

     accuracy                           0.93     17194
    macro_avg       0.93      0.92      0.93     17194
 weighted_avg       0.93      0.93      0.93     17194

======================
english_1
100%
5/5 [00:38<00:00, 11.44s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.91      0.16      0.27       833
    offensive       0.85      1.00      0.92      4124

     accuracy                           0.86      4957
    macro_avg       0.88      0.58      0.59      4957
 weighted_avg       0.86      0.86      0.81      4957

======================

LR
               precision    recall  f1-score   support

not_offensive       0.85      0.76      0.81       833
    offensive       0.95      0.97      0.96      4124

     accuracy                           0.94      4957
    macro_avg       0.90      0.87      0.88      4957
 weighted_avg       0.94      0.94      0.94      4957

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.86      0.63      0.73       833
    offensive       0.93      0.98      0.95      4124

     accuracy                           0.92      4957
    macro_avg       0.90      0.81      0.84      4957
 weighted_avg       0.92      0.92      0.92      4957

======================
RF
               precision    recall  f1-score   support

not_offensive       0.89      0.59      0.71       833
    offensive       0.92      0.99      0.95      4124

     accuracy                           0.92      4957
    macro_avg       0.91      0.79      0.83      4957
 weighted_avg       0.92      0.92      0.91      4957

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.83      0.78      0.81       833
    offensive       0.96      0.97      0.96      4124

     accuracy                           0.94      4957
    macro_avg       0.89      0.87      0.88      4957
 weighted_avg       0.94      0.94      0.94      4957

======================
filipino
100%
5/5 [00:51<00:00, 14.63s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.73      0.71      0.72      2596
    offensive       0.68      0.70      0.69      2251

     accuracy                           0.71      4847
    macro_avg       0.71      0.71      0.71      4847
 weighted_avg       0.71      0.71      0.71      4847

======================
/Users/rehanahmed/miniforge3/envs/test/lib/python3.8/site-packages/sklearn/linear_model/_logistic.py:814: ConvergenceWarning: lbfgs failed to converge (status=1):
STOP: TOTAL NO. of ITERATIONS REACHED LIMIT.

Increase the number of iterations (max_iter) or scale the data as shown in:
    https://scikit-learn.org/stable/modules/preprocessing.html
Please also refer to the documentation for alternative solver options:
    https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression
  n_iter_i = _check_optimize_result(
LR
               precision    recall  f1-score   support

not_offensive       0.80      0.83      0.81      2596
    offensive       0.80      0.76      0.77      2251

     accuracy                           0.80      4847
    macro_avg       0.80      0.79      0.79      4847
 weighted_avg       0.80      0.80      0.80      4847

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.76      0.83      0.79      2596
    offensive       0.78      0.69      0.73      2251

     accuracy                           0.77      4847
    macro_avg       0.77      0.76      0.76      4847
 weighted_avg       0.77      0.77      0.76      4847

======================
RF
               precision    recall  f1-score   support

not_offensive       0.91      0.90      0.90      2596
    offensive       0.88      0.89      0.89      2251

     accuracy                           0.90      4847
    macro_avg       0.89      0.90      0.89      4847
 weighted_avg       0.90      0.90      0.90      4847

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.76      0.79      0.77      2596
    offensive       0.74      0.71      0.73      2251

     accuracy                           0.75      4847
    macro_avg       0.75      0.75      0.75      4847
 weighted_avg       0.75      0.75      0.75      4847

======================
chinese
100%
5/5 [00:22<00:00, 6.08s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.67      0.99      0.80      1175
    offensive       0.85      0.09      0.16       619

     accuracy                           0.68      1794
    macro_avg       0.76      0.54      0.48      1794
 weighted_avg       0.73      0.68      0.58      1794

======================
LR
               precision    recall  f1-score   support

not_offensive       0.80      0.91      0.85      1175
    offensive       0.77      0.57      0.65       619

     accuracy                           0.79      1794
    macro_avg       0.78      0.74      0.75      1794
 weighted_avg       0.79      0.79      0.78      1794

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.79      0.92      0.85      1175
    offensive       0.78      0.55      0.64       619

     accuracy                           0.79      1794
    macro_avg       0.79      0.73      0.75      1794
 weighted_avg       0.79      0.79      0.78      1794

======================
RF
               precision    recall  f1-score   support

not_offensive       0.80      0.91      0.85      1175
    offensive       0.76      0.57      0.65       619

     accuracy                           0.79      1794
    macro_avg       0.78      0.74      0.75      1794
 weighted_avg       0.79      0.79      0.78      1794

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.80      0.86      0.83      1175
    offensive       0.69      0.59      0.64       619

     accuracy                           0.77      1794
    macro_avg       0.75      0.73      0.73      1794
 weighted_avg       0.76      0.77      0.76      1794

======================
korean
100%
5/5 [00:15<00:00, 3.76s/it]
NB
               precision    recall  f1-score   support

not_offensive       0.89      0.33      0.48       729
    offensive       0.65      0.97      0.78       945

     accuracy                           0.69      1674
    macro_avg       0.77      0.65      0.63      1674
 weighted_avg       0.76      0.69      0.65      1674

======================
LR
               precision    recall  f1-score   support

not_offensive       0.76      0.61      0.67       729
    offensive       0.74      0.85      0.79       945

     accuracy                           0.74      1674
    macro_avg       0.75      0.73      0.73      1674
 weighted_avg       0.75      0.74      0.74      1674

======================
SVM
               precision    recall  f1-score   support

not_offensive       0.76      0.61      0.68       729
    offensive       0.74      0.85      0.79       945

     accuracy                           0.75      1674
    macro_avg       0.75      0.73      0.73      1674
 weighted_avg       0.75      0.75      0.74      1674

======================
RF
               precision    recall  f1-score   support

not_offensive       0.74      0.52      0.61       729
    offensive       0.70      0.86      0.77       945

     accuracy                           0.71      1674
    macro_avg       0.72      0.69      0.69      1674
 weighted_avg       0.72      0.71      0.70      1674

======================
GBT
               precision    recall  f1-score   support

not_offensive       0.68      0.62      0.65       729
    offensive       0.73      0.78      0.75       945

     accuracy                           0.71      1674
    macro_avg       0.71      0.70      0.70      1674
 weighted_avg       0.71      0.71      0.71      1674

======================