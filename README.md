# CSCI 5828: Homework 2
## Tanya Schulz
##

This document details the commits made and the commands used in the process to create the desired graph for the assignment.

### Commands

**First Edit** <br>
git init <br>
git add . <br>
git commit -m "Commit 0" <br>
gedit README.md <br>

**Second Edit** <br>
git add . <br>
git commit -m "Commit 1" <br>
gedit README.md <br>

**Third Edit** <br>
git add . <br>
git commit -m "Commit 2" <br>
git log - _Find Commit 0 ID_<br> 
git checkout 318b3c433d13ea7934688f592baf048edbe171d3 - _Switch to Commit 0_ <br>
git checkout "bug-fix" <br>
gedit README.md <br>

**Fourth Edit** <br>
git add . <br>
git commit -m "Commit 3" <br>
gedit README.md <br>

**Fifth Edit** <br>
git add . <br>
git commit -m "Commit 4" <br>
git merge master - _Merge bug-fix to master_ <br>
gedit README.md - _fix merge conflict_ <br>

**Sixth Edit** <br>
git add . <br>
git commit -m "Commit 5" <br>
gedit README.md <br>

**Seventh Edit** <br>
git add . <br>
git commit -m "Commit 6" <br>
git log --graph - _Find Commit 4 ID_ <br>
git checkout 1ee8e8a731159e32c1f16b5bfbc06f0f70a29892 - _Switch to Commit 4_ <br>
git checkout -b "bug-fix-experimental" - _Make new branch_ <br>
gedit README.md <br>

**Eighth Edit** <br>
git add . <br>
git commit -m "Commit 7" <br>
gedit README.md <br>

**Ninth Edit** <br>
git add . <br>
git commit -m "Commit 8" <br>
gedit README.md <br>

**10th Edit** <br>
git add . <br>
git commit -m "Commit 9" <br>
git checkout master - _Switch back to master branch for commit 10_ <br>
gedit README.md <br>

**11th Edit**
git add . <br>
git commit -m "Commit 10" <br>
git checkout bug-fix - _Switch back to bug-fix for 11_ <br>
git merge bug-fix experimental - _Merge at Commit 11_ <br>
gedit README.md - _Fix merge conflict_<br>

**12th Edit** <br>
git add . <br>
git commit -m "Commit 11" <br>
gedit README.md <br>

**13th Edit** <br>
git add . <br>
git commit -m "Commit 12" <br>
git checkout master - _Switch back to master for 13_ <br>
git merge bug-fix - _Merge at Commit 13_ <br>
gedit README.md - _Fix merge conflict_ <br>

**14th Edit**
git add README.md
git commit -m "Commit 13" <br>
gedit README.md 

**15th Edit**
git add commit-graph.png - _Add the commit graph_ <br>
git add README.md <br>
git commit -m "Commit 14" <br>








