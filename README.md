bash-config
===========

Adam's addition aliases, prompt setup and misc helpful things for bash

Installation
------------
```
git clone git@github.com:Peregrine42/bash-config.git .bash-config 

cat >>~/.bashrc <<EOS
  if [[ -f ~/.bash-config/bash_settings ]]; then
    source ~/.bash-config/bash_settings
EOS
```
