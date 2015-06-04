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

# bashrc

Some usefull aliases:

```
alias h="heroku"
alias hl="heroku logs"
alias hlt="heroku logs -t"
alias hc="heroku run console"
alias hr="heroku run"
alias hp="heroku ps"
alias ho="heroku open"
alias hs="heroku status"
alias ha="heroku apps"
alias hu="heroku update"
alias hh="heroku help"
```

Add this file to your Run Control Bash file (usually .bashrc or something like that)

```
curl -sS https://github.com/eon01/heroku-tools/raw/master/bashrc >> path_to_your_bashrc
```
