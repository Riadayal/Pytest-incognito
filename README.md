# How to run an automation test in Pytest in incognito mode on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-incognito)

If you want to run you automation test in Pytest in incognito mode on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps:

You can run a test in incognito mode by adding it in ChromeOptions in the `conftest.py` file. For Chrome:

 ```python
capabilities = {
        "build": "Sample PY Build",
        "platformName": "Windows 11",
        "browserName": "Chrome",
        "browserVersion": "latest",
        "chromeOptions" : {
                "args" : ["incognito"]  # ChromeOption to start chrome in incognito mode
  }
}
 ```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

