# machine-learning-with-solar-data
predicting solar eruptions using machine-learning methods

Of all the activity observed on the Sun, two of the most energetic events are flares and
Coronal Mass Ejections (CMEs). Coronal Mass Ejections (CMEs) are large blasts of energy that eject plasma from the Sun into interplanetary space; flares are more localized blasts that don't eject as much plasma into space. Usually, solar active regions that produce large flares will also produce a CME, but this is not always true.

We use machine-learning algorithms to [1] determine which features distinguish flares associated with CMEs from flares that are not, and [2] forecast whether an active region that produces a flare will also produce a CME. To do so, we use features derived from the photospheric vector magnetic field data taken by the Helioseismic and Magnetic Imager instrument aboard the Solar Dynamics Observatory, which takes the most data of any NASA satellite in history. We find that [1] we only need about 6 features to distinguish between the two populations, and [2] our True Skill Statistic, a forecast verification metric, is a relatively high value of approximately 0.8 plus or minus 0.2. 

The code we used for this study is included in this repository as an ipython notebook (to view the ipython notebook, use the [Jupyter notebook viewer](http://nbviewer.jupyter.org/)). It uses libraries from [scikit-learn](http://scikit-learn.org/stable/) for the machine learning and feature selection analysis. The ipython notebook, and additional data files, is also permanently available in the [Stanford Digital Repository](https://purl.stanford.edu/wt605kh4712). To read more about the research, see [Bobra & Ilonidis (2016)](http://arxiv.org/abs/1603.03775).
