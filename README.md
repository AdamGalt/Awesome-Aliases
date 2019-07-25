# Awesome-Aliases

A collection of awesome aliases for your bash shell

alias plz="sudo !!"  # runs the last command as sudo

alias oops='history -d $(history 1)'  # Remove last command from history

alias vi="nano"  # Don't get along with vi, this is for you

alias upgrade='sudo apt update && sudo apt upgrade -y && apt-get autoremove -y && apt-get autoclean'  # upgrade with less typing

alias df='df -h'  # human readable output should be default

alias wget='cd ~/Downloads; wget'  # wget always download to ~/Downloads

alias ping='mtr'  # because my traceroute is WAY better than ping

alias nuke='kill -9' # no messing about - just kill it now

alias zzz='sudo shutdown now'  # put it to bed with less typing

alias rrr='sudo restart now'  # restart with less typing

alias uptime='uptime | cowsay'  # your cow now tells you your uptime

A handy app to grab to fix your typos:

https://github.com/nvbn/thefuck - Magnificent app which corrects your previous console command.

