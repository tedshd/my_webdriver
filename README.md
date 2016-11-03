## automation test

[webdriver.io](http://webdriver.io/)

### webdriver guide

[DEVELOPER GUIDE](http://webdriver.io/guide.html)

### Check webdriver

Diff OS & Browser use diff webdriver
[Selenium WebDriver](http://www.seleniumhq.org/projects/webdriver/)

### Run Selenium environment

```shell
java -jar /your/download/directory/selenium-server-standalone-2.42.2.jar
```

### Run test code

#### Standalone Mode

```shell
node test.js
```

#### The WDIO Testrunner(recommand)

```shell
./node_modules/.bin/wdio wdio.conf.js

# or

# need set from wdio.conf.js
./node_modules/.bin/wdio wdio.conf.js --suite <test js>
```
