pdblp
=====

This is a simple interface to integrate pandas and the Bloomberg Open API.
The standard Bloomberg API provides an extensive set of features for building
applications on top of however does not provide easy and interactive access to
data. This package provides several functions for accessing historical market
data and reference data. A simple set of examples is available
[here](/examples)

The library borrows heavily from a similar package available
[here](https://github.com/kyuni22/pybbg)

##Requires

[Bloomberg Open API](http://www.openbloomberg.com/open-api/) 

[pandas](http://pandas.pydata.org/)

##Installation
To install pdblp clone this repository and pip install the package, i.e.

```
git clone https://github.com/matthewgilbert/pdblp.git
pip install -e pdblp
```

##Documentation
Once `pdblp` has been installed, documentation can be built using

```
cd doc
make html
```

and then viewed in ./doc/_build. Before building this ensure that you are
logged into a Bloomberg terminal as this is required for building many of the
examples.
