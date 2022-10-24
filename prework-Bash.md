# Bash Exercises

## Shell

A shell determines how your terminal looks and acts. This article is for bash but I'm pretty sure the shell we use at codefellows is zsh.

## Commands

- up and down arrows- scroll previous commands.
- tab- auto complete path
- `pwd` print working directory `/Users/luser/Documents/codefellows/reading-notes`
- `ls` list contents of current dir. can be given options such as `-a` which additionally lists hidden files. can also be given a location to list, relative to current dir.
- `cd` change directory. works with paths as described below
- `file` give a dir and it will tell you the filetype. maybe more useful on linux
- `man` give a command and it will take you to the manual page. this will tell you the command syntax, as well as applicable options. you can even type in `man man` for info abou the manual itself. `-k` as option for a general search for an action whose command you don't know, something like that.
- options have long and short hands, longhand are called with `--` and short with a single `-`. shorthand options can be chained together.
- `mkdir newDir` make directory named newDir. can also be given a path to make dir at given location. `-p` to make parent dirs i.e. `/make/all/these/dirs`
- `rmdir newDir` remove dir. works much the same but opposite. can only remove empty dirs.
- `touch someFile` seems like this works just how it sounds, updates a files access record but nothing else, just a touch. more useful: if the file doesn't exsist, it creates a blank file.
- `cp` copy file. needs a spot to copy from and a spot to copy to. to copy directories and the files they contain, you must use `-r` recursive, so all contained files get the treatment as well.
- `mv` move file. works a similar way to above. can be used to rename files. moving dirs does not require `-r`
- `rm` remove file. can be used with `-r` to remove dirs and everything in them! `-i` is a good addition here, interactive, prompts you on every step taken so you can abort.

## Paths

- assume we are here ---------vvv
- `/Users/luser/Documents/codefellows/reading-notes`
- and want to go here --------------------^^^
- relative path would be simply `reading-notes` where as the line above is the absolute path.
- `~` home dir
- `.` current dir, so above rlative path would actually be `./reading-notes` probably.
- `..` one level above current dir. if `.` is `/codefellows`, `..` is `/Documents`. add more `.` to go up as many levels
