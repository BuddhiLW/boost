# Beginner Boost

![WIP](https://img.shields.io/badge/status-wip-red.svg)

Every [May the 4th] I hold a free series of live-recorded *Beginner
Boost* sessions on [Twitch] and [YouTube] that run through the end of July
(or so). Below is the outline of current and planned content. This is a
living document; it changes from day to day --- even hour to hour ---
[like software].

[Twitch]: <https://twitch.tv/rwxrob>
[YouTube]: <https://youtube.com/rwxrob>
[May the 4th]: 20210503061604
[like software]: <https://github.com/rwxrob/zet/search?q=knowledge%20as%20source>

> 🌟 You may want to *Watch* this GitHub repo to be notified of updates and
changes. A *Star* would be nice as well. If you want to contribute open
an *Issue* to discuss it. Much of the content will be drawn from my
[personal Zettelkasten repo] and my [learning labs] (which you might
also want to watch for changes, but they are not always Boost related).
You can also help fund this project by clicking *Sponsor*. Thanks.

[personal Zettelkasten repo]: <https://github.com/rwxrob/zet>
[learning labs]: <https://github.com/rwxrob/lab>

# But First ...

## <a id=day0> Day 0: Get Set Up, May the 4th Be With You

[📺 Unedited Video](https://youtu.be/UkE2KMsVzjQ)

1. [What is the purpose of Beginner Boost?](20210504161937)
1. [Beginner Boost, Day 0, Logistics](20210505025834)
1. [Who is the Beginner Boost for?](20210505031231)
1. [Setup Essential Services][services]

[services]: <https://github.com/rwxrob/zet/tree/main/20210505023938>

## <a id=day1> Day 1: Get Motivated to Learn ¡Viva la Revolución!

[📺 Unedited Video](https://youtu.be/U7BNE-AKLeI)

1. [Problems with Traditional Education][prob]
1. [Help Others Learn, A Social Responsibility][social]
1. [Become an Autodidact][autodidact]
1. [Tribute to Aaron Swartz][aaron]

[prob]: <https://github.com/rwxrob/zet/tree/main/20210506155713>
[social]: <https://github.com/rwxrob/zet/tree/main/20210506160012>
[autodidact]: <https://github.com/rwxrob/zet/tree/main/20210506163935>
[aaron]: <https://github.com/rwxrob/zet/tree/main/20210506164209>

## <a id=day2> Day 2: The Scientific Method, Our Greatest Learning Tool

[📺 Unedited Video](https://youtu.be/mlecHo2p7aU)

1. What did you learn about the Scientific Method?
1. The RWX Method, Refining the Scientific Method
   1. Read, Research, Reach Out, Repeat
   1. Write Who, What (If), When, Where, Why, and How
   1. Execute, Explore, Experiment, and Exercise
1. Fail Faster, Fail Better, Fail Often
1. Personal Progressive Enhancement, Layer Your Learning
1. Meritocracy in the Workplace
1. Zettelkasten (Slips in a Box) Knowledge Management System
1. Capture Thoughts as Markdown, The Syntax of Knowledge Source

# Get on a Docker Linux Container Terminal

## <a id=day3> Day 3: Understand Linux Approach

[📺 Unedited Video](https://youtu.be/8myY7Ydf64g)

1. What's Linux? History of UNIX and GNU/Linux
1. Do Macs Use Linux?
1. Does Windows Use Linux?
1. The UNIX Philosophy
1. How Does Linux Work?
1. When and How Should I Install Linux?

## <a id=day4> Day 4: Get on the Terminal

[📺 Unedited Video](https://youtu.be/GlpSi2LW4_Y)

**Mac:** Open and Configure a Mac Terminal  
**Windows:** Install and Configure Modern Windows Terminal  
**Linux:** Open and Configure a Linux Terminal  

1. What's the Difference Between TUI and CLI?
1. Terminal Emulators Replaced Teletype Machines
1. The Terminal is Different Than Command Line Shell
1. Should I install Git-Bash on Windows?
1. What about Alacritty/Kitty or ...?
1. My Favorite Theme: GruvBox
1. Can't I just use VSCode on Windows?
1. Why not just use Vim plugins with VSCode?
1. What about WSL2 on Windows?

## <a id=day5> Day 5: Learn About Containers and Get Docker

[📺 Unedited Video](https://youtu.be/GlpSi2LW4_Y)

1. What's a Container and Why Should You Care?
   1. The Difference Between "Container" and "Image"?
   1. Kubernetes is the New Operating System
   1. Containers are the New Programs
1. Install Docker
   1. Install Docker on Windows
      1. Why do I still need WSL2?
   1. Install Docker on a Mac
   1. Install Docker on Linux

## <a id=day6> Day 6: Run Linux Inside a Container

[📺 Unedited Video](https://youtu.be/_jJWOgZwBBs)

1. Linux Distro Matters Less in Container World
   1. `docker run -it --rm ubuntu`
   1. `docker run -it --rm fedora`
   1. `docker run -it --rm archlinux`
   1. `docker run -it --rm opensuse`
   1. `docker run -it --rm nixos/nix`
   1. `docker run -it --rm kalilinux/kali-rolling`
   1. `docker run -it --rm blackarch/blackarch`
1. Run Rob's Workspace Linux Container
   1. `docker run -it --rm rwxrob/workspace`
   1. Workspace Means *Not* Small (1.3GB)
1. Use Docker Basic Commands
   1. Use Docker Pull
   1. Use Docker Run
   1. Use Docker Start
   1. Use Docker Attach and Detach `Ctrl-pq`
   1. Use Docker Stop
   1. Use Docker Remove
1. Don't Worry About Dockerfile and Compose (For Now)

# Survive the Linux Command Line (For Now)

## <a id=day7> Day 7: Start Using the Linux Terminal Command Line

[📺 Unedited Video](https://youtu.be/EBtWx5m7pds)

1. The Command Line, Fastest Human-Computer Interface
1. Every Command Line Entered is a Line of Shell Code
1. Use Bash, Don't Play the Shell Game (For Now)
   1. Interactive Shell is Not Same as Shell Scripting
   1. Why Bash and Not Zsh, Fish, or Whatever?
   1. Use Consistent Supported Bash Tab Completion
1. Understand the Parts of the Command Prompt
   1. Username
   1. Hostname
   1. Interesting Origin of Email Addresses
   1. Current Directory
   1. Git Branch
   1. Long Versus Short Prompts
1. Navigate Your Command History Efficiently
   1. Use Up and Down Arrow Keys (For Now)
   1. Use Initial Spaces to Stop Adding to History
   1. Use Hashtag to Make One Line Comment Notes
   1. Don't Learn More for Now (Learn `set -o vi` Later)
1. Send Special Terminal Escapes
   1. Remember, a Terminal is Just a Teletype Emulator
   1. `Ctrl-c` to Send Interrupt Signal (*Not* Copy)
   1. `Ctrl-[` to Send Exact Same as `Esc` Key
   1. `Ctrl-s`/`Ctrl-q` to Buffer and Suspend/Unsuspend
      1. "Help! My Terminal is Frozen!"
   1. `Ctrl-z` to Background Current Process (Not Quit)
   1. `Ctrl-d` to Send EOF (End of File)
   1. `Ctrl-v`, `Ctrl-x` Do Nothing (From Shell)
   1. Silencing the Terminal Bell
1. Cut and Paste from Host Operating System
   1. Depends on Terminal
   1. First Ever Mouse Had Three-Button, Middle Was Paste
   1. Windows Right Click to Paste
   1. `Ctrl-x|c|v` Don't *Usually* Work (And Shouldn't)
1. Learn Useful and Essential Beginning User Commands
   1. Use `reset` to Fix Bork Terminal
   1. Use `clear` to Clear Screen (and Alternatives)
   1. Use `watch` to Repeat Things and See Output
   1. Use `man`/`help`/`info` Commands to Get Help
   1. Use `less`/`more` for Paging Output
   1. Use `ls` Command to List Files and Directories
   1. Use `type` to See What Type of Thing It Is
   1. Use `which` to See Where Command Lives
   1. Use `pwd` Command to Show Working Directory
   1. Use `cd` Command to Change Directories
      1. Use `cd foo` to Change Into `foo` Child Directory
      1. Use `cd ..` to Change Into Parent Directory
      1. Use `cd -` to Toggle Change to Last Directory
      1. Use `cd ~` (or Just `cd`) to Change to Home Directory
      1. Don't Fall for Silly `cd` Replacements (Use `CDPATH`)
   1. Use `cal` to View Calendar
   1. Use `date` to View Dates and Times
      1. Use `date -u +%Y%m%d%H%M%S` to Get ISO Second
      1. Use `date -d 'last week'` to Exact Time Last Week
   1. Use `bc` for Floating Point Precision Math Calculations
      1. Don't Forget To Set Scale (`scale=2`)
      1. Use Semicolons for Same Line
   1. Use `top` to See Running Processes
      1. Often Replaced with `htop`

## <a id=day8> Day 8: Install Software from Package Manager

[📺 Unedited Video](https://youtu.be/6EDT-Vc4PCY)

1. Create and Name a Workspace Container
   1. `docker run -it --name boost -h boost ubuntu`
   1. Difference Between Detach and Exit
      1. Detach with `Ctrl-pq`
      1. Exit with `exit`
1. Understand Container States and Storage
1. Manage Software Packages from Command Line
   1. Restoring Documentation and More with `unminimize`
   1. Understand Linux Package Management
   1. Use `apt update`
   1. Use `apt search`
   1. Use `apt install`
   1. Use `apt remove`

## <a id=day9> Day 9: Work with File System from Command Line

[📺 Unedited Video](https://youtu.be/eZV14xpFAlA)

1. [OverTheWire], Fun Hacker Practice
1. Understand the Linux File System
1. Use `mkdir` to Make a New Directory
1. Use `mktemp` to Make a New File or Directory
1. Use `rmdir` to Remove an Empty Directory
1. Use `touch` to Make a New File (or Update Timestamp)
1. Use `mv` to Move or Rename a File or Directory
1. Use `cp` to Copy a File or Directory
1. Use `rm` to Remove a File or Directory
1. Use `ln` to Link to a File or Directory
   1. What is the difference between hard and soft link?
   1. Used `ln` for Multicall Executables (BusyBox)
1. Use `file` to See What Details About File
1. Use `stat` to See Exhaustive Details About File
1. Use `cat` to Display Lines of a File, First to Last
1. Use `tac` to Display Lines of a File, Last to First
1. User `head` to Display Number of Lines at Top
1. User `tail` to Display Number of Lines at Bottom
1. Use `grep` to Find Lines of a File
1. Use `uniq` to Find Unique Lines
1. Use `sort` to Sort Lines
   1. Use `wc` to Count Lines, Words, Bytes, and Runes

[OverTheWire]: <https://overthewire.org/wargames/bandit/>

## <a id=day10> Day 10: Understand Streams, Pipes, and Redirection

[📺 Unedited Video](https://youtu.be/rhknj8h0zU8)

1. Understand Standard Output and Error
   1. Use `echo` and `printf` to Print Stuff
      1. Difference Between `echo` and `printf`
      1. Never Use `print` (for Printers)
   1. Use `>` File Redirect Operator
      1. Fix `find` Command Errors with Redirection 
   1. Use `>>` File Append Operator
   1. Use `>|` Force File Overwrite Operator
1. Understand Pipes and Pipeline
   1. Use `|` Pipe Operator to Connect Out with In
   1. Power of Pipelines and Shell Integration
      1. Watch Ken Thompson Describe UNIX Pipes
      1. Pipes are at the Core of UNIX Philosophy
      1. Use Shell and Pipes from Within Applications
   1. Transform and Filter Lines
      1. Use `nl` to Number Lines
      1. Use `rev` to Reverse Line
      1. Use `tee` to Pipe *and* Redirect Lines
      1. Use `echo` for Arguments and `cat` for Lines
      1. Use `xargs` to Transform Lines Into Arguments
      1. Use `cut` to Remove Stuff from Lines of Stream
      1. Use `tr` to Translate Stuff in Lines of Stream
      1. Use `sed` to Edit Lines of Stream (Streamed `ed`) (More Later)
      1. Use `jq` to Select from JSON Input (More Later)
      1. Use `yq` to Select from YAML Input (More Later)
1. Get Standard Input Into Your Programs
   1. Input Most Useful After You Know How to Code
   1. Use `<` File Input Redirect Operator
      1. Always Use `<` Instead of `cat foo | ...`
   1. Use `<<` Here Document Operator
   1. Use `read` to Read Input
      1. Combine `printf` and `read` to Create Prompts
      1. Always Use `-r` and Understand Why
      1. Use `for` or `while` with Read for Line Loops
   1. Use `curl` to Read Input from Internet
      1. Usually Combined with `jq` or `yq`

## <a id=day11> Day 11: Edit Files with Basic Vi (Then Vim)

[📺 Unedited Video](https://youtu.be/RJ3EVB5-Emw)

*Please note that I mistakenly say `Ctrl-C` many times in this video
where I actually mean `Ctrl-[`. See if you can catch all the times I get
it wrong. It will be a good way to learn from my mistake.*

1. Vi ("Visual Mode") History and Legacy
1. Why Vi/m and Not NeoVim/Emacs/Nano/VSCode?
1. Appreciate the Difference Between `vi` and `vim`
1. Restore `Esc` Key to Its Original Keyboard Home
1. Use `Ctrl-[` Instead of `Esc` Key (Never `Ctrl-x|z`)
1. Do the Vim Tutorial (`vimtutor`), But Beware
1. Other Recommended Learning Resources
   1. <https://openvim.com>
   1. <http://vimgenius.com> (no `s`)
   1. Vim Adventures is Strongly Discouraged
1. Start with Defaults and *Zero* Configuration
   1. Complex `.vimrc` is *Not* for Beginners
   1. Customizing `.vimrc` Requires Scripting Skills
   1. Eventually, Learn a Little Vimscript (Not Lua)
1. Avoid Vim Pane Splitting (Use TMUX Instead)

## <a id=day12> Day 12: Manage Users, Groups, and Permissions 

[📺 Unedited Video](https://youtu.be/TNdI8fNvP5k)

1. How Much User Stuff Do I Need to Know?
1. Create and Manage Users and Groups
   1. Use `adduser` and `useradd` to Create User
   1. Use `su - <user>` to "Login" as User
   1. Use `deluser` and `userdel` to Delete User
   1. Use `usermod` to Modify User Settings
   1. Use `addgroup` and `groupadd` to Create Group 
   1. Use `delgroup` and `groupdel` to Delete Group 
   1. Use `groupmod` to Modify User Settings
   1. Use `passwd` to Change Passwords
   1. Know the Files Involved
      1. `/etc/passwd`
      1. `/etc/shadow`
      1. `/etc/group`
   1. Use `id` to Get the User and Group Information
   1. Use `login` to Login
      1. Does Not Register as Logged in User
   1. Use `su - <user>` to Simulate a Login as Root
   1. Understand `root` Access
      1. Use `sudo` to Grant `root` (SuperUser) Access
      1. Use `sudo su -` to Get Root Shell
      1. use `doas -s` to Do Something As Root
   1. Use `who`,`w`,`whoami`,`who am i`,`last` to See Users
1. Understand UNIX File and Directory Ownership and Permissions
   1. Use `ls -l` to See Permissions
   1. Use `stat` to See Even More About File
   1. Read, Write, and Execute Permission
      1. On Files
      1. On Directories
1. Modify Ownership and Permissions
   1. Use `chmod` to Change Permissions
   1. Use `chown` to Change Owner (and Group)
   1. Use `chgrp` to Change Group
1. Know About Setuid, Setgid, and Such, But Don't Use 

# Start Scripting in POSIX Shell

## <a id=day13> Day 13: Scripts are Just Terminal Commands in a File

[📺 Unedited Video](https://youtu.be/72OmbZiyKsc)

1. You're Already Coding, Every Command *is* Code
   1. Commands are Really Just Functions with Arguments
1. POSIX Shell is a Universal Command Interpreter
   1. Shell Started as Bourne Shell, Now Ash and Dash
   1. Korn Shell Led to Bash and Zsh Interpreters
   1. Awk, Perl, Python, Ruby, Node Also Shell Scripting
1. Create First Script 
   1. Create a File Containing Some Commands
   1. Know What *Interpreted* Means
   1. Know What *Syntax* Means
   1. Use `sh` Interpreter to Run Commands in File
   1. Use `bash` Interpreter to Run Same Commands
   1. Use `perl` to Attempt Same and Note Errors
   1. Use `python3` to Attempt Same and Note Errors
   1. Use `chmod +x` to Make File Executable
   1. Add `#!/bin/sh` Shebang Line to Specify Interpreter
      1. Even If Others Work, Use to Communicate to Others
      1. Sets Vi/m Syntax So Suffix Not Needed
   1. What's Up with `/usr/bin/env`?
   1. Use `set -e` to Exit Program if *Anything* Fails
   1. Use `set -x` When Needed for Debug Tracing
1. Difference Between *Running* and *Sourcing* Scripts
   1. Use Dot (`.`) or `source` to Source a Script
   1. Most Stuff Should Be in Script (Subprocesses)
   1. Some Stuff Can't Be Done Any Other Way
      1. Change Current Working Directory
      1. Modify Current Environment
1. Put Executables in Your `PATH` to Run From Anywhere
   1. Use `which` to See Which Executable Wins
   1. Understand Difference Between `which` and `type`
   1. Never Put `./` in Your Path
1. Manage Jobs and Processes
   1. A Running Program is a *Process*
   1. A Backgrounded Program a *Job*
   1. `Ctrl-z` to Background Running Process
   1. Use `jobs` to See All Background Processes
   1. Use `fg` to Bring Background Job Forward
   1. Use `&` and `nohup` to Start and Keep Program in Background
   1. use `()` to Combine Into Single Process (Subshell)
      1. Know `$$` Still Refers to Parent
   1. Use `pgrep`, `pkill`, `kill`, `ps`, `/proc` to See Processes
   1. Use `nice` to Change Priority of Process
   1. Use `crontab` to Schedule Jobs in the Background
      1. Editing Your `crontab` is Not Really Beginner

## <a id=day14> Day 14: Functions, Procedures, Operations, Methods

[📺 Unedited Video](https://youtu.be/zRNwt1y3lr4)

1. Get and Use `shellcheck` Throughout to Ensure POSIX
1. Know What *POSIX* Means [POSIX Standard]
1. Know What *Script* Means
1. Know What *Program* and *Programming* Mean
1. A Universe of Stateful, Composable Objects with Actions, Interacting
   1. Not Specifically Talking About OOP, Much Bigger
1. On Programming Humans ...
   1. Routines, Procedures, and Commands in the Real World
   1. What About *Algorithms*?
1. It All Started with Math, Know Why Linear Algebra Matters
   1. `f(x,y) = 3x + 2y + 3`
      1. `x`,`y` are *Parameters*
      1. `=`, `+` are *Operators*
      1. `3x`, `2y`, `3` are *Operands*
      1. Function Parameter Variables Receive Argument Values
      1. "This functions *returns* the value ..."
      1. Same in JS: `let z = (x,y) => 3*x + 2*y +3`
1. *True* Functions are *Not* Procedures
   1. What About *Subroutines*?
   1. What About *Methods*?
   1. What About *Operations*?
   1. What About *Commands*?
   1. Even If Language Allows, Group Code Into Either
   1. Know Advantages of One Over the Other
   1. Know What *Functional Programming* Is
   1. Know What *Side Effects* Are
1. Shell Functions Are *Not* Functions, They Are Subroutines
1. Use Action Verb When Naming
1. Use `foo() {}` to Create a Subroutine (Function)

[POSIX Standard]: <http://31.42.184.140/main/2328000/032a6956a51f4d1dd5c91aa161eee03a/IEEE%20%26%20The%20Open%20Group%20-%20IEEE%20Std%201003.1-2017%20%28aka%20POSIX%29%20%282017%29.pdf>

## <a id=day15> Day 15: State, Data Types, Variables, and Constants

[📺 Unedited Video](https://youtu.be/yHdUh6-qZw8)

1. All Objects Have States: Mutable, Immutable, Persistent, Dynamic, Static
1. Variables Save Data as State
1. Types Declare How to View State Data
   1. Same Data, Different Type
   1. Binary (Base 2, Ones and Zeros, Digital)
   1. Number 
   1. Symbol or Letter
   1. String
   1. Bit Field 
   1. POSIX Shell Only Has Strings and Integers
   1. Use Strings for Everything
1. Function Parameter Variables Receive Argument Values
   1. Like Putting Something Into Box or on List
1. Use `=` to Declare and Assign Variable
   1. No Spaces Around Operator (`=`)
1. Use `$foo` to Use Variable After Assigned
1. *Always* Wrap with Double Quotes (`"$foo"`)
1. Use `"${foo}bar"` to Disambiguate
1. Don't Forget to Check with `shellcheck`
1. Use `bc` When Numbers and Math are Actually Needed
1. Understand *Scope* and Considerations
   1. Know What *Scope* Means
   1. Know What a *Block* Is
   1. Know What *Global* Means
   1. Know What *Local* Means
1. All Variables are Global in POSIX Shell

## <a id=day16> Day 16: Function and Command Communication

[📺 Unedited Video](https://youtu.be/Gv-39gfhKR8)

1. *Calling* to Communicate
   1. Know What to *Call* a Function or Subroutine Means
   1. Arguments Contain Incoming Communication
   1. Return Values Produce Outbound Communication
   1. Calls Must Come After Declarations
1. Arguments Passed as Special Parameter Variables: `$1`, ...
   1. No Parameters Between Parens `()`
   1. Unlike Most Other Languages
1. Use `$0` to Get Name/Path of Executable Script
1. Use `$#` to Get the Total Number of Arguments Passed
1. Use `"$@"` for `"first" "second" "third"`
1. Use `"$*"` for `"first second third"`
1. Reminder About Necessity of Quoting (`"foo"`) Everything
1. Shell Functions Only Return Integers
   1. Use `return [RVALUE]` to Set Return Value
   1. Omitting `return` is Fine
   1. Return Values are *Not* Output
   1. Use `echo`/`printf` and `$(foo)` to "Return" Strings
1. Use `$?` for Last Return Value
1. Use `exit [RVALUE]` to Return Value for Program Itself

## <a id=day17> Day 17: Flow, Conditions, and Logic

[📺 Unedited Video](https://youtu.be/Nvsae1lVPwY)

1. Conditions Alter Flow
1. Use `test` to Check Condition (Read `test` Man Page)
   1. Remember, `test` Not Needed for Single Command
1. Use `&&` and `||` to Create *Compound Conditions*
1. Use Range Notation (like `20 < i < 100`)
1. Know and Use *Short-Circuit Logic*
   1. Use `test` to Keep it Clear to Read
   1. Use `&&` to Join (Not `||`)
1. Use `set -e` to Assert Every Line or Exit
   1. Use `|| true` to Make Assertion Optional
1. Avoid Problematic `[]` to Check Conditions
1. Use `if` to Group Commands If True
1. Avoid `else` Whenever Possible, Return Early Instead
1. Use `case` to Branch Multiple Conditions

## <a id=day18> Day 18: Loops, Signals, and Events

1. Power of Loops on the Command Line
   1. Use `watch` for Simple Repetition
   1. Iterating Over Ranges and Items
   1. Creating Small Monitors and Services
1. Loops Repeat Commands Until Condition Met
   1. Use `while` to Repeat While Condition True
   1. Use `while true` for Infinite Loops
   1. Use `sleep` to Lessen Impact to System
   1. Use `until` to Repeat Until Condition True
   1. Avoid Loops That Require Math in POSIX Shell
      1. But If Needed, Remember, Integer Only
   1. Understand "Init", "Check", "Change"
      1. Arithmetic `for` Loops are Not POSIX
      1. Can Be Done with `while` in POSIX
   1. Use `for` to Repeat for Sequence or Number of Items
      1. Use `seq` Instead of Bash `{1..10}` Notation
   1. Use `break` to Break Out of Any Loop
   1. Use `continue` to Start Next Iteration Early
1. Unexpected Benefits of Loops for Editing
1. Know What *Inter-Process Communication (IPC)* is and Methods
   1. Signals are Just One IPC Method
1. Signals Communicate Between Programs
   1. Use `kill`, `pkill` to Send a Signal
      1. Use `Ctrl-C` from Within Process to Send Interrupt
      1. Use `kill` to Send Terminate
      1. Use `kill -1` to Send Hangup (Reread Config)
      1. Use `kill -9` to Send Kill When Not Responding
      1. No Need to Learn Others (For Now)
   1. Use `trap` to Handle a Signal
1. Use Loops, `nohup`, and `&` to Create *Daemons*
   1. Judicious Use of `&` Can Improve Concurrent Tasks
   1. Better to Use `screen` or `tmux` (More Later)
1. Use `exec` to Exit a Program When Possible
   1. Hands Off All Resources, Including Signal Handling

## <a id=day19> Day 19: ANSI Escapes, Color, Gotchas, What's Next?

1. Happy Pride Month!
1. Don't Fear Color, All Modern Terminals Have Support
1. Know When to Use Color and When to Not
   1. Use `test -t 1` to Detect Terminal Output
   1. Use `reset` When You Break Your Interactive Terminal
1. Know What *ANSI Escapes* are, Which to Use, and How to Lookup
1. Use `printf` Because Escapes `\e` Properly
   1. Avoid `echo -e` Which is Not POSIX
1. Prefer 16 Terminal Theme Colors for Compatibility
   1. Use `\e[30m`-`\e[37m` for Terminal Theme Colors
   1. Use `\e[1;30m`-`\e[1;38m` for "Bright/Bold" Variations
   1. Add 10 for Background Colors
   1. Use `\e[H\e[2J` to Clear the Screen
   1. Use `\e[0m` to Reset Color
   1. Avoid Dependencies from Sourcing Color Libraries
      1. Write a [`termcolors`] Script, Run from Vim
1. Use Specific Colors When Needed
   1. Understand These are *Never* Relative to Terminal Theme
   1. Set `TERM` to `xterm-256colors` (or Whatever)
   1. Use `\e[38;5;Nm` for "Hundreds" of Colors ( 0 <= N <= 255)
   1. Use `\e[38;2;R;G;Bm` for "Millions" of Colors ( 0 <= R,G,B <= 255)

1. Conclusion of POSIX Shell Scripting
   1. What's Next for Shell Coding
   1. Learn Bash `RANDOM` for Fun
   1. Learn POSIX Parameter Expansion
   1. You Just Don't Need `awk`, Ever
   1. Sometimes You Need `sed` to Remain POSIX Compliant
   1. Don't Use `expr`, It's Deprecated
   1. POSIX -> Bash / Perl -> Python / CmdBox Go (Not Shell, But Still)
   1. Learn Bash *After* Coding a Lot of POSIX First
      1. Bash is Fine, When You Have It
      1. Much Better Parameter Expansion
      1. Safe Double Bracket Conditions
      1. Regular Expression Support (Never Use `sed`)
      1. Use `select` for Instant Interactive Menus
      1. Read Google Bash Style Guidelines
      1. It is Very Difficult to Keep Bashisms Out of Your Head
   1. Node and Deno If You Must Have JavaScript
   1. Ruby is Great as Well (If You Need It)
1. Some Fun Challenges to Get You Started
   1. <https://rwx.gg/lang/cha>
1. Other Resources

[`termcolors`]: <https://raw.githubusercontent.com/rwxrob/dot/main/scripts/termcolors>

# Deal with Data, In a Structured Way

*Remember purpose of Boost is not to cover in depth, but to give a sense
of what you need to know and why. Mastering these topics (SQL, for
example) could take several months alone, writing your own language
grammar in PEGN, a year or more*

## <a id=day20> Day 20: Understand the Need for Structured Data

1. What is Data?
1. Evolution of Data Utilization
1. Delimited Data (WS, Tab, Bar, Paths, CSV)
1. Universal JSON, YAML, and JSON-Schema Data
1. Pattern Matching (Globbing, Globstar)
1. Matching and Parsing with Regular Expressions

Other important structured data formats to know:

* gRPC and ProtoBuf
* Hashicorp Configuration Language (HCL)
* ABNF, EBNF, PEG, and PEGN Specification Languages
* Structured Query Language (SQL)
* Markdown
* INI and TOML
* HTML
* XML

## <a id=day21> Day 21: Delimited Data (Space, Tab, Bar, Paths, CSV)

1. Describe Differences Between Delimited Data Formats
1. Name Common Applications and Uses of Delimited Data
1. Know the Different Forms of *White Space* 
1. Know the Difference Between `PATH` and File Path 
1. Use Parameter Expansion to Get Prefix and Suffix
1. Use `cut` To Get At Stuff In The Middle (But Careful, Not Greedy)
1. Use `awk` If You Really Want (But You Don't Need It)
1. Use `tr` or `sed` to Change the Delimiter or "Squeeze" (Spaces, etc.)
1. Understand Input Field Separator (IFS) (Maybe use `()`)
1. Understand the Problems with CSV (Not the Source Manager)

## <a id=day22> Day 22: Universal JSON, YAML, JSON-Schema Data

1. What is JSON and Why Does it Matter?
   1. JSON is for Parsing, Not People
   1. "Should I Use JSON5?" HELL NO!
1. What is YAML and Why Does it Matter?
   1. YAML is for People and Programming
1. Know the Definition of *Schema*
1. Know the Definition of *Domain Model*
1. Use `jq`/`yq` to Parse and Output JSON/YAML Data
   1. Install `jq` with `sudo apt install jq`
   1. Install `yq` However
   1. Always Surround Query in Single Quotes

## <a id=day23> Day 23: Pattern Matching (Globbing, Globstar)

1. Use `shopt` to Activate Pattern Matching in Bash Shell
1. Use `*` to Match Zero or More of Anything
1. Use `**/` to Descend Into All Directories as Well
1. Use `?` to Match Exactly One of Anything
1. Use `{foo,bar}` to Match `foo` or `bar`
1. Use `[a-c]` to Match `a`, `b`, or `c` (Like `{a,b,c}`)
1. Use `[^a-c]` Match *Anything But* `a`,`b`, or `c`
1. Use `[^.]*` to Match All Non-Hidden Files
1. Skip POSIX Character Classes (For Now)
1. Know the Limitations of Globbing
   1. Glob on the Command Line, But Avoid in Scripts
   1. Extended Globbing (`**`, etc.) is Not POSIX
   1. Can Expand Past Maximum Command Line Length
      1. Consider `find` Instead When Needed
   1. Know When a Regex Is Better
1. Learning Resources
   1. Use Globbing for Static Site Generator ([20210327130106])

[20210327130106]: <https://youtu.be/Efk2M77naFU>

## <a id=day24> Day 24: Match and Parse with Regular Expressions

1. Know What a *Regular Expression* (Regex) Is
1. Know Regex is for Matching *And* Parsing
1. Use `Deny` Then `Allow` Approach with Regex Validation
   1. Basis of Perl Taint (`-T`)
1. *Never* Use the Deprecated `expr` for Anything
1. Use `[[ =~ ]]` / `[[ != ]]` in Bash When Needed and Available
1. Use `sed` or `grep` if You Must
   1. Basic Regular Expressions (BRE) Only
   1. Just Don't Clutter Brain with BRE
1. Use Perl Regex Whenever Possible
   1. Perl Set the Standard for Modern Regex (PCRE)
   1. Use `\s` to Match White Non-Whitespace Class
   1. Use `\S` to Match White Whitespace Class
   1. Often `\s` and `\S` is All That's Needed
   1. Use `\w` for Word Character Class
      1. Remember `_` is Considered AlphaNumeric
   1. Use `\b` to Match Word Boundary
   1. Use `\p{}` to Match Unicode Properties
   1. Use `[]` to Match Non-Standard Classes
1. POSIX Character Classes Less Relevant in Unicode World
   1. The `[:lower:]` is Not Same as `Ll`
1. Use Alternatives When Possible and Necessary
   1. Parameter Expansion
   1. Substring Matches
1. Know Advantages of Regex Over Other Parsing Methods
   1. Powerful
   1. Succinct
   1. Universal
1. Know Limitations of Regex Versus Other Parsing Methods
   1. Some Grammars Cannot Be Represented
   1. Often Unnecessary Overhead
      1. Cognitive
      1. Technical
1. Learning Resources
   1. <https://alf.nu/RegexGolf>
   1. <https://regex101.com/>
   1. <https://regexr.com>
   1. <https://xkcd.com/1313>

## <a id=day25> Day 25: Terminal Shell Customization Overview

1. Use Hidden Files and Directories
1. No Place Like Home
1. <https://freedesktop.org>
   1. [XDG Specification]
1. Bash Interactive Shell
   1. `/etc/skel`
   1. `.bashrc`
   1. `.bash_profile`
   1. `.profile`
   1. Scripts Collection
1. Vim Configuration
   1. `.vimrc`/`.exrc`
   1. `.vim`
   1. `.vimplugins`
   1. Snippets
1. TMUX
1. Directory Colors
1. Use Symbolic Links to Centralize
1. It *Never* Ends

[XDG Specification]: <https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html>

More ...

----

*More to come (boost is at least 100 days) including ...*

* Create Minimal Web Sites Using Simple, Standard Tech
* Code in C for Understanding Modern Computers
* Code Perl for Practical Prototyping
* Code Go for Building Big Stuff
* Code Python for Math, ML, and Automation
* Know the Problem, Peril, and Practicality of Paradigms
