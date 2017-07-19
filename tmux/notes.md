
## term

session
window
pane

ctrl+b  - prefix

tmux ls - list sessions
tmux attach  
tmux new -t


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


xpanes -c "ping {}" 192.168.0.{1..9}


ssh admin@transcoder-agent-00.awsusw2.subsplash.net

xpanes -l ev -c 'ssh admin@{}.awsusw2.subsplash.net' transcoder-agent-{00..16}










