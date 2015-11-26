# selenium-saucelabs-nose
Nosetest plugin for running selenium tests in Saucelabs. Runs tests as per configuration in `saucelabs_config.json`:
```
{
    "recipes": {
        // opera and windows 2003
        "opera11_win2003": { "browserName": "opera", "version": "11", "platform": "Windows 2003" },
        "opera12_win2003": { "browserName": "opera", "version": "12", "platform": "Windows 2003" },

        // chrome and linux
        "chrome_linux": { "browserName": "chrome", "version": "", "platform": "Linux" },

        // firefox and linux
        "firefox3_6_linux": { "browserName": "firefox", "version": "3.6", "platform": "Linux" },
        "firefox4_linux": { "browserName": "firefox", "version": "4", "platform": "Linux" },

    }
  }
 ```

Latest implementation owned by CMED:
https://bitbucket.org/cmedtechnology/selenium-saucelabs-nose
