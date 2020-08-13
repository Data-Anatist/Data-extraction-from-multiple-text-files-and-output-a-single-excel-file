# Data extraction from multiple text files and output a single excel file

### Purpose
##### In the organization, the network team has to maintain multiple network devices like primary or secondary switches, routers, Access points, etc. For the monitoring of those devices, Putty software use. Putty software generates a .txt file for each device uniquely. ***For example,*** if total online devices are 1000 so that Putty generates 1000 .txt files for each device. It is very difficult to analyze the update modification that will happen in the devices, by opening a single file at a time.

### Solution
##### Using a Python will extract the needed data as .csv or .xlsx in single file

### Import libraries used
```sh
import re
import glob
import pandas as pd
from pandas import ExcelWriter
```

### Technique used
###### The regular expression used to search the needed data from the .txt file. for more details click the link.https://docs.python.org/3/library/re.html
