mongo-heroku
============

program to login to the mongo instance running in the current directory's heroku instance (for Mac OS X)

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

## Install

1. Put mongo-heroku on your $PATH to have access from any directory. Check out http://shapeshed.com/using_custom_shell_scripts_on_osx_or_linux/
2. Run ```chmod +x <path-to-the-script>```
3. Run ```mongo-heroku``` from any Heroku app directory.
