# auto_pastebin

A python script that takes a file and uploads it to ubuntupastebin and returns the url. optionally you can add user name or it will take the uername of the host pc .

# Requirements 
  
  python 3
  
  pyperclip ( pyperclip is required for copying the returned url to clipboard )
  more info https://pypi.org/project/pyperclip/
 
 
 
 # Usage
  python3 auto_pastebin.py "path to your file" "an optional username"
  
  
  ex:
  
    $ python3 auto_pastebin.py uva900.cpp shakil
    > https://pastebin.ubuntu.com/XXXX
    
    or 
    
    $ python3 auto_pastebin.py uva900.cpp 
    > https://pastebin.ubuntu.com/XXXX (this will take the username of your pc account)
    
    
 #Gui is created with pyqt5 
      
      you can open files and edit them before pasting it.
      or you can paste something without even opening the file just by writing in the text field
      
    
    
    
 
