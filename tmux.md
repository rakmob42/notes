`sudo apt install tmux` to install tmux.

`tmux` to start tmux.

**Panes**

`ctrl+b %` to create a new pane vertically separated.

`ctrl+b` with arrow keys to move between windows.

`ctrl+b "` to create a new pane horizontally separated.

`ctrl+b E` to have equal sized panes.

`exit` to exit the pane.

**Windows**

`ctrl+b c` to create a new window.

`ctrl+b` followed with number to switch to that window.

`ctrl+b ,` to rename the window.

A window can have multiple panes.

**Sessions**

A session will preserve your work even if you lose the connection.

`ctrl+b d` to detatch tmux session while keeping it running in the background.

`tmux ls` to see list of running tmux sessions.

`tmux attach -t 0` to attach to the session number 0.

`tmux rename-session -t 0 woof` to rename the session `0` to `woof`.

`tmux new -s meow` will create a new named session called `meow`.

`tmux kill-session -t meow` will close the named session.
