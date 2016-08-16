# Win-Price-Estimation
This is a win price estimation model in Real-Time Biddiing System by NCTU ADSL lab.

# Required Python Library
  [scikit-learn](http://scikit-learn.org/stable/), [scipy](https://www.scipy.org/), [mpmath](http://mpmath.org/)

# Dataset

[iPinYou dataset] (http://data.computational-advertising.org/)

  * Season2: 2013/6/6~2013/6/12

  * Season3: 2013/10/19~2013/10/27

# Library
   * [dbFeatureHasher](./dbFeatureHasher): [sklearn FeatureHasher](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.FeatureHasher.html)
   * [ftrlProximal](./ftrlProximal):Use [Ftrl-Proximal](https://www.eecs.tufts.edu/~dsculley/papers/ad-click-prediction.pdf) to predict CTR for each bid request. 

# Competitor
  [Wush Chi-Hsuan Wu, Mi-Yen Yeh, and Ming-Syan Chen. Predicting Winning Price in Real Time Bidding with Censored Data](http://www0.cs.ucl.ac.uk/staff/w.zhang/rtb-papers/win-price-pred.pdf). In KDD, 2015.
  
  
  https://github.com/wush978/KDD2015wpp
