ppft
====
distributed and parallel python

About Ppft
----------
`ppft` is a fork of Parallel Python, and is developed as part of `pathos`: https://github.com/uqfoundation/pathos

Parallel Python module (`pp`) provides an easy and efficient way to create parallel-enabled applications for SMP computers and clusters. `pp` module features cross-platform portability and dynamic load balancing. Thus application written with `pp` will parallelize efficiently even on heterogeneous and multi-platform clusters (including clusters running other application with variable CPU loads). Visit http://www.parallelpython.com for further information.

`pathos` is a python framework for heterogeneous computing.
`pathos` is in active development, so any user feedback, bug reports, comments,
or suggestions are highly appreciated.  A list of known issues is maintained
at http://trac.mystic.cacr.caltech.edu/project/pathos/query.html, with a public
ticket list at https://github.com/uqfoundation/pathos/issues.

NOTE: `ppft` installs as `pp`. If `pp` is installed, it should be uninstalled before `ppft` is installed -- otherwise, `import pp` may not find the `ppft` fork.


Major Changes
-------------
* `pip` and `setuptools` support
* support for python 3
* enhanced serialization, using `dill.source`


Current Release
---------------
This version is a fork of `pp-1.6.4`.

The latest released version of `ppft` is available from::
    https://pypi.org/project/ppft

`pp` and `ppft` are distributed under a BSD-like license.


Development Version
-------------------
You can get the latest development version with all the shiny new features at::
    https://github.com/uqfoundation

If you have a new contribution, please submit a pull request.


More Information
----------------
Probably the best way to get started is to look at the examples that are
provided within `pp`.  See `pp.examples` for a set of scripts.  Please feel
free to submit a ticket on github, or ask a question on stackoverflow
(@Mike McKerns).

`pathos` is an active research tool. There are a growing number of publications
and presentations that discuss real-world examples and new features of `pathos`
in greater detail than presented in the user's guide.  If you would like to
share how you use `pathos` in your work, please post a link or send an email
(to mmckerns at uqfoundation dot org).


Citation
--------
If you use `pathos` to do research that leads to publication, we ask that you
acknowledge use of `pathos` by citing the following in your publication::

    M.M. McKerns, L. Strand, T. Sullivan, A. Fang, M.A.G. Aivazis,
    "Building a framework for predictive science", Proceedings of
    the 10th Python in Science Conference, 2011;
    http://arxiv.org/pdf/1202.1056

    Michael McKerns and Michael Aivazis,
    "pathos: a framework for heterogeneous computing", 2010- ;
    http://trac.mystic.cacr.caltech.edu/project/pathos

Please see http://trac.mystic.cacr.caltech.edu/project/pathos or
http://arxiv.org/pdf/1202.1056 for further information.

