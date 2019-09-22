[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)


```python
import scipy.stats
dist = scipy.stats.norm(loc = mu, scale = sigma)
# Solution goes here
five_feet_ten_inches = 177.8
six_feet_one_inch = 185.42
dist.cdf(185.42) - dist.cdf(177.8)
```

**About 34.27% of the men in the US is between 5ft 10in. and 6ft 1in.**
