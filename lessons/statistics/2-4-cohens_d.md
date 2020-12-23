[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

The Cohen effect size  for the difference in weights between the two groups is -0.089. Compared to 0.029 for the Cohen effect size for the difference in pregnancy length, we can see that the effect size for weight difference is larger in magnitude, though both effects are small. The difference in signs also shows that first babies have a longer pregnancy length but are lighter on average. The code below was used to calculate the two effect sizes.
```python
#Cohen's d for weight between the two groups
CohenEffectSize(firsts['totalwgt_lb'],others['totalwgt_lb'])

#Cohen's d for pregnancy length
CohenEffectSize(firsts['prglngth'],others['prglngth'])
```
