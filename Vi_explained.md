# Vi Text Editor

## What is Vi Editor?

It is the default editor that comes with the UNIX operating system is called vi (visual editor). Vi is a command line editor included with most linux systems. Vi is a modal editor: it operates in either insert mode (where typed text becomes part of the document) or command mode (where keystrokes are interpreted as commands that control the edit session). Vi works great over slow network ppp modem connections and on systems of limited resources. One can completely utilize vi without departing a single finger from the keyboard. This includes XML, TeX, HTML, and programming languages, but not binary files like Word or OpenDocument. To edit a file, type the command line:

                                             vi filename

#### There are three modes in vi editor:

1. **Command Mode:**
When vi runs, it takes over the terminal window. Initially, the user is in command mode. In command mode, any keystroke is a command. 

2. **Insert Mode:** When the user presses the key "i", vi switches to insert mode, as the word “– INSERT –” at the bottom of the window reminds you. Everything you type will be inserted as text. To get back from insert to command mode, hit the <esc> key.      

3. **Last line Mode:** When the colon (:) key is pressed, vi switches to last line mode. While in last line mode, a command line is entered at the bottom of the window. It’s executed only when the user presses <enter>. To save what whats inserted, type “:w” (colon followed by lower-case w and <enter>). That will write the file out. If it is a new file, the user will need to provide a file name. This is done by entering “:w filename” followed by <enter>. After this, it will return you to command mode.
