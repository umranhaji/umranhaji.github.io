---
layout: page
title: About
permalink: /about/
---

Centrarium is a custom theme for Jekyll, made by [Ben Centra](http://bencentra.com) for his own blog. He’d be humbled if you liked it enough to use it as well! Installation and configuration instructions can be found in the [GitHub repository](https://github.com/bencentra/centrarium).

![test](/uploads/wide-field.jpg)

This page is a good place to write about yourself, your project, your product, or whatever it is your site is for. You can replace the image above, or you can get rid of it entirely.

You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/). And you can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)

```python
a = []
for i in np.arange(5):
    print "Hello world"
    a.append(i)
print "Just a test"
```

```r
S = function(sample){
    n = length(sample)
    S = 1 - ecdf(sample)(seq(0,12, .01))*n/(n+1) #return(log(sample, base = exp(1))) return(S)
    }
samples = replicate(100, rexp(n = 100, rate = 1))
Ss = apply(samples, 2, FUN=S) x = seq(0,12,.01)
logs = apply(Ss, 2, log)
matplot(x, logs, lty=1, type='l', xlab = 'Time',
ylab='Log of Empirical Survival Function',
main="Log Survival Functions for 100 Samples from Exponential (1) Distribution", cex.main=.85)
grid()
```

{% highlight <R> %}

S = function(sample){
    n = length(sample)
    S = 1 - ecdf(sample)(seq(0,12, .01))*n/(n+1) #return(log(sample, base = exp(1))) return(S)
    }
samples = replicate(100, rexp(n = 100, rate = 1))
Ss = apply(samples, 2, FUN=S) x = seq(0,12,.01)
logs = apply(Ss, 2, log)
matplot(x, logs, lty=1, type='l', xlab = 'Time',
ylab='Log of Empirical Survival Function',
main="Log Survival Functions for 100 Samples from Exponential (1) Distribution", cex.main=.85)
grid()

{% endhighlight %}}

Below I will test some $$\forall x \in R$$ latex:

$$a = b$$

$$\left( \sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6} \right)$$