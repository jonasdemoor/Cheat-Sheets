# Linux Cheat Sheet

## Git

| Command | Description
| ------- | -----------
 `git checkout -- <file>` | Revert local changes to file before commit.
 `git reset HEAD <file>` | Unstage a staged file.

## VIM

### Movement

| Key | Motion
| --- | ------
`j` | Move down
`k` | Move up
`l` | Move left
`h` | Move right
`w` | Move forward by one word
`b` | Move backwards by one word
`gg` | Move to beginning of file
`G` | Move to end of file

### Buffer management

| Command | Description
| ------- | -----------
`:ls` | Display a list of open buffers
`:b <buffer>` | Switches to open buffer 
`:bd <buffer>` | Deletes current or specified buffer 

### Searching

| Command | Description
| ------- | -----------
`%s/foo/bar/g` | Find each occurrence of 'foo' (in all lines), and replace it with 'bar'

### Formatting

| Command | Description
| ------- | -----------
`=` | Fix text indentation (e.g. `gg=GG`: go to beginning, fix indentation, move to EOF)
`:%s/\s\+$//e` | Remove trailing whitespace
