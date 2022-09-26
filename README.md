# Experiments with Overparameterized Models with Linear Regression


 <strong> Files:  </strong> 
 <br> 
4803_ProjectReport.pdf : Paper outlining the work I tried to replicate and the phenomenon in depth. 
 <br> 
  <br> 
Experiment 1: This experiment varies the number of samples and holds the number of dimensions constant. I replicated the experiment of Preetum Nakkiran in "More Data Can Hurt in Linear Regression: Sample-wise Double Descent." Here, I tried two settings for the number of dimensions/parameters: 1000 and 500. This did not make a difference, as the shape of the curve is a function of the ratio of <em>n</em> (the number of samples) to <em>p</em> (the number of parameters). 
 <br> 
 <br> 
Experiment 2: This experiment varies the number of dimensions (parameters) and holds the number of samples constant. I do this for 100, 500, and 1000 samples. Once, again the ratio of samples to dimensions is the important part here, so the curves don't look much different for each setting. I varied the signal-to-noise ratio (SNR) by changing the standard deviation of the data matrix, and this affects the shape of the curve.
 <br> 
 <br> 
Experiment 3: This experiment varies the number of dimensions (parameters) and holds the number of samples constant. I do this for 100, 500, and 1000 samples. Here, I misspecify the model by adding additional unnecessary samples and by leaving out significant features.
 <br> 
 <br> 
Experiment 4: This experiment varies the number of dimensions (parameters) and holds the number of samples constant. I do this for 100, 500, and 1000 samples. Here, I add a ridge regularization constant to view the effect of a regularization hyperparameter on the double descent curve.

