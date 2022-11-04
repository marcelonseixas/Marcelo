# Bem Vindo
```python
import pandas as pd

class MarceloSeixas:
    def __init__(self):   
        marcelo = { 'language':{0:'Python',
                                1:'php',
                                2:'html'},
                    'projects':{0:'PRA',
                                  1:'Selenium',
                                  2:'Bs4',
                                  3:'Pandas',
                                  4:'Data Base',
                                  5:'and more'},
                    'learning':{0:'Scrapy',
                                  1:'Flask',
                                  2:'Django',
                                  3:'API',
                                  4:'and more'}} 
        df = pd.DataFrame(marcelo)
        display(df)
if __name__=='__main__':
    MarceloSeixas()

```
