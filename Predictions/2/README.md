
# This is for High Accuracy Tries on main Data with Above 98% correctness:

----------

1- For **so-so.csv** all around 400,000 inputs r2_score is around **0.998** ([colab page link][1]):

[![enter image description here][2]][2]

2-For **so-so.csv** all around 10,000 Random data form 400,000 inputs r2_score is around **0.57** ([colab page link][3]):

[![enter image description here][4]][4]

3- For the main 45 columns input data without the skewwness transform we have the r2_score as **0.9836** ([Colab Link][5]):

[![enter image description here][6]][6]

4- For the main 45 columns input data with the skewwness transform we have the r2_score as **0.9858** ([Colab Link][7]):

[![enter image description here][8]][8]

ToDo:

## Try use random train and test selection form the inputs.

Thanks.

  [1]: https://colab.research.google.com/github/So-AI-love/Test_NN/blob/main/Predictions/2/time_series_rnn_full_predict so-so-99.ipynb
  [2]: https://i.stack.imgur.com/BIfXx.png
  [3]: https://colab.research.google.com/github/So-AI-love/Test_NN/blob/main/Predictions/2/time_series_rnn_full_predict%20so-so-57.ipynb
  [4]: https://i.stack.imgur.com/y8pMI.png
  [5]: https://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/2/time_series_rnn_full_predict_99_Correct_main_data_local.ipynb#scrollTo=YvOC96GtJCww
  [6]: https://i.stack.imgur.com/XgGPS.png
  [7]: https://colab.research.google.com/github/So-AI-love/academic-courses-Pattern-Recognition/blob/main/Predictions/1/time_series_rnn_full_predict_97_Correct_main_data_local_skewness.ipynb#scrollTo=DXOSgrgtJF6V
  [8]: https://i.stack.imgur.com/00az1.png
