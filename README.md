# utils

A collection of different useful tools, hacks and programs I use from time to time.

## Aliases

delete local git branches:

```alias deleteLocalBranches="git branch | grep -v "staging" | grep -v "master" | xargs git branch -D"```

interactive git checkout:

```alias gci="git branch | fzf | xargs git checkout"```

## mySql

Find column names in all tables and views in db:

```SELECT COLUMN_NAME AS 'ColumnName' ,TABLE_NAME AS 'TableName' FROM INFORMATION_SCHEMA.COLUMNS WHERE COLUMN_NAME LIKE '%MyName%' ORDER BY TableName ,ColumnName;```

## NPM
- Execute arch and confirm that at the moment it is returning arm64
- Execute arch -x86_64 zsh
- Execute arch and confirm that it is now returning i386
- Execute nvm install 14. NVM will install the latest NodeJs 14.
- Execute nvm use 14 to switch to NodeJs 14, if you have other NodeJs

## Terminal

[Warp terminal](https://www.warp.dev/) <br>
[Oh My Zsh](https://ohmyz.sh/)
