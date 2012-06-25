### apache-sample

Sample app that can be deployed to Heroku that uses https://github.com/anandbn/heroku-buildpack-apache buildpack

### To get started:

1. Clone this repo (git clone )
2. Create a Heroku app

    heroku create --buildpack https://github.com/anandbn/heroku-buildpack-apache
    
3. Make changes to your httpd.conf
4. Commit your changes to heroku
   
    git push heroku master

