# Termux-ide-tools
Shell scripts automating installation(and much more) of (nvchad?) things so I don't break my bone with ampersand 

It is kind of like termux desktop, but I feel that gui ide on termux is kinda bloat and nonproductive.

That's why I made this script (maybe cringe)

Neovim with NVchad included :D

ncat-fe - ncat based frontend tool in bash 

scroll down for installations

# PREREQUISITES:

Termux (gplay is ded so get from github or f-droid - fresh install recommended)

internet (maybe... 500 mb of data)


some storage (minimum 2 gigs if u wanna install more application)

# INSTALLATION:

## main script:

```sh
curl -sL https://raw.githubusercontent.com/TBApknoob12MC/Termux-ide-tools/main/install.sh | bash
```
## ncat-fe alone:

```sh
 curl -sL https://raw.githubusercontent.com/TBApknoob12MC/Termux-ide-tools/main/ncfe-install.sh | bash
```

exit termux after you see 
```sh
 tools successfully installed.exiting in 10 seconds
```

after reopening type nvim 

wait some time and then when you see nvim opening and see like 'tree-sitter : installed' at the bottom of termux(from my memory),type `:q` multiple(3) times until you get out of nvim

u got a good looking ide/experiment sandbox

change shell to zsh the right way: 

```sh
 chsh
```

type zsh in the prompt to change shell and restart 
