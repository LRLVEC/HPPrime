Notepad++ HP Prime Programming Language Support
August 5, 2016

This adds syntax highlighting, command auto-completion, and function documentation for the 
HP Prime Programming Language (HP PPL) to Notepad++, based on firmware revision 10077.

The original work (most of what is in "userDefineLang.xml") was written back in 2015 by 
Juerg W. Buser at jwbuser@bluewin.ch.

Inspired by this, I created "HP Prime.xml" to add the function documentation for about
800 functions including overloads.  This function documentation came from the extract made
from the calculator on revision 10077 (2016.04.14) by Terje Vallestad, with significant
adaptation made to optimize it for use with Notepad++.

Installation directions:

1. Place "userDefineLang.xml" in any folder
2. In Notepad++, choose "Language" - "Define your language..."
3. Click "Import..." and pick the userDefineLang.xml file
4. Place "HP Prime.xml" in "C:\Program Files (x86)\Notepad++\plugins\APIs"
5. Restart Notepad++
6. In Notepad++, choose "Language" - "HP Prime"

Eric Rechlin
eric@hpcalc.org
http://www.hpcalc.org