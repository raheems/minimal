---
title: Testing code embedding in Markdown
author: Enayet Raheem
date: '2017-02-26'
slug: Code embedding in markdown
from_Rmd: yes
---

This is a chunk of R code


```r
# This is R code
x <- rnorm(100)
hist(x)
```

![plot of chunk unnamed-chunk-1](/figures/en/2017-02-26-my-first-blog-post/unnamed-chunk-1-1.png)


```python
# Code in Python
import numpy as np
x = np.array(10)
print(x)
```

```
## 10
```

Now trying code in SAS

```
# Code in SAS
# Highlights not showing
proc sql;
select * from a
quit;
```

