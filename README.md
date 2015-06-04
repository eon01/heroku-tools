# heroku-vim
To edit a file on a Heroku Dyno, you will need vim. Use this script to install it.
First, attach a Dyno bash to your terminal:

```
$ heroku run bash
Running bash attached to terminal... up, run.1
~ $
```

Then run:

```
wget -O - https://raw.githubusercontent.com/eon01/heroku-tools/master/heroku-vim.sh | bash
```
