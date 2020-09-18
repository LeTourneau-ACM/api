# API Walkthrough
## Setting Up Environment
1. Visit https://www.python.org/downloads/ and download version 3.8.5
2. Make sure you have pip3 installed:
`$ pip --version`
3. You should see something like:
`pip 20.2.3 from c:\python\lib\site-packages\pip (python 3.8)`
4. If you are out of date (not version 20.2.3), you can run:
`$ pip install --upgrade pip`
5. Install the python library for web requests:
`$ pip install requests`
6. Verify your installation by running
```$ python3
>>> import requests
#### If the library is not found, try reinstalling
>>> quit()
```

## Connecting to the API
(For more public APIs, take a look at https://github.com/public-apis/public-apis)
1. Navigate to your project folder and clone the GitHub repository for this project:
```
$ cd ~/projects
$ git clone https://github.com/letourneau-ACM/api
```
2. Open the api_demo.py file in IDLE
3. In your browser, visit https://openlibrary.org/developers/api 
4. Click on the ‘books’ API link
5. Look up your favorite book and GET the data using the API
