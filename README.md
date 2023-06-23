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

## Terminal

[Warp terminal](https://www.warp.dev/)

[Of My Zsh](https://ohmyz.sh/)
