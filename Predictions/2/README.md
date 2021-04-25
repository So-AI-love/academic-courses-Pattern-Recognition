
# This is for High Accuracy Tries on main Data with Above 98% correctness:

----------

1- For **so-so.csv** all around 400,000 inputs r2_score is around **0.998** ([colab page link](http://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict%20so-so-99.ipynb)):

[![enter image description here][1]][1]

2-For **so-so.csv** all around 10,000 Random data form 400,000 inputs r2_score is around **0.57** ([colab page link](http://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict%20so-so-57.ipynb)):

[![enter image description here][3]][3]

3- For the main 45 columns input data without the skewwness transform we have the r2_score as **0.9836** ([Colab Link](http://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict-o-local-main-skewness.ipynb)):

[![enter image description here][5]][5]

4- For the main 45 columns input data with the skewwness transform we have the r2_score as **0.9858** ([Colab Link](https://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict-no-local-main-no-skewness.ipynb)):

[![enter image description here][7]][7]

ToDo:

## Try use random train and test selection form the inputs.

Thanks.

  
  [1]: https://i.stack.imgur.com/BIfXx.png
  [2]: https://colab.research.google.com/github/So-AI-love/Test_NN/blob/main/Predictions/2/time_series_rnn_full_predict%20so-so-57.ipynb
  [3]: https://i.stack.imgur.com/y8pMI.png
  [4]: https://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict_99_Correct_main_data_local.ipynb#scrollTo=YvOC96GtJCww
  [5]: https://i.stack.imgur.com/XgGPS.png
  [6]: https://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/1/time_series_rnn_full_predict_97_Correct_main_data_local_skewness.ipynb#scrollTo=DXOSgrgtJF6V
  [7]: https://i.stack.imgur.com/00az1.png
