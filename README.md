# Apriori Association Python [![License](http://www.apache.org/licenses/LICENSE-2.0)](LICENSE) [![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://python.org)

Practical implementation of Apriori algorithm for association rule mining in Python. Perfect for learning and experimentation!

## Features
- 🧠 Complete Apriori algorithm implementation
- 🛒 Market basket analysis examples
- 📝 Jupyter notebook tutorials
- 📁 Sample datasets included

## Quick Start
```bash
git clone https://github.com/mohbds1/apriori-association-python
cd apriori-association-python
pip install -r requirements.txt
jupyter notebook apriori_demo.ipynb
An efficient pure Python implementation of the Apriori algorithm.
```

The apriori algorithm uncovers hidden structures in categorical data.
The classical example is a database containing purchases from a supermarket.
Every purchase has a number of items associated with it.
We would like to uncover association rules such as {bread, eggs} -> {bacon} from the data.
This is the goal of [association rule learning](https://en.wikipedia.org/wiki/Association_rule_learning), and the [Apriori algorithm](https://en.wikipedia.org/wiki/Apriori_algorithm) is arguably the most famous algorithm for this problem.
This repository contains an efficient, well-tested implementation of the apriori algorithm as described in the [original paper](https://www.macs.hw.ac.uk/~dwcorne/Teaching/agrawal94fast.pdf) by Agrawal et al, published in 1994.
