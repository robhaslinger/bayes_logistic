=========================
Bayes Logistic Regression
=========================

+------+-----------+
|asdasd|asdasdasd  |
+======+===========+


.. image:: https://img.shields.io/travis/MaxPoint/bayes_logistic.svg
        :target: https://travis-ci.org/MaxPoint/bayes_logistic

.. image:: https://img.shields.io/pypi/v/bayes_logistic.svg
        :target: https://pypi.python.org/pypi/bayes_logistic

.. image:: https://img.shields.io/pypi/pyversions/bayes_logistic.svg
        :target: https://pypi.python.org/pypi/bayes_logistic
        
Notes
----

I wrote the core algorithms of this package back when I worked at 
MaxPoint Interactive. So basically the bayes_logistic/bayes_logistic.py 
function. My co-worker Marius Van Niekerk did all the packaging and made it
pip installable ("pip install bayes_logistic"). I decided to fork it to my
personal repository for posterity.

Overview
----

This package will fit Bayesian logistic regression models with arbitrary
prior means and covariance matrices, although we work with the inverse covariance matrix which is the log-likelihood
Hessian.

Either the full Hessian or a diagonal approximation may be used.

Individual data points may be weighted in an arbitrary manner.  

Finally, p-values on each fitted parameter may be calculated and this can be used
for variable selection of sparse models.

* Free software (BSD): |lic|
* Documentation: https://bayes_logistic.readthedocs.org.
* See related presentation video `here`_.

.. |lic| image:: https://img.shields.io/github/license/MaxPoint/bayes_logistic.svg
.. _here: http://www.opendatascience.com/conferences/rob-haslinger-at-bdf-2015-bayes_logistic-a-python-package-for-bayesian-logistic-regression/

Demo
----

`Example Notebook`_

.. _Example Notebook: http://nbviewer.ipython.org/github/MaxPoint/bayes_logistic/blob/master/notebooks/bayeslogistic_demo.ipynb
