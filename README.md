# FEWD-demo-01

Step 1 - copy files to your local drive
### git clone https://github.com/hammerchu/FEWD-demo-01.git

Step 2 - Make some changes to the repository(e.g. add a text file)

Step 3 - Add the new file to the stage(it will be shown in red when you git status)
### git add *

Step 4 - commit with a comment, if you skip "-m 'comment' ", you will be sent to a text editor
### git commit -m " your comment for this commit "

Step 5 - Add remote server info - skip this if it shows its already exist
### git remote add origin https://github.com/hammerchu/FEWD-demo-01.git

Step 6 - Set url of the server that you want to push to
### git remote set-url origin https://yourGitToken@github.com/hammerchu/FEWD-demo-01.git

Step 7 - Pull info and update your local copy with latest info/files
### git pull (optional)

Step 8 - push! it should show up in the master shortly
### git push -u origin main

When you Comment without -m, NANO editor might show up, Write a meaningful message and use Ctrl+O and Enter to save, and then Ctrl+X to leave the editor.

When you git pull, you are integrating old data with update data and git will do MERGE for you, and it would want you to write comment about the merge in.

And depends on what OS you are using you might be using a VI / Vim editor from UNIX environment

mini-tutorial about VI https://medium.com/@tburgess57/the-vi-text-editor-crash-course-bacdedfe71

How to just save and quite: Press ESC first, then type the following command then ENTER :wq -> write to a file and then quite :q -> quit
