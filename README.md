[![PyPI version](https://img.shields.io/pypi/v/ar-apriori?color=8b21a0&label=PyPI%20الإصدار)](https://pypi.org/project/ar-apriori/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://python.org)

An efficient pure Python implementation of the Apriori algorithm.

The apriori algorithm uncovers hidden structures in categorical data.
The classical example is a database containing purchases from a supermarket.
Every purchase has a number of items associated with it.
We would like to uncover association rules such as {bread, eggs} -> {bacon} from the data.
This is the goal of [association rule learning](https://en.wikipedia.org/wiki/Association_rule_learning), and the [Apriori algorithm](https://en.wikipedia.org/wiki/Apriori_algorithm) is arguably the most famous algorithm for this problem.
This repository contains an efficient, well-tested implementation of the apriori algorithm as described in the [original paper](https://www.macs.hw.ac.uk/~dwcorne/Teaching/agrawal94fast.pdf) by Agrawal et al, published in 1994.
