# Arbitrage Opportunity Evaluation

This application evaluates the arbitrage opportunities of Bitcoin between Bitstamp and Coinbase from 2016 through 2018.It calculates the spread between the two exchanges and the potential gains on selected dates in percentages and in dollar terms.  By using this application, one is able to identify arbitrage opportunities should they exist. 

---

## Libraries and Dependancies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/docs/) - an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [path library](https://docs.python.org/3/library/pathlib.html) - For utilizing filesystem paths with semantics appropriate for different operating systems.

* [numpy](https://numpy.org/doc/) - a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

* [%matplotlib](https://matplotlib.org/) - A a comprehensive library for creating static, animated, and interactive visualizations in Python.

---

## Installation Guide

None.

---

## Usage

The application uses the closing prices of Bitcoin on Bitstamp and Coinbase from December 31, 2015 through January 7, 2019.  It compares the spread between the two exchange in early, middle and late part of the period.  The application quantifies the arbitrage opportunities during each segment of the period by selecting a date in each of the time segment.  The conclusion is that the arbitrage opportunities were more abundant in the early segment of the period and became fully explored, leaving little artitrage opportunities toward the end of the period.  

---

## Contributors

Jackie You with the support of FinTech Boot Camp Staff

---

## License

Berkeley