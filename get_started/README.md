We ran everything on the Google Cloud Platform. Our raw data is in a bucket that our "preprocessing.py" script pulls from. The shell script in this directory should install all the packages you need. We are running python 2.7 so if you want to run on python 3 you are on your own. Once your environment is setup, you should be able to run preprocessing.py in place and it will pull the raw data and process it into the state in which we used it.