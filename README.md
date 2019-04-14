# Tmux Personal Settings

- author: engel-ch
- license: MIT
- last update: 2019-04-14

# Description

tmux.conf enabling

- mouse selections
- default (OSX) selection mode when pressing the Alt key
- 1..n window numbering starting from 1 instead of 0
- F1..F8 to switch windows
- F9 to start copy mode
- prefix r  to reload the configuration file
- Shift left/right-arrow  to switch between windows

# Installation

Usually, this repository is cloned to `/opt/Arch/`. To install it, do

```bash
cd /opt/Arch/
git clone <this repo>
```

Now install the configuration file:

```bash
cd 
ln -fs /opt/Arch/tmux/dot.tmux.conf ~/.tmux.conf
```

# References

Thanks for all the information found here:

- https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/
- https://awhan.wordpress.com/2010/06/20/copy-paste-in-tmux/
- http://jasonwryan.com/blog/2011/06/07/copy-and-paste-in-tmux/
- https://gist.github.com/russelldb/06873e0ad4f5ba1c4eec1b673ff4d4cd
- https://blog.bugsnag.com/benefits-of-using-tmux/
- http://uploads.mitechie.com/books/tmux_p1_1.pdf  :- book about productive, mouse-free development with tmux.
- https://thoughtbot.com/blog/a-tmux-crash-course
- https://tmuxcheatsheet.com/
