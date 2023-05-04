## Instructions for creating and configuring a repository:
<br/>

* According to your OS, download the Git system https://git-scm.com/downloads

* Register at https://github.com/ in management system that 
you will use to store your project

* Create a new-project folder, navigate to the directory 
and initialize a new public Git repository using this command:
git init

* Сreate a branch development use next command: 
git branch development

* Switch to the branch using the command:
git checkout development

* Copy your remote repository's URL from GitHub

* Add the URL copied, which is your remote repository 
to where your local content from your repository is pushed
 git remote add origin 'your_url_name'
 
* Push the code in your local repository to GitHub git push -u origin master 
(or git push -u origin main)
depending on how the main branch is named

* for a password when connecting to GitHub, you need to create an access token, 
a link to the documentation on how to do this:
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
<br/>
<br/>
<blockquote>
If you don't have any experience with Git, check out the documentation: https://www.git-scm.com/docs
</blockquote>
