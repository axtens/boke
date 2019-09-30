boke
====

Bruce's Own scriptable [Klong](https://www.t3x.org/klong/index.html) Editor

written in B4J. MIT License.

Requires Java 8.

Uses a dynamic menu. Path to menu folder stored in BOLE.INI. JavaScript files are interpreted by Nashorn. 

    MENU
    ├───1-File
    │       1-New.js
    │       2-Open.js
    │       3-Save.js
    │       4-SaveAs.js
    │       5-Close.js
    │       6-Exit.js
    │
    ├───2-Edit
    │       1-Cut.js
    │       2-Copy.js
    │       3-Paste.js
    │       4-Clear.js
    │       5-SelectAll.js
    │
    ├───3-Script
    └───4-Help
            1-About.js

The following objects are exposed to the script engine:
	MessageBox
	MenuItem
	MainForm
	MainText
	gbDirty
	gsVersion
	gsPath
	FileControl
	
See https://docs.oracle.com/javase/8/javafx/api/javafx/scene/control/TextArea.html for methods and properties that can be exercised against MainText.

Execute jar as 

	javaw -jar BOKE.jar

If anyone runs it in Mac OS X, please let me know how it performs (if it does at all.)

The menus are strangely reordered under Linux (or were back in 2014)
