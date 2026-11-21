# Task 1: Linux Terminal Navigation & Environment Exploration

## Commands practised
- `pwd` – print the current working directory
- `whoami`, `hostname`, `date` – show the current user, machine name and date
- `ls`, `ls -l`, `ls -la` – list files, with details and hidden files
- `cd <path>` – move into a directory using an absolute or relative path
- `cd ..` – go up one level
- `cd -` – return to the previous directory
- `cd ~` – go to the home directory
- `mkdir -p` – create nested directories in one step
- `touch` – create empty files
- `find <dir> -maxdepth 2 -type d` – list directories up to two levels deep
- `find <dir> -name "README.md"` – locate files by name
- `nano` – edit a file in the terminal
- `rm` – remove a file (used to delete a misspelled `README.0`)
- `tree` – display the directory structure

## What I learned
I learned how to move around the filesystem using absolute paths (for
example `~/Radius-training-center/radius-zero_day`) and relative paths such
as `cd ..`. Shortcuts like `cd -` and `cd ~` let me jump between locations
quickly. I used `ls -la` to read permissions, owners and hidden files such
as `.git`.

I created the `0x02-command_line` structure with `mkdir -p` and `touch`,
checked it with `find`, and fixed a typo (`README.0`) by removing it with
`rm`. Finally, `tree` showed the finished structure: one README for the
assignment and one folder per task, each with its own README.md.

## Screenshot


![Task 1 terminal screenshot](screenshot.png)


