
# Vim commands

## Basic commands

### Open a file in Normal Mode
```
vim file.name
```

### Command Mode

Enter before a command  
```
shift+:
```

### Exit a Mode
To exit any mode  
```
esc
```  

### Edit
Enter Insert Mode    
```
i
```  
Exit Insert Mode    
```
esc
```  
Save   
```
w
```

### Key Bindings  
Move Right  
```
h
```  
Move Left  
```
l
```  
Move Up  
```
k
```  
Move Down  
```
j
```  
Move Foward a Word  
```
w
```  
Move Back a Word  
```
b
```  
### Quit Vim
Quit   
```
:q
```  
Save and Quit   
```
:wq
```  



### Visual Mode
To enter Visual Mode  
```
v
```  
To enter Visual Line Mode  
```
shift+v
```  

### Open New File
Open blank New File  
```
vim
```  
Save As
```
:w FileName.txt
```  

### Editing
Delete a line  
```
dd
```
Delete Line and Preserve Whitespace  
```
shift+d
```  
Delete a Word and Enter Insert Mode  
At start of Word Type  
```
cw
```  
### Edit Command Combinations Examples
Delete 5 Words  
```
d5w
```  
Change 3 Lines Down and Put into Insert Mode  
```
c3j
```  
### Edit Commands - Action Location Context
Delete Text Within Tags  
``` 
cit
```  
Delete Text Within Curly Braces  
```
ci{
```  
Delete Text Within Double Quotes  
```
ci"
```

### Copy Commands
Enter Visual Mode  
```
v
```  
Then Highlight Line  
Copy  
```
y
```  
Paste  
```
p
```  
Cut
```
dd
```  

### Configure VIM
Syntax Highlighting On  
```
:syntax on
```  
Syntax Highlighting Off
```
:syntax off
```  
Line Numbers On  
```
:set number
```  
Line Numbers Off  
```
:set nonumber
```  
View All Options
```
:help option-list
```  













  
   
