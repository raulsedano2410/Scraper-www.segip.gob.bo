# Scraper_Bolivia

![Interior Ministry page](pagebolivia.PNG)

> ### Need :
<center>
    Enter the Bolivian "General Personal Identification Service"<br/>
    page and Create a File with the addresses of all the Identity<br/>
    Registry Offices.
</center>
 
> ### website:

<center>
    <a href="(https://www.segip.gob.bo/">www.segip.gob.bo</a>
</center>

> ### Library:

```python
from selenium import webdriver
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from selenium.webdriver.common.by import By
from webdriver_manager.chrome import ChromeDriverManager
import time
from time import sleep
import numpy as np
import pandas as pd
from pandas import Series,DataFrame
import re
```
