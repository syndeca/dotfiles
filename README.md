# dotfiles
dot em up

### Install dotfiles

    curl -Ls https://raw.githubusercontent.com/syndeca/dotfiles/master/cfg-install.sh | /bin/bash


### Set host nickname

    sudo sh -c 'echo "export NICKNAME=prod|stage|dev.vXXX.appname" > /etc/profile.d/prompt.sh'
    

### Thanks

Thanks to [StreakyCobra][0] for this amazing and easy setup and [durdn][1] for expanding on it and explaining the steps!


[0]: https://news.ycombinator.com/item?id=11071754
[1]: https://www.atlassian.com/git/tutorials/dotfiles
