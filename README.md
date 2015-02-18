# conda-recipes

[![build status](http://img.shields.io/travis/ioos/conda-recipes/master.svg?style=flat)](https://travis-ci.org/ioos/conda-recipes)
<span>&nbsp;</span>
[![Build status](https://ci.appveyor.com/api/projects/status/github/ioos/conda-recipes?branch=master&svg=true)](https://ci.appveyor.com/project/ocefpaf/conda-recipes)


conda-recipes for IOOS packages

The recipes here create conda packages that are uploaded to
[Binstar.org](http://binstar.org) and shared with the community.

For IOOS python users, the
[Anaconda Scientific Python Distribution](https://store.continuum.io/cshop/anaconda/)
is the easiest way to get custom packages needed to run the IOOS system tests.
Using Anaconda users can `conda install`, which installs not only binary
packages for their platform, but the binary libraries they depend on.
So easier than `pip install` and, thanks to Binary Relocation, more powerful
than python wheels.  System-level installation of libraries and admin
privileges are not requires. Check out
[Travis Oliphant's blog piece](http://technicaldiscovery.blogspot.com/2013/12/why-i-promote-conda.html) for more info.

The recipes here are automatically built using
[Travis-CI](https://travis-ci.org/ioos/conda-recipes) with the assistance of
[Obvious-CI](https://github.com/pelson/Obvious-CI/https://github.com/ioos/conda-recipes/blob/master/.travis.yml#L14-L31).

**CAVEAT:**  Windows users must be aware that the packages here are not fully
tested in a Windows environment.  Some bugs related to path and/or others might
surface when trying to use them.  In that case open a issue here and
[upstream](http://en.wikipedia.org/wiki/Upstream_%28software_development%29).
