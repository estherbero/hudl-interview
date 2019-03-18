# automated-user-flow

This repository contains the tests for a user flow:
     - Login into hudl.com with your credentials.
     - Upload video
     - Share it with the Team Members

## Getting started

Install python (MacOS used in this task):

```brew install python```

Install Google Chrome:
- Go to https://www.google.com/intl/en_au/chrome/

Download chrome driver:
- Go to https://chromedriver.storage.googleapis.com/index.html?path=2.46/
- Unzip and place in /usr/bin or /usr/local/bin

Install selenium:

```pip install selenium```


## Run tests

You will need to be signed up in Hudl, and then you can either:
- Define env vars `EMAIL` and `PASSWORD` with the proper credentials.
- Modify `email` and `password`variables in test.py file.

In the folder just run:

```python tests.py```
