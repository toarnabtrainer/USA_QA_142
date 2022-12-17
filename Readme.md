Pressman E-Book Download Link:<br>
https://drive.google.com/file/d/0B7hJ_tX3yJUiVk11QWdxQXRLME0/view?resourcekey=0-c54Ti4gsFstKnBkYUFynlg

HTML Color Codes Site Link: https://htmlcolorcodes.com/

Selenium Tutorial Link: https://www.javatpoint.com/selenium-tutorial

SeleniumProg1.ipynb Code:<br>
-------------------------<br>
### importing required modules<br>
from selenium import webdriver<br>

### check the version of selenium<br>
print (webdriver.__version__)<br>

### check whether the chrome driver is present in the current directory or not<br>
### otherwise provide the relative path of the chromw driver<br>
driver = webdriver.Chrome(executable_path = './chromedriver.exe')<br>

### start wikipedia page<br>
driver.get('https://en.wikipedia.org/wiki/Main_Page')<br>
