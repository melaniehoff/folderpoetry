# Folder Poetry Club
 

## A Re-Introduction to your Computer

— A pre-introduction to computing

Coding isn’t something that just happens in your text editor or terminal. Coding can be a wholistic computer practice, a new relationship you have with your computer & your computer habits. from the way you name your files or organize your folders, to completely changing how you perform routine tasks on your computer such as moving a file.

**Activity 2 - The Start of a New Relationship you Have with our Computers**

Old Habits Die Hard or How to Use Your Computer

- Desktop and Folder Organizing - In Class exercise!
    - home/design2b
    - www/
- Navigating through different windows and applications
    - [+How to Use Your Computer](https://paper.dropbox.com/doc/kqWk6aC6zgmpVkIowBrg3)
    - I need a volunteer here to take notes
    - Keyboard shortcuts
- Overview of file paths & file types
    - .txt, .html, .css, .js
    - /../../../../../
1. naming files and folders
2. navigating through windows
3. emoji keyboard
4. files
5. folders
6. matryoshka dolls
7. what is terminal
    1. photoshop
8. interface is artifice
9. whenever you are taking actions on your computer, you are always doing so from a particular location. you are not an omnipresent within the landscape of your computing environment and the desktop is a lie.
10. Everyone will need to download this folder, unzip it, and move it to your “home” folder (the one with the little house icon on a Mac)
11. directories are like / .   
12. example of code poem with url
- There is a wide range of experiences in this room
- Coding isn’t something that just happens in your text editor or terminal
    - Coding can be a revelatory computer practice, a new relationship you have with your computer & your computer habits. from the way you name your files or organize your folders, to completely changing how you perform routine tasks on your computer such as moving a file.
- Note about Melanie’s programming teaching style
    - Feel free to ask questions during class or ask your neighbor if they might be able to point you in the right direction
- Make sure anything you create in class today is something you would be comfortable sharing in class / existing online publicly

- Use Spotlight: Command, space, spotlight search pulled up, type in folder name: design2b
- Command, tab- switches between most recent applications that you already have opened with ease.

Note- Folder names and file names should be written in lowercase and without any spaces.

Cmd + S = save

Cmd + Ctrl + spacebar = emojis!!!

# Command line

- Everyone receives a folder and puts it in their **home** directory
    - What is this folder and how will we use it throughout the whole session?
    - What is the home directory?
- Terminal - what is it?
    - It is a way to get text based access to your operating system
    - How to get to it?
1. Type Cmd + Spacebar to open Quickfinder
2. type ‘terminal’
- Bash - what is it?
    - bash is the programming language that we use in the terminal, often one line at a time, but we can also put bash code in a file and run that file

    - The house as an example folder structure narrative because using the command line is a relational practice. You are never using the command line from a “global” perspective. When you issue commands from the command line, you are doing so, from a particular position within the hierarchy of your computer’s file system.
        - Similarly, when we are inside a house, we are never simultaneously in the kitchen and the bedroom. If we tried to “get into bed” while in the kitchen, we would not be able to. However if we wanted to wash dishes while standing in the kitchen, we would be able to.
        - From the command line, if we have navigated to the Desktop folder but try to perform an action on a file that’s inside your home directory, this would not work. You would have to navigate to the home directory by navigating your file path.

# [Class folder](https://www.notion.so/melaniehoff/Folder-Structure-Narratives-b138497cf2a44e6f9f90c3a78b2bcc01#8a54cef58fe04a2d9d960e5ca6c79b69)



## File and Folder Naming
- All lowercase
- No spaces

# Commands, codes, spells
## [Spreadsheet of commands](https://docs.google.com/spreadsheets/d/1vooOk6UczgGD8eLHbizH6kIYJl0DVEpxyo7GEr266KY/edit#gid=0)

## Handy Shortcuts

| Keyboard Shortcuts for Mac | Description                 |
|----------------------------|-----------------------------|
| cmd + Tab                  | Switch between applications |
| Cmd + Spacebar             | Spotlight search            |
| Cmd + S                    | Save file                   |
| Cmd + Shift + N            | New Folder                  |
| Cmd + Ctl + Spacebar       | Emoji Keyboard              |

## Bash Commands

| Commands in Bash                        | Description                               | Verb   |
|-----------------------------------------|-------------------------------------------|--------|
| `cd`                                      | change directory                          | move   |
| `cd ..`                                   | change directory one level back           | return |
| `ls`                                      | list contents of directory                | look   |
| `pwd`                                     | parent working directory                  | where  |
| `open .`                                  | open folder with finder                   | open   |
| `open filename.txt`                       | opens file in Text Edit                   | open   |
| `cat`                                     | print contents                            | print  |
| `touch filename.txt`                      | create a file named filename.txt          | create |
| `mkdir foldername/`                       | create a folder named filename.txt        | create |
| `rm filename.txt`                         | remove file                               | remove |
| `rm foldername/`                          | remove folder                             | remove |
| `cp filename.txt filename2.txt`           | copy file .                               | copy   |
| `say "hello, what is poetic computation"` | say words out loud                        | speak  |
| `man cd`                                  | show the manual for 'cd'. Press q to quit | define |

## Key Commands
| Key commands         | Description            | Verb     |
|----------------------|------------------------|----------|
| Up + Down Arrow keys | scroll through history | scroll   |
| Tab Key              | autocomplete           | complete |

### Other useful commands
| Other useful codes                                                                | Description                                          |
|-----------------------------------------------------------------------------------|------------------------------------------------------|
| `open ~/.bash_profile`                                                              | opens your bash profile in Text Edit                 |
| `source ~/.bash_profile`                                                            | reloads your bash profile (for after making changes) |
| `export PS1="🌸 \h ✸ \w ⇢ "`                                                        | to change your bash prompt                           |
| `for i in {1..2000}; do printf ' ♡ 📂 → ➩ ➪ ➫ ➬ ➭ ➮  '; done;`                      | to make an emoji for loop                            |                   |
| `bash myfile.sh`                                                                    | to run a bash file                                   |
| `curl sfpc.io`                                                                      | prints the html of a website                         |



### Alias to put in bash_profile

`alias tree="find . -print | sed -e 's;[^/]*/;|;g;s;|; |;g'"` → An alias (shortcut) to put in your .bash_profile for viewing folder tree structure

`alias folderpoetry="for i in {1..2000}; do printf ' ♡ 📂 → ➩ ➪ ➫ ➬ ➭ ➮ '; done;"` → An alias (shortcut) to put in your .bash_profile for automatically run an emoji for loop
