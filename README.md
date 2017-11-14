# cancerdetect
## This is the support file uesed by our cancer detect kernel
It is hard to install xgboost in my MAC.<br>
There is a common version of installation.<br>
http://xgboost.readthedocs.io/en/latest/build.html<br>
It doesn't work at my computer.<br>
I found a proper way in a kaggle answer.<br>
git clone --recursive https://github.com/dmlc/xgboost<br>
cd xgboost; cp make/minimum.mk ./config.mk; make -j4<br>
cd python-package; python setup.py develop --user<br>
