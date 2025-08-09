# Efficient-Apriori ![Build Status](https://github.com/mohbds1/apriori-association-python/workflows/Python%20CI/badge.svg?branch=master) [![PyPI version](https://badge.fury.io/py/apriori.svg)](https://pypi.org/project/apriori-association-python/) [![Documentation Status](https://readthedocs.org/projects/apriori-association-python/badge/?version=latest)](https://apriori-association-python.readthedocs.io/en/latest/?badge=latest) [![Downloads](https://pepy.tech/badge/apriori-association-python)](https://pepy.tech/project/apriori-association-python) [![Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

An efficient pure Python implementation of the Apriori algorithm.

The apriori algorithm uncovers hidden structures in categorical data.
The classical example is a database containing purchases from a supermarket.
Every purchase has a number of items associated with it.
We would like to uncover association rules such as {bread, eggs} -> {bacon} from the data.
This is the goal of [association rule learning](https://en.wikipedia.org/wiki/Association_rule_learning), and the [Apriori algorithm](https://en.wikipedia.org/wiki/Apriori_algorithm) is arguably the most famous algorithm for this problem.
This repository contains an efficient, well-tested implementation of the apriori algorithm as described in the [original paper](https://www.macs.hw.ac.uk/~dwcorne/Teaching/agrawal94fast.pdf) by Agrawal et al, published in 1994.
