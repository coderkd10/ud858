ud858
=====

Course code for Building Scalable Apps with Google App Engine in Python class

#Notes
##Installing App Engine SDK on Linux
1. Download the SDK from https://cloud.google.com/appengine/downloads (in this tutorial we will be using the python SDK)
2. Unzip downloaded file.
3. Add SDK directory to path. Run `export PATH=$PATH:<path to app engine sdk>` with the appropriate path to the google app engine directory. For example `export PATH=$PATH:~/Downloads/google_appengine`

##Test App locally
Run `dev_appserver.py <application root>`. For example to run `dev_appserver.py ~/Desktop/udacity_ud858/ud858/Lesson_2/000_Hello_Endpoints`.  
By default the application port is 8080 and admin port is 8000. So to access the running application, open http://localhost:8080/ from a browser.

##Deploy application on Google App Engine
Run `appcfg.py update <application root>`. If deployment is successful, application can be accessed via http://your-app-id.appspot.com/. For example - http://kdfirstproj.appspot.com/
