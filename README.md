# Bash-Scripts
Bash scripts for learning purposes.

## Content
#### skrypt1
Numering all files in given directory (script call parameter) where we have execute right by adding addictional extension: "..". Numeration should be ascending.
#### skrypt2
In a given directory ($1) find symbolic links to objects in the same directory $1 and delete them.
#### skrypt3
In a given directories tree find subdirectories where owner does not have read or execute permissions, but someone else (group owner or not) has write rights. The script should not impose any additional conditions regarding access rights.
#### skrypt4
In given directory remake all symbolic links defined by relative paths as esuivalent to defined as a absolute paths.
#### skrypt5
In given directories tree list names of all regular files having big letters inside name (not in path or extension) on pattern _ and small letter (for example noweDrogi.doc to nowe_drogi.doc). List with a path (same as find`s -print).
#### skrypt6
In given directory create regular files with names equivalent to next lines in given file (also create files with spaces in names). If file with that name already exists, change permission rights by removing write rights to everyone. If object with that name already exists but it is not a reagular file, display warning and do not change it. 
