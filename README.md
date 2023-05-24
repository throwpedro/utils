# utils

A collection of different useful tools, hacks and programs I use from time to time.

## git

delete local git branches: ```alias deleteLocalBranches="git branch | grep -v "staging" | grep -v "master" | xargs git branch -D"```
interactive git checkout: ```alias gci="git branch | fzf | xargs git checkout"```
