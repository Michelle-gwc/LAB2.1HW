# LAB2.1HW
Last login: Wed Jul 21 17:46:59 2021 on ttys000
[mhedrington@sol28 ~]$ svnadmin create Lab2
[mhedrington@sol28 ~]$ svn checkout file:///users1/st/mhedrington/Lab2
Checked out revision 0.
[mhedrington@sol28 ~]$ svn add lab.txt
svn: E155007: '/users1/st/mhedrington' is not a working copy
[mhedrington@sol28 ~]$ svnadmin add lab.txt
Unknown command: 'add'
Type 'svnadmin help' for usage.
[mhedrington@sol28 ~]$ cd Lab2
[mhedrington@sol28 Lab2]$ svn add lab.txt
svn: warning: W155010: '/users1/st/mhedrington/Lab2/lab.txt' not found
svn: E200009: Could not add all targets because some targets don't exist
svn: E200009: Illegal target for the requested operation
[mhedrington@sol28 Lab2]$ ls
conf  db  format  hooks  locks  README.txt
[mhedrington@sol28 Lab2]$ touch lab.txt
[mhedrington@sol28 Lab2]$ ls
conf  db  format  hooks  locks  README.txt  lab.txt
[mhedrington@sol28 Lab2]$ vim lab.txt
[michelleh@sol28 Lab2]$ svn add lab.txt
A         something.txt
[mhedrington@sol28 Lab2]$ svn commit -m "pls work"
Adding         lab.txt
Transmitting file data .
Committed revision 1.
[mhedrington@sol28 Lab2]$ vim lab.txt
[mhedrington@sol28 Lab2]$ svn commit -m "pls work"
Sending        lab.txt
Transmitting file data .
Committed revision 2.

![image](https://user-images.githubusercontent.com/20997266/126572491-ca1cec83-af49-413f-ab98-f3e78aa2d3ac.png)
