# Ultimate Git Cheat Sheet , Author : PaareshC 
==================================================================================

Remember :
> The only way to master Git is through Practice   

## Configuring you Git 

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git config --global user.name "Username" | Sets the name you want attached to your commit transactions |          
| $ git config --global user.email "Email" | Sets the email you want attached to your commit transactions |             
| $ git config --global color.ui auto | Colorization of command line output |                                 

	
 ## Creating Repository

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git init | Turn an existing directory into a git repository |          
| $ git clone [url] | Clone a repository that already exists on GitHub |             


 ## Operations on Files

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git add <filename> | Adds a file to Staging area |          
| $ git add * | Adds all files to Staging area | 
| $ git commit -a | Stages files automatically |
| $ git log -p | Produces patch text |
| $ git show | Shows various objects |
| $ git diff | Can show the differences in various commits |
| $ git diff --staged | Show all staged files compared to the named commit |
| $ git add -p | Allows a user to interactively review patches to add to the current commit |
| $ git mv | Moves a file |
| $ git rm | Removes a file |
	

## Reverting Changes 

| Syntax | Description |                        
| :--- | :--- |                                                                                
| $ git reset | Resets the repo, throwing away some changes |          
| $ git commit --amend |  Make changes to commits |             
| $ git revert  | New commit which effectively rolls back a previous commit |


