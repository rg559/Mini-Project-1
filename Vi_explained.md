# Vi Text Editor

## What is Vi Editor?

It is the default editor that comes with the UNIX operating system is called vi (visual editor). Vi is a command line editor included with most linux systems. Vi is a modal editor: it operates in either insert mode (where typed text becomes part of the document) or command mode (where keystrokes are interpreted as commands that control the edit session). Vi works great over slow network ppp modem connections and on systems of limited resources. One can completely utilize vi without departing a single finger from the keyboard. This includes XML, TeX, HTML, and programming languages, but not binary files like Word or OpenDocument. To edit a file, type the command line:

                                                 vi filename

#### There are three modes in vi editor:

1. **Command Mode:**
When vi runs, it takes over the terminal window. Initially, the user is in command mode. In command mode, any keystroke is a command. 

2. **Insert Mode:** When the user presses the key "i", vi switches to insert mode, as the word “– INSERT –” at the bottom of the window reminds you. Everything you type will be inserted as text. To get back from insert to command mode, hit the <esc> key.      

3. **Last line Mode:** When the colon (:) key is pressed, vi switches to last line mode. While in last line mode, a command line is entered at the bottom of the window. It’s executed only when the user presses <enter>. To save what whats inserted, type “:w” (colon followed by lower-case w and <enter>). That will write the file out. If it is a new file, the user will need to provide a file name. This is done by entering “:w filename” followed by <enter>. After this, it will return you to command mode.

## Why use the Vi Editor?

Vim controls look strange to start with but there is a logic to them where you combine movements and actions, so eventually they make a lot of sense. Once you are familiar you can do things quicker than in other editors (and without having to take you hands off the keyboard).The following are the benefits of using Vi editor:

1. Vi is available on any UNIX machine and hence is universal.
2. Vim supports several programming languages and file formats.
3. It's much quicker to use vi for a sudo edit.
4. It is very light-weight.
5. Typing and Navigating around text is easy and productive.
6. Provides rich number of command set.

## Basic Vi Commands:

- **Creating a File:** For creating a new file, type "vi <filename.extension>" So, if we want to create a file named Test.txt we type "vi Test.txt" and press Enter.

- **Editing a File:** For editing a file, press "i" and the editor goes into insert mode, and then the user can edit the document using several shortcut commands provided. Press (esc) key to exit the insert mode.

- **Saving/Quiting a File:** For saving a file, press ":w" and press enter. For closing a file, press ":q" and press enter. You can also press "wq" and press enter to save and quit vi at once.

### Other Useful Vi Commands

1. **Input Mode Commands**

| Command      | Action |
| ----------- | ----------- |
| a      | Insert characters to the right of the cursor|
| A   | Append characters to the current line|
| i      | Insert characters to the left of cursor|
| I      | Insert characters at the beginning of the current line|
| o   |Add a new line after current line|
| O      |Insert a new line above the current line|

2. **Command mode commands**

| Command      | Action |
| ----------- | ----------- |
| :r file      | Import a file into the current file|
| :34 r file   | Import a file into the current file|
| :w	      | Write out the file to save changes|
| :w file      | Write the file to named file|
| :wq   | Save the file exit vi|
| :w!      | Force save the file|
| :q!	   | Quit vi but don’t save changes|
| :g/X/s//x/g	      | Global Search and replace (X=search object x=replace object)|

3. **Vi mode commands**

| Command      | Action |
| ----------- | ----------- |
| k      | Move one line upwards|
| l   | Move one character to the right|
| h      | Move one character to the left|
| w   | Move one word to the right|
| b      | Move one word to the left|
| 1G   | Move to the beginning of the file|
| H      | Move to the top of the current screen|
| M   | Move to the middle of the current screen|
| L      | Move to the bottom of the current screen|
| Ctrl-G	   | Move to the last line in the file|
| Ctrl-L	      | Refresh the screen|
| 5G   | Move to line 5 of the file|
| ZZ      | Save the file exit vi|
| x   | Delete the character at the cursor|
| dd      | Delete the line the cursor is on|
| 10dd   | Delete the 10 lines following the cursor|
| yy      | Yank the current line|
