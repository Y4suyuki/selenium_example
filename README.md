# selenium example


```python
from selenium import webdriver
from selenium.webdriver.common.keys imoprt Keys
driver = webdriver.Firefox()
driver.get('https://google.com')
i = driver.find_element_by_class_name('gLFyf')
i.send_keys('covid19')
i.send_keys(Keys.RETURN)
driver.quit()
```
