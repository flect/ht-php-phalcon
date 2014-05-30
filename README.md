ht-php-phalcon
==================

Sample project that use PHP Phalcon for Heroku training.

Notes
==================

This project use custom buildpack.  
see [heroku-buildpacks-php-with-phalcon](https://github.com/elct9620/heroku-buildpacks-php-with-phalcon)

How to deploy
--------------

### Step1  

Clone app from Github  

```
$ git clone git@github.com:flect/ht-php-phalcon.git
$ cd ht-php-phalcon/
```

### Step2  

Create Heroku application

```
$ heroku create -b https://github.com/elct9620/heroku-buildpacks-php-with-phalcon
```

### Step3  

Deploy application
```
$ git push heroku master
```

### Step 4

Visit application

```
$ heroku open
```
