This is a theme I made for a clients site.
It is based off of the original Nitelite theme by: Dominic Cerquetti

Tested on XOOPS 2.0.x


zip file contents:
==================
TpM_Theme/
TpM_Theme/images/*
TpM_Theme/theme.html
TpM_Theme/style.css
TpM_Theme/styleMAC.css
TpM_Theme/styleNN.css

newbb_update/
newbb_update/reply.php


Installation:
==============
1. Extract contents of the .zip file.
2. Upload the TpM_Theme folder to the www.yourdomain.xxx/themes/ directory.
3. Replace reply.php in the www.yourdomain.xxx/modules/newbb/ directory with the one provided.
4. Add TpM_Theme to the list of theme choices in the XOOPS Admin Control Panel General Preferences.


Additional Info:
=================
Due to the black background, and white blocks, there is a small problem where the quoted posts shown below the reply form are not visible when replying in the NewBB 2 / cbb 1.14 module.  I have solved that problem by adding a style sheet parameter to the reply.php file in the newbb / cbb folder.

reply.php Change Log:
=========================================
//line 170

echo "<tr><td class='body'><br />".$p_content."<br /></td></tr></table>";

//added style class 'body' to make text visible  (found at the bottom of the style.css file in the theme)
=========================================

****THIS WILL NOT AFFECT ANY OTHER THEMES THAT I AM AWARE OF****

I have tested the reply.php file with the default xoops theme, nitelite, phpkaox and this theme, and the text is visible in all of them after the file is replaced.

QUESTIONS/COMMENTS:
Email: imp96ss{at}gmail{dot}com
PM: Adrock at the xoops.org site

Enjoy!