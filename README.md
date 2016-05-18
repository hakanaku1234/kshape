## k-Shape

Python implementation of k-Shape

### Usage

```
from kshape import kshape, zscore
import numpy as np

time_series = [[1,2,3,4], [0,1,2,3], [-1,1,-1,1], [1,2,2,3]]
cluster_num = 2
clusters = kshape(zscore(time_series), cluster_num)
```
