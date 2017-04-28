To install the plugin, simply copy the jar into the "plugins" folder in your Eclipse installation directory and restart Eclipse. To test the plugin, follow the following steps:

1. Make sure that CDT is installed in your Eclipse. If not, then install it first.

2. Make a new C project and import the two source files provided in the "sample" directory (modO.c and modT.c) of this project.

3. Go to Window->Show View->Other->Other, and select "Equivalence Checker Results". You will notice that a console appears with a name "Equivalence Checker Results". All the results will be displayed in this console.

4. Open any one of the files (modO.c or modT.c) by double clicking on it. Note that if a file of project A is opened in the editor, then you cannot use this plugin on files in project B. Thus, just open any file (not necessarily the files you want to use this plugin on) of the project in which the two files are present, in the editor, and you are good to go.

5. Select the two files from the project explorer by using ctrl+click. Note that if you select more than two files, and the plugin will test the last two files for equivalence.

6. Go to the toolbar, and press the square yellow icon. Or, go to the menu bar, click on "Equivalence Check" and select "Perform Equivalence Check".

7. The results will be displayed in the custom console that was opened in step 3. 

8. For ease in viewing the results, expand the console to full screen.

Note: These steps were performed on Eclipse Mars. Some steps may vary depending upon the version you have. For best results, we recommend you use the plugin with Eclipse Mars.
