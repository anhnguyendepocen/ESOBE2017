
### Machine Learning Models and Methods for Econometricians

by Mattias Villani, Division of Statistics and Machine Learning, Linköping University

---

##### 09.00-09.15 Coffee/Tea

---

#### 09.15-10.00 Gaussian Process Regression
Reading: 

- [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf)
- Chapters 2.1-2.5 in [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/chapters/RW.pdf).
- Chapter on [kernels](https://raw.githubusercontent.com/duvenaud/phd-thesis/master/kernels.pdf) from [David Duvenaud](http://www.cs.toronto.edu/~duvenaud/)'s PhD thesis.

Software:

- [Kernlab](https://cran.r-project.org/web/packages/kernlab/index.html) - R package for GPs. Quick [demo](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/KernLabDemo.R).
- [GPML](http://www.gaussianprocess.org/gpml/code/matlab/doc/) - Matlab suite for GPs.
- [Matlab's GP fitting](https://se.mathworks.com/help/stats/gaussian-process-regression.html) in the Statistics and Machine Learning Toolbox. Very quick [demo](https://github.com/mattiasvillani/ESOBE2017//master/Code/MatlabGPexample.m). 
- [GPy](https://sheffieldml.github.io/GPy/) - extensive Python suite for GPs.

Code snippets:

- [R code](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/GaussianProcesses.R) for simulating from a GP.

Extras:

- [Interactive web app](https://skaae.shinyapps.io/test_project/) for playing around with GPs

---

##### 10.00-10.15 Break

---

#### 10.15-11.00 Gaussian Process Classification and Optimization
Reading:

- [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPclassification.pdf)
- Chapters 3.1-3.4.1 and 3.7 in [Gaussian Processes for Machine Learning](http://www.gaussianprocess.org/gpml/chapters/RW.pdf).
- [Practical Bayesian Optimization of Machine Learning Algorithms](https://arxiv.org/pdf/1206.2944.pdf) (NIPS2012)

Software: 

- [GPML](http://www.gaussianprocess.org/gpml/code/matlab/doc/) - Matlab suite for GPs.
- [GPy](https://sheffieldml.github.io/GPy/) - extensive Python suite for GPs.
- [Spearmint - Python library for GPO](https://github.com/HIPS/Spearmint)
- [Bayesian Optimization - Python library for GPO](https://github.com/fmfn/BayesianOptimization)
- [BayesOpt](https://se.mathworks.com/help/stats/bayesian-optimization-algorithm.html) in the Statistics and Machine Learning Toolbox
- [RStan](https://betanalpha.github.io/assets/case_studies/gp_part1/part1.html) 

##### 11.00-11.15 Coffee/Tea break

---

#### 11.15-12.00 Distributed and Subsampling MCMC

Reading: 

- [Slides Distributed MCMC](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/DistributedMCMC.pdf)
- [Slides Subsampling MCMC](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/SubsamplingMCMC.pdf)  

---

##### 12.00-13.15 Lunch

---

#### 13.15-14.00 Text as data - Topic Models

Reading: 

- [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/TopicModels.pdf)
- [Probabilistic Topic Models](http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf) - a non-technical intro to topic models
- [Latent Dirichlet Allocation](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf) - the original paper
- [Topic Models](http://www.cs.columbia.edu/~blei/papers/BleiLafferty2009.pdf) - a survey of the field

Software:

- Mallet R package [CRAN version](https://cran.r-project.org/web/packages/mallet/) or more refined [GitHub repo](https://github.com/MansMeg/RMallet)
- [gensim](https://radimrehurek.com/gensim/) - Python module.

---

##### 14.00-14.15 Break

---

#### 14.15-15.00 Variational Bayes

Reading: 

- [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/VariationalInference.pdf)
- [Explaining Variational Approximations](http://www.maths.usyd.edu.au/u/jormerod/JTOpapers/Ormerod10.pdf) (Amer Stat)
- [Variational Inference: A Review for Statisticians](https://arxiv.org/abs/1601.00670) (JASA2017)

Software:

[Edward for variational inference](http://edwardlib.org/tutorials/variational-inference) - a probabilistic programming language (think Stan)

---

##### 15.00-15.15 Coffee/Tea break

---

 
#### 15.15-16.00 Deep Learning

Reading: 

- [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/DeepLearning.pdf)
- Chapters 1,4,5 and 6 of [Deep Learning](http://www.deeplearningbook.org/) - the main book for deep learning.

Software:

- [Google's TensorFlow](https://www.tensorflow.org/)

Code for analyzing the [Bank Marketing Data](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from the [UCI repository](https://archive.ics.uci.edu/ml/index.html):
- [classification.R](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/DeepNN/classification/classification.R) using the mxnet package. [R-bloggers about mxnet](https://www.r-bloggers.com/deep-learning-with-mxnetr/)
- [classification.py](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/DeepNN/classification/classification.py) and as [python notebook](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/DeepNN/classification/classification.ipynb)
- [classification.m](https://github.com/mattiasvillani/ESOBE2017/raw/master/Code/DeepNN/classification/classification.m)

---

