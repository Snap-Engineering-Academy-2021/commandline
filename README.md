# Let's Practice Using the Command Line!

We adapted this tutorial from [Jacob Wolf and Making with Code](https://cs.fablearn.org/courses/cs9/unit00/labs/lab1_terminal/). :)

## Let's go on an adventure

First, let's practice using `brew` to install python3 (we won't be coding in python at all; we just need it for the terminal adventure). Type this into your terminal: 

```
brew install python
```

Then, type this into your terminal so you can make a copy of our terminal adventure project: 

```
git clone https://github.com/Snap-Engineering-Academy-2021/lab-terminal-adventure.git
```

Type the following to get started. You will need to use terminal commands!

```
cd lab-terminal-adventure
node welcomeToSurface.js
```

## What is the command line interface? 

It's a text-based way for you to give instructions to your computer. Before we had graphical user interfaces (finders, file explorers, windows, icons, etc.), we had the command line interface. It's also known as a terminal or shell!  

![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Hard_reset_BBC_Micro_32K_Acorn_DFS.gif/220px-Hard_reset_BBC_Micro_32K_Acorn_DFS.gif)

![](https://thatmarta.files.wordpress.com/2020/10/2020-10-11_15-59-1.png)

✨By the way, there are lots of ways you can personalize your terminal! Check out [youtube tutorials](https://www.youtube.com/watch?v=eDnor6PXjnQ) or [internet resources](https://opensource.com/article/20/8/iterm2-zsh) in your spare time. ✨

## Some terminal commands to get you started 

#### Commands

Let’s see what goes into a command. Some commands like like pwd (which shows us the path to our current location) appear solo:

```
jhan$ pwd
/Users/jwolf/Desktop/cs9
```

#### Arguments

Other commands require arguments that follow the command. An arguement is a specification for where or what you want the command to run. For example, the cd command requires a path to a directory as an arguement:

```
jhan$ cd desktop/
```

Some commands require multiple arguments. mv moves a directory or file to another location and requires two paths as arguements:

```
jhan$ mv file.txt desktop/
```

#### Options

Finally, the functionality of commands can often be changed with options which are placed between the command and any arguments the command takes. An option is a minor difference in the way the command works. For example, the rm command normally removes (or deletes) a file:

```
jhan$ rm bad_file.txt
```

However, with the -d option, rm will also remove a directory:

```
jhan$ rm -d bad_directory
```

| Command              | What it does                                 |
| --------------       | -------------------------------------------- |
| `ls`                 | List what's in the current directory.        |
| `cd ~`               | Go to your home directory                    |
| `cd somewhere`       | Go to `somewhere`                            |
| `cd ..`              | Go to the parent directory                   |
| `cat file.txt`       | Prints out the contents of `file.txt`        |
| `python3 file.py`      | Runs `file.py`, which is a python file |
| `node file.js`      | Runs `file.js`, which is a javascript file |
| `mv old.txt new.txt` | Renames a file from `old.txt` to `new.txt`. Also works for directories. |
| `mv file.txt dir`    | Moves a file to directory `dir`.             |
| `mv dir1 dir2`       | Moves `dir1` to `dir2` or renames if `dir2` doesn't exist.          |
| `cp old.txt new.txt` | Copy a file from `old.txt` to `new.txt`.     |
| `mkdir bag`          | Creates a new directory called `bag`     |
| `pwd`                | Prints the path to where you are in the filesystem |
| `rm file.txt`        | removes (deletes) the file `file.txt`        |
| `rm -d dir`          | removes (deletes) the directory `dir`        |
| `rm -r dir`          | recursively removes (deletes) the directory `dir` and all subdirectories and files within that directory. **Be careful, this is a powerful tool!** |
| `man cal`          | Pulls up the reference guide for the command `cal` -- use this to learn about new commands |
| `:q!`          | Quit out of a file or page without saving|
| `:wq`          | Quit out of a file with saving  |


## More terminal commands
These are just for fun. 

| Command              | What it does                                 |
| --------------       | -------------------------------------------- |
| `say hello`          | Makes the computer say hello (Mac only)      |
| `cal`                | Shows you a monthly calendar                 |
| `banner hello`       | Just try it                                  |
