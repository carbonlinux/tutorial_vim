
VIMRC TUTORIAL
=

#Creating a file

	vim filename    - To create a file
	vim -e filename - To edit existing file 

MODES >>
===

Basic mode 

	Normal mode  - Esc Ctrl +[
	visual mode  - v
	insert mode  - iIoOsSaA 
	command mode - : 
Advance mode 

	Xteam mode
	Block mode  - Ctrl +v

Pen to the page
===

	i - Enter insert mode at cursor 
	I - Enter insert mode at first non-blank character
	s - Delete character under cursor and enter insert mode
	S - Delete line and begian insert at the biginning of same line 
	a - Enter insert mode _after_ cursor 
	A - Enter insert mode at the end of the line
	o - Enter insert mode on the next line
	O - Enter insert mode on the above line
	C - Delete from cursor to end of line and begain insert

	This is a test sentence 

Picking up the brush 
===

	ESC
	Ctrl +[

Scanning the canvas 
===
	
	       	 k 
			 ^
	     h<     >l
			 v
             j

" Why hjkl and not jkl;" 

Ans > Because its easy to move fingers around hjkl instent jkl;

They invented mouse , Why not use that?
===

la la la la, I can't hear you


Getting from a to b: Motions
===

Basics: wWbBeE

	w - Forward to the beginning of next word
	W - Forword to the beginning of the next WORD
	b - Backword to the next beginning of the a word
	B - Backword to the next beginning of the a WORD
	e - Forword to the next end of word
	E - Forword to the next end of WORD
	0 - To the zero character of line
	$ - To the end of line 
	^ - First non-bank charactor of line


slightly less basic: fFtT 
	
	[n]f<o> - Forword until (nth) (o) (Inclusive)
	[n]F<o> - Backword until (nth) (o) (Inclusive) 
	[n]t<o> - Forword until (nth) (o) (Exclusive)
	[n]T<o> - Backword until (nth) (o) (Exclusive)
	
abcdefg, abcdefg, abcdefg


Searching 
===

	/ - Forword
	? - Backword
	* - Word under cursor  - forword (bonding)
	g*- Word under cursor  - forword (unbonding)
	# - word under cursor  - backword (bonding)
	g#- word under cursor  - backword (unbonding)
	n - Next result 	- forword
	N - Next result 	- backword


Copy/past
===

	y - yank. Example: yw (yank word)
	p - past after cursor 
	P - past before cursor 

Undoing your changes 
===

	u - undo stuff
	Ctrl +R - redo stuff


