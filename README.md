                      --------TWO METHODS OF MERGE---------

                 ''''''''' 1) From local GIT /From Terminal '''''''''

1- Go to story folder containing files namely chapter1,chapter2,chapter3. (Can check it by git log)
2- Create a new branch namely "alien-plot" from master/main branch.
3- For this purpose use command "git branch alien-plot".
4- Use "git branch" to check on which branch we currently are. 
5- Use "git checkout alien-plot" to switch to this new branch.
6- Make any change (addition/modification) to existing files in story folder/directory.
7- Now save all changes by using "git add .".
8- Also commit by using "git commit -m 'message'   ".
9- Now "git log" to check all changes and files in the directory.
10- Use "git branch to check on which branch we currently are.
11- Use "git checkout master" to switch to this main branch and create a file namely "chapter4.txt",add it and then commit, also log to check position.
12- Use "git branch to check on which branch we currently are and Use "git checkout alien-plot" to switch to this new branch.
13- We will see if our new changes are good enough to be merged to main. If yes the we go for merge.
14- Again use "git checkout master" to switch to this main branch.
15- Merge by using command "git merge alien-plot". Log to check all changes.
16- Now push to remote by using command "git push origin master -u".
17- We can see all steps in GitHub by going to Insights -> Networks -> Graphs.
