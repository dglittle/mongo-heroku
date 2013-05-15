mongo-heroku
============

program to login to the mongoDB instance running in the current directory's heroku instance (for Mac OS X)

### Instead Of

```
> heroku config
=== super-dragon-9000 Config Vars
HOST:             https://super-dragon-9000.herokuapp.com
MONGOHQ_URL:      mongodb://heroku:password123@dragon.mongohq.com:1001/app12345
NODE_ENV:         production
SESSION_SECRET:   kittens

> mongo -u heroku -p password123 dragon.mongohq.com:1001/app12345
```

### Just Do

```
> mongo-heroku
```

## Install on Mac

```
> curl https://raw.github.com/dglittle/mongo-heroku/master/mongo-heroku -sLo /usr/local/bin/mongo-heroku &&
  chmod +x /usr/local/bin/mongo-heroku
```

## Uninstall

```
rm /usr/local/bin/mongo-heroku
```
