# Keybindings

### State

```
<ESC> -> Normal state

<i>   -> Insert text at the cursor while normal state

<o>   -> Insert text with /n

<a>   -> To append test after the caracter under

A     -> To append text to the end of the line

O     -> Opens the line the cursor is on.
```
### Moving the cursor 
``` 
h  -> (left)

j  -> (down)

k  -> (up)

l  -> (right)

gg -> To go to the beginning of a buffer

G  -> To move to the end of buffer

: <# of the line> <ENTER> -> Return to the # line 
```

### Exit Emacs

```
<ESC> :qa! <ENTER> -> To trash all changes.

<ESC> :wqa <ENTER> -> To save the changes.
```

### Delete
 
```
x -> To delete a character under the cursor 

dw -> To delete from the cursor to the end of word

d$ -> To delete from cursor to the end of a line 

dd -> To delete whole line

p -> To replace the character under the cursor

```
### Format for a Command 

```
[number] command object / command [number] object

where: 
    number -> times repeat
    command -> what to do
    object -> what the command should act upon
```


### Undo
```
u -> undo

Ctrl-R -> undo the undo's 
```
### Change
```
r               -> To replace the character under the cursor 

cw              -> To change the end word

c$              -> To change to the end of a line

:s/old/new      -> To substitute new for the first old on a line

:s/old/new/g    -> To substitute new for all 'old's on a line

:#,#s/old/new/g -> To substitute phrases between two line #'s

:%s/old/new/g   -> To substitute all ocurrences in the file 

:%/old/new/gc   -> To ask for confirmation each time add 'c'

R               -> To replace more than one
```
### Search
```
/ -> followed by phrase to search for the phrase

: -> the same (?)

n -> To search for the same phrase again

N -> To search for the same phrase in the opposite direction

? -> To search for a phrases  in the backwards direction
```
### Debugging
```
% -> Matching parentheses
```

### External Command/Files

```
:<command>! <ENTER> -> external command

:!ls -> To see directory

:w Name -> File that does not exist yet

:!rm -> remove the file

:#,# w FILENAME -> To save part of the file

:r -> To insert the contents of a file
``` 
