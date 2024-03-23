# Arkanoid
# Project Title: Arkanoid using C++ with SFML
# Developer: Sourav Banerjee
# Development Tools: DEV C++ with SFML-2.4.2 set up

<h2> How I create  Arkanoid Game Using DEV C++ with SFML setup</h2>
<p>
<h3>SETUP: Download Dev-C++ by visiting sourceforge.net</h3><br><b>
After finishing the installation, Search SFML 2.4.2 version and download ‘GCC 4.9.2 TDM(SJLJ) -64-bit’ and extract that. Go to that folder and copy/cut the ‘SFML-2.4.2’ folder and paste it into ‘C:/”drive.<br>
After that open Dev-C++, goto file->new->project
Select windows application and give it a name.
After clicking on ‘ok’ make a folder in the desktop or other, simply name it and save it.<br>
After that goto ‘project Option’ and set 'Parameters->Linker' as --<br>
-lsfml-audio<br>
-lsfml-graphics<br>
-lsfml-system<br>
-lsfml-window<br>
after that goto 'Directories->Library Directories' ad 'C:\SFML-2.4.2\lib'<br>
then go to 'Directories->Include Directories' ad 'C:\SFML-2.4.2\include'<br><br>

After Setup is successful, one last thing copy all bin files of 
‘SFML-2.4.2/bin/’ and paste it into that Project folder.</p></b>
