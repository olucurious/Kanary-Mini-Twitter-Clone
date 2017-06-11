# Kanary-Mini-Twitter-Clone
This is a proof of concept RestAPI written in Kotlin and built with Kanary web framework


AngularJS frontend is here: https://github.com/olucurious/cwitter

![alt text](https://github.com/olucurious/Cwitter/raw/master/ScreenShot.png?raw=true "")


Quickstart
==========

Deploy using Heroku:

* Download and cd into the directory.
```sh
$ cd Kanary-Mini-Twitter-Clone
```

* Create a new git project and add all the files to it
```sh
$ git add .
```

* Commit all the files to git
```sh
$ git commit -m "init"
```

* Login to Heroku
```sh
$ heroku login
```

* Create a new Heroku project and take note of the url
```sh
$ heroku create
```

* Push everything to Heroku and your new RestAPI will be available at the url you copied earlier
```sh
$ git push heroku master
```


NOTE: Heroku's storage is ephemeral, so the sqlite db will be wiped out after a while, you should use Heroku postgres or a remote database for more serious stuff