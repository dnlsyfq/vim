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
: #s/ex/EX/gc  # find ex replace with EX , globally and confirm
```

