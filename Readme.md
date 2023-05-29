```shell
curl -LO https://invisible-island.net/datafiles/current/terminfo.src.gz && gunzip terminfo.src.gz

/usr/bin/tic -xe tmux-256color terminfo.src

If you want to use tmux-256color for all users, use sudo. The result is placed into /usr/share/terminfo:
sudo /usr/bin/tic -xe tmux-256color terminfo.src
```
