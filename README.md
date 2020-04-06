# ML_Project_2020
Machine Learning Project 2020, Group 16: Vladimir Dmitriev, Alexander Shumilov, Veronika Zorina, Daria Gazizova, Elizaveta Noskova.

## "On scalable and efficient computation oflarge scale optimal transport"

Optimal transport is one of the popular methodsused in ML, e.g.  for domain adaptation or sam-ple generation. But due to the heavy computing load, this method is difficult to use everywhere. To solve this problem, the SPOT algorithm wasdescribed, the operation of which was tested inthis project. SPOT (Scalable Push-forward of Optimal Transport) is an implicit generative learning-based framework by which the optimal transport problem is casted into a minimax problem andthen is efficiently solved by primal dual stochastic gradient-type algorithms. In this work SPOT wastested on Gaussian distribution toy dataset andused for domain adaptation and image generation.

### Content:

1) SPOT.py - notebook for SPOT algorithm realization (to run it on GPU just try downloading it in '.py' format)
2) DASPOT.py - DASPOT algorithm realization 
3) 
4) pu.sh - example of input file to run experiments on cluster
5) Requirements.txt - python packages that required for results recreation
6) Experiment_DASPOT - folder with some results for DASPOT that did not make it to the final version of report

Full SPOT & DASPOT experiment results are too big for github, so we decided to upload zip archive here - : . Please, contact alexander.shumilov@skoltech.ru if link will brake or expire.
