[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

```python
import random
import thinkstats2
import thinkplot

## Generate 1000 random numbers
numbers = [random.random() for x in range(0,1000)]

## Create and plot its PMF:
pmf = thinkstats2.Pmf(numbers)
thinkplot.Pmf(pmf, linewidth = 0.1)
thinkplot.Show()

## Create and plot its CDF:
cdf = thinkstats2.Cdf(numbers)
thinkplot.Cdf(cdf)
thinkplot.Show()

```
