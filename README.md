which vim

chmod rwx file

ls -al /bin/vi*

:q // quit

yum install vim
yum install gvim

vim -g

echo " " > test.txt

:e

:q!

i // insert 
esc // to exit 

x // delete


### On Start

```

$ vim
:e <filename>
i // insert

```

### Save
```
:w // write
:saveas <filename> // new file
:q!
```


### Navigating in Command 

```
H  1-LEFT
K  1-UP
J  1-DOWN
L  1-RIGHT

B  FIRST LETTER
E  END LETTER
W  SKIP nth LETTER

$ JUMP-PARAGRAPH

```

### Manipulating Text

```
* In Command Mode

r  # Edit
a  # append
u  # undo
d  # delete
x  # delete 1 character 
```

### Copy , Paste and Replace

```
* In Command Mode

yy # copy
p  # paste
>  # twice to indent
/ex  # find ex 
: #s/ex/EX/gc       # find ex replace with EX , globally and confirm
: 16,23 ! sort -r   # swap 16 to 23 , 23 to 16 and write in vim 
```

### External Commend in VIM

```
:! ls -al ~                   # list all items in pwd in vim command mode 
:r ! cat/root/.bash_profile   # write in vim 
:r ! ls -al /etc | wc -l      # write list all items in etc pipe word cound in vim 
```

