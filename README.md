# Level 3 BTEC IT Diploma Unit 17: Project Planning with I.T
###### Thomas Broughton, Faisal Zulfiqar, Yousef Aljasem, Thomas Elvidge

Repository for storing project files including HTML files, CSS files and Images.


## UPDATE LOG:

#### 11/01/2019
Added the project specifications to the repository file.

Added two more buttons.

Added hover over fade effect.

Added introduction to homepage.

Adjusted font styling for easier readability.

Adjusted page overflow to enable scrolling.

Added unblurred background image underneath blurred background to counter vignette around the window edges.


## ISSUES KNOWN IN CURRENT VERSION:

Background partially scrolls with web page despite background: fixed and position: static being in 
the source code. This is believed to be because of the scale transition used in order to hide the vignette via hidden overflow. Removing the overflow altogether fixes the problem but lowers the background quality due to the clear background behind the blurred one. Workaround needed.
