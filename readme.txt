This is a creation of fork of a repository and below are the steps taken to create a fork:
1. git clone <URL>
where URL is the copied URL from github's repository whose fork branch you want to create

2. After pressing enter, the local fork branch is created on your PC.
3. To sync this fork branch with the actual GitHub repository, follow the below steps:
3.1. $git remote add upstream <actual repository URL>
3.2. $git remote -v

Now you can check the github's repository should have 2 fork branches.
This text is being committed to the master branch and some additions will be made in the fork branch of this repo's master branch.