# SQLformat.py for Notepad++ Python Scripting plugin
This makes SQL code pretty. It is a simple NPP wrap to the python sqlparse library
See: https://github.com/andialbrecht/sqlparse

Version 1.0

## Installation
1. Copy **sqlformat.py** to **\plugins\PythonScript\scripts\** in your NPP folder
2. Copy the **sqlparse** folder to **\plugins\PythonScript\lib\** in your NPP folder
3. Restart NPP. It will now appear as a menu item under Plugins...Python Script...Scripts

## Usage
1. Select the text to minify, or select nothing.
2. Go to the NPP menu, Plugins...Python Script...Scripts...SQLformat and click!
3. If selected text is detected, it mins and replaces the selected text, otherwise the entire contents of current document.
4. Undo is available if you dont like the results

##Credits
sqlparse library Copyright (C) 2008 Andi Albrecht, albrecht.andi@gmail.com
This module is derived from python-sqlparse and is released under the BSD License: http://www.opensource.org/licenses/bsd-license.php.