###Fleiss' Kappa - Statistic to measure inter rater agreement
####Python implementation of Fleiss' Kappa (Joseph L. Fleiss, Measuring Nominal Scale Agreement Among Many Raters, 1971)

```
from fleiss import fleissKappa
kappa = fleissKappa(rate,n)
```

rate - ratings matrix containing number of ratings for each subject per category [size- #subjects X #categories]

n - number of raters   

Refer *example_kappa.py* for example implementation
