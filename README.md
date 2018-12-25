======<br>
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
https://www.urlteam.org/2018/11/%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3selenium%E8%A2%AB%E6%A3%80%E6%B5%8B%EF%BC%8C%E5%AE%9E%E7%8E%B0%E6%B7%98%E5%AE%9D%E7%99%BB%E9%99%86/
https://stackoverflow.com/questions/33225947/can-a-website-detect-when-you-are-using-selenium-with-chromedriver
http://www.site-digger.com/html/articles/20180821/653.html
https://intoli.com/blog/making-chrome-headless-undetectable/
