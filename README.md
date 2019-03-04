
the chrome of anti taobao login 
======

Overview
========

To login [taobao](https://www.taobao.com/) by selenium,you will get the sliding verification code,so this chrome can ignore that code.

Install
========
1. download form 链接: https://pan.baidu.com/s/1G2Wn4JpkDH97YWIsQHBrmg 提取码: mutq 
2. install mini_installer.exe can get a Chromium,this version is 63,and use selenium(python):
```
driver = webdriver.Chrome(desired_capabilities={'chromeOptions':{'binary':r'C:\Users\Administrator\AppData\Local\Chromium\Application/chrome.exe'}})
driver.get('https://www.taobao.com/')
```

principle
=======
see the "return"$cdc_asdjflasutopfhvcZLmcfl_"in u||f.webdriver" in '淘宝反登陆机制.js'

reference material
=======
https://w3c.github.io/webdriver/<br>
https://stackoverflow.com/questions/33225947/can-a-website-detect-when-you-are-using-selenium-with-chromedriver<br>
http://www.site-digger.com/html/articles/20180821/653.html<br>
https://intoli.com/blog/making-chrome-headless-undetectable/<br>
