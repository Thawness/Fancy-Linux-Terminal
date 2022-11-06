# Fancy-Linux-Terminal
Stylize your bash terminal like Konsole, Gnome terminal or Terminator for Absolute Beginner.
For Fancy Terminal to work well you also need powerline fonts.

__________________________
Installing powerline fonts :
sudo apt install fonts-powerline

_________________________________________
Setting up powerline fonts for bash
_________________________________________

Open your terminal, logged in as user. 

Open .bashrc file in an editor for example nano by typing the following command 
nano .bashrc

⚠️ Be cautious here. Messing your .bashrc files can have serious consequences. Although doing this is usually safe, but you should backup your .bashrc before making changes.  

Scroll down to the bottom of the file. 
Now, paste the contents of fancy-bash-prompt.sh from FUNCTIONS at line 71 to the end of the script. 

You can even add a comment about your changes, so that you know what changes were not originally part of the file. 
To paste the contents use ctrl+shift+v.

Save and exit the changes.

_________________________________________
Now restart your terminal. And enjoy !!!
(If you have done everything like mentioned, you will see beautified terminal. 
PS : you can use su to edit root user's .bashrc for the same effects as well. 
