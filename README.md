# Personal Wordpress with Heroku

Personal Portfolio wordpress installation used with square theme. Production available at www.evankimlinger.com

## Installation

Requires use of Postgresql and heroku configs which can be generated [here](https://api.wordpress.org/secret-key/1.1/salt/).

    heroku config:set AUTH_KEY='put your unique phrase here' \
      SECURE_AUTH_KEY='put your unique phrase here' \
      LOGGED_IN_KEY='put your unique phrase here' \
      NONCE_KEY='put your unique phrase here' \
      AUTH_SALT='put your unique phrase here' \
      SECURE_AUTH_SALT='put your unique phrase here' \
      LOGGED_IN_SALT='put your unique phrase here' \
      NONCE_SALT='put your unique phrase here'

For further installation details see [template](https://github.com/mhoofman/wordpress-heroku)



## History

Original wp startup modified from github.com/mhoofman
