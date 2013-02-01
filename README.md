*How to compile the NES file*

1.	Clone this repository.
2.	Download x112f at
		http://www.zophar.net/download_file/2991
	and extract into the same repository.
3.	If running Windows, simply run obama.bat. Otherwise:
	a.	Execute
			x112f -$ -l obama.asm
		You will probably need some compatability layer like DOSEMU to run x112f.exe.
	b.	Combine header.bin, obama.bin, and smb.chr in that order to create obama.nes. To do this in a Unix(-like) system such as Mac or Linux, enter this into the terminal:
			cat header.bin obama.bin smb.chr > obama.nes
	or simply run make.

*How to examine the graphics*

Use a graphics editor like YY-CHR for Windows:
	http://www.romhacking.net/download/utilities/119/
For other graphics editors, see
	http://www.romhacking.net/?page=utilities&category=10&platform=&game=&author=&os=&level=&perpage=20&title=&desc=&utilsearch=Go