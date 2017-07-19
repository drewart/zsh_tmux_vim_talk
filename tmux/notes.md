
# tmux 

## install

```brew install tmux```

Session -> Windows -> Pane

ctrl+b  - prefix

## cli commands

tmux ls		-- list sessions

tmux attach	-- attach to last session

tmux new -t <name> -- create new session name

## shortcuts

<prefix> d - detach from session

<prefix> : - command mode

<prefix> c - create new window 

<prefix> n - next window

<prefix> p - previous window

<prefix> 0-9 - window number

<prefix> w - windows select

<prefix> , - rename window

<prefix> & - close window   

# panes

<prefix> % - split vertically

<prefix> " - split horizontally

<prefix> o - cycle through open panes

<prefix> q - display pane number

<prefix> x - close pane

<prefix> space - cycle pane layouts


# xpanes + tmux

## xpanes

```brew install xpanes```

### ping 9 servers

note: ctrl+c to cancel ctrl+d to close term 

```xpanes -c "ping {}" 192.168.0.{1..9}```


ssh admin@transcoder-agent-00.awsusw2.subsplash.net

### ssh to 16 servers and control them all

```xpanes -l ev -c 'ssh admin@{}.awsusw2.subsplash.net' transcoder-agent-{00..16}```










