# Dependencies
 - Install git, jdk version needed for server jar, and tmux
 - Inside your server directory write a script called start.sh containing the server launch command. An example script has been provided

# Getting Started
- Start by cloning this repo and copy the config files to the home directory

## To Initialize
 - First run `tmux -f [config-filename]`
 - Then run `tmux attach`

## To Detach
 - Ctrl+b, d

## To stop the server
 - First attach to the session
 - Then type `stop` in the server client

## To kill the Tmux session
 - Run `tmux kill-server`
