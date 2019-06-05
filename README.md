# Folder Poetry Club
 

### Coding isn’t something that just happens behind your screen. Coding _can be_ a holistic computer practice, a new relationship you have with your computer & your computer habits. from the way you name your files or organize your folders, to completely changing how you perform routine tasks on your computer such as moving a file.


**A New Relationship with Computers**

Old Habits Die Hard or How to Use a (Mac) Computer
   - A folder is an organizational regime imposed on your computer. Let's have fun with it.
   - File types
       - .txt, .html, .css, .js
   - File paths
       - /../../../../../
       - ✨ Sentence activity ✨
   - Naming files and folders
       - All lowercase
       - No spaces
   - [Keyboard shortcuts](https://github.com/melaniehoff/folderpoetry/blob/master/README.md#handy-shortcuts)


# Command line

## Download this folder named [house](https://drive.google.com/drive/folders/19U9G9hNCWdiwFbkfna20nlhDOoB8uHHg) and put it in your computer's home folder 

- Everyone receives a folder and puts it in their **home** directory
    - your home directory on a Mac is represented with a house icon in fnder and by the ~ symbol in terminal. It is a folder that is located near the root of your computer's entire system.
    
### Terminal
    - It is a way to get text based access to your operating system
    - How to get to it?
        - Type Cmd + Spacebar to open Quickfinder
        - type ‘terminal’
### Bash
    - bash is the programming language that we use in the terminal, often one line at a time, but we can also put bash code in a file and run that file


The house as an example folder structure poem because **using the command line and computing in general is a relational practice**. You are never using the command line from a “global” perspective. When you issue commands from the command line, you are doing so, from a particular position within the hierarchy of your computer’s file system.

Similarly, when we are inside a house, we are never simultaneously in the kitchen and the bedroom. If we tried to “get into bed” while in the kitchen, we would not be able to. However if we wanted to wash dishes while standing in the kitchen, we would be able to.
From the command line, if we have navigated to the Desktop folder but try to perform an action on a file that’s inside your home directory, this would not work. You would have to navigate to the home directory by navigating your file path.



# Commands, codes, spells

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






# Folder Poetry Activity

1. After exploring the house together, consider what other narratives you would like to explore with folder structures?
Using the worksheet template or a blank piece of paper, take a few minutes to come up with some ideas that are meaningful or interesting to you. 

Example:
- Fears
- little-buddies

2. Share with a partner


3. Using terminal alone, create the folders and files that make up your folder poem

    - Your files can be .txt, .html, or .sh
    - inside them can be words, ideas, thoughts, feelings, emojis, or bash scripts

4. Upload your folder to:
#### --> --> [Folder Poetry Club](https://drive.google.com/drive/folders/1U8IcCOcDpxOcaweu5qovpnPAM1KQU8VN?usp=sharing)

5. Soon, you should see your folder poem live on [folderpoetry.club[(folderpoetry.club)
