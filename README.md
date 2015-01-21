## Deploy instructions

    git clone https://github.com/MozMorris/phpapp.git
    cd phpapp
    heroku create
    heroku config:set BUILDPACK_URL=https://github.com/MozMorris/heroku-buildpack-php#pagespeed
    git push heroku master
    heroku open
