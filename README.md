MDD - Portfolio 
===================


Local Development

Synch the project master branch to your local development folder before beginning.  Never work directly from the master branch and always create a new branch for yoru local development files.  merge it with the master branch when the new code is final and ready for deployment.

----------
Test changes made in your local development environment on the remote testing environment before making code live.

**Move files to remote StagingServer for testing**
 1. git checkout master 
 3. git add -A
 4. git commit -m 'a description of what is in the commit'
 3. git push StagingServer master

**Test new code on the live site, resolve any issues before continuing.  If issues arise make changes to code and repeat above step.**

## Make Live ##

**Deploy to LiveServer**

 1. git checkout master
 2. git merge master
 3. git add -A
 4. git commit -m 'a description of what is in the commit'
 5. git push LiveServer master

