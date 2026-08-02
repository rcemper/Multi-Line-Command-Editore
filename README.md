## Multi-Line-Command-Editor

This example is obsolete  
Proper use of ISOS commands achieves the same:  
- ZR (ZREMOVE) to clean your local routine buffer  
- ZI (INSERT) to insert a line   
- ZS (ZSAVE) to name and keep your lines  
- P (PRINT) to show the actual content of the local routine buffer

For more comfortable line editing, you may run the embedded editor **^%**

USER>X ^%
Edit: ?
Enter one of the following
.B   to break a line into two pieces
.C   to change all occurrences of a string
.D   to display s specific range of lines
.F   to file the routine
.FX  to file the routine and exit the editor
.G   to get lines that were put into in a buffer (see .P)
.I   to insert additional lines (or use the TAB key)
.J   to join a line with the next one
.M   to move lines within the routine
.P   to put lines into a buffer (see .G)
.R   to remove one or more lines
.S   to search for all occurrences of a string
tag OR tag+offset  to edit a line
+n   to move down n lines and edit
-n   to move up n lines and edit
""+n to edit the nth line of the program
^globalref  to edit a value stored in a global node
any line of Cache ObjectScript source code, to execute it
     (but if you call another routine before filing this one,
     it will wipe out any edits you have made).
"." use decimal point to move character by character on the current line
" " use space bar to move from space to space on the line
"e" to enter characters, use "." and " " to move to entry point,
    then press "e".  To get out of entry mode, press <RETURN>.
"d" to delete the characters to the end of the word the cursor is on
Backspace: Depending on your terminal settings, backspace will either move
           back character by character, or delete the character at the cursor.
Edit:
  
No magic since this was invented at least 60 years ago
