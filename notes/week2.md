# Week 2, rwxrob boost

- isosec: 221105100254-03

- "What would we do today?" -> Come-up with the questions. (Active learning.)

TODOs:

- Install and configure terminal software (MS Terminal, iTerm2).
- Setup Secure Shell.
- Really simple and essential shell commands.
- Basic system update and package management and installation.
- What is UNIX and Linux?
- What is the `shell` and `why do I care?`.
- What is `inode`? Why everything is "just a file"?

  > "Everything is a file."

  `inode` is an entry to a table. A directory, in UNIX-like systems, behaves as
  a table of `inodes`. The files, in these systems, correspond to a `inode` in
  their table representation, just like directories.

  `inode` stands for **information-node**.

- What is a `rooted-node-tree`? A directory is a `rooted-node-tree`.

## Commands Used

- `man` - show manual information about a command.
- `sudo` - do it as a root(superuser).
- `apt` - use interactively only (use `apt-get` in scripts).
- `sudo apt get` - update all the source for packages.
- `sudo apt upgrade` - upgrade `all` packages to latest version.
- `ls` - list the files in the (current) directory.
- `ls -al` - list all the files including hidden (begin with .).
- `hostname` - display name of host computer.
- `pwd` - print working directory.
- `cd` - change current directory.

Related:

- ![https://www.linuxcommand.org](https://www.linuxcommand.org)
