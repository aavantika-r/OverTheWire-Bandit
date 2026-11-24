OverTheWire Bandit – Linux Learning Journey

Hands-on Linux learning through OverTheWire Bandit challenges.

Progress

- [x] Level 0 → Level 1
- [x] Level 1 → Level 2
- [x] Level 2 → Level 3
- [x] Level 3 → Level 4
- [x] Level 4 → Level 5
- [ ] Level 5 → Level 6

Level 0 → Level 1: SSH Connection

Command:

ssh bandit0@bandit.labs.overthewire.org -p 2220

Learned:

- SSH (Secure Shell)
- Remote server connection
- SSH port 2220

Level 1 → Level 2: File Named "-"

Command:

cat ./-

Learned:

- Handling filenames starting with special characters
- Using "./" to specify the current directory

Level 2 → Level 3: Spaces in Filenames

Command:

cat "spaces in this filename"

Learned:

- Handling filenames containing spaces
- Using double quotes

Level 3 → Level 4: Hidden Files

Commands:

ls -la
cat ./filename

Learned:

- Listing hidden files
- Understanding the "-a" option
- Accessing hidden files

Level 4 → Level 5: Human-Readable Files

Commands:

file ./*
cat ./filename

Learned:

- Identifying file types
- ASCII text
- Understanding binary and unidentified data

Level 5 → Level 6: Finding Files

Command:

find . -type f -size 1033c ! -executable

Learned:

- Finding regular files
- Searching by file size
- Checking executable permissions
- Combining search conditions

Linux Commands Practised

"ssh" · "ls" · "cd" · "pwd" · "cat" · "file" · "find" · "stat"

Important Note

Passwords are intentionally excluded from this repository.

Learning Goal

Build strong Linux command-line skills through practical security challenges.
