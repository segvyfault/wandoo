# wandoo

![screenshot of wandoo](app.png)

wandoo is a simple and sturdy tree-based todo software in pure C using ncurses. 

its a checklist with n-ary trees. what more could you want? 

technically project management software but its like 600 lines of code..

its pretty simple, that's good. i'm following the unix philosophy.

## how to use 

- space to check or uncheck a task.
- enter to edit a task.
- delete to delete a task.
- `+` opens an add task dialog to create a new task.
- `w` writes the file with the latest changes. 
- `q` quits.

## contributing

add a pull request and ill look over it. 

if you get a bug please just make an issue with a screenshot or logs.

## installing

[![Packaging status](https://repology.org/badge/vertical-allrepos/wandoo.svg)](https://repology.org/project/wandoo/versions)

### aur
`yay -S wandoo` or `paru -S wandoo`

### compiling

Run `./build.sh` and `build/wandoo <filename>` to build/run. 

## licensing

Licensed under GPLv3 or later. 
