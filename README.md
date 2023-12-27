# TTF-Estimator
There are two Matlab apps that estimates time to task failure (TTF) based on inputs using 5-min (knee extensions) or 3-min (cycling) all-out tests.

TTF_estimation_KneeExtension.mlapp estimates TTF based on end-test torque (ET) and torque-impulse above ET (both values acquired through 5-min all-out test introduced by Burnley et al., 2009). 
  - "Contraction (s)" and "Rest (s)" refers to the duty cycle durations of the experimental task (most common is 3s contraction to 2s rest).

TTF_estimation_cycling.mlapp estimates TTF based on end-test power (EP) and work above EP (both values acquired through 3-min all-out cycling test introduced by Vanhatalo et al., 2007).

Fill out all the numerical fields, then press "Estimate TTF".
