# TMUX
Tmux is also a Terminal multiplexer that allows us to create number of terminal sessions and run more than one programs or processes at the same time inside a single Terminal window.

#### Split panes horizontally
To split a pane horizontally, press Ctrl+b and " (single quotation mark).

#### Split panes vertically
To split a pane vertically, press Ctrl+b and %.


#### Switch between panes

To switch between panes, press Ctrl+b and Arrow keys (Left, Right, Up, Down).


#### Send commands to all panes

In the previous example, we run three different commands on each pane. However, it is also possible to run send the same commands to all panes at once.


To do so, press Ctrl+b and type the following command and hit ENTER:


```:setw synchronize-panes```



Now type any command on any pane. You will see that the same command is reflected on all panes.

#### Swap panes

To swap panes, press Ctrl+b and o.

#### Show pane numbers

Press Ctrl+b and q to show pane numbers.
