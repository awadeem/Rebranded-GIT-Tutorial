# Rebranded-GIT-Tutorial
# Git and GitHub Tutorial

## What is GIT?
Git is the most commonly used version control system. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source. 

So regardless of whether you write code that only you will see, or work as part of a team, Git will be useful for you.
 <img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/c59896f0770215f85ddcbf4e9abace171730d501/Screen%20Shot%202022-03-02%20at%209.49.32%20AM.png" 
     width="500" 
     height="300" />


## What is GitHub?
GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management functionality of Git as well as adding its own features.

 GitHub is a place to share software repositories and collaborate with other developers.
 
## Why do we used GitHub?
* We can **Contribute** to open source projects.
* It is a **Social Network** for developers.
* We can **Track** changes across mutliple versions in our code.
* We can **Showcase** our work to other developers and recruiters.
* We and other developers can **Collaborate** on a single project easily.

## Creating an account on GitHub
To be able to use GitHub, you will have to create an account first. You can do that on their [GitHub Website](https://github.com) and fillout the main form.

<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/1acf39bf0bf926f5b6ba340f8f08a639fda2d37a/Screen%20Shot%202022-03-01%20at%204.51.51%20PM.png" 
     width="400" 
     height="300" />
 
 This form is the first thing that appears if you enter the website without being logged in
 
 You need to inform GitHub which plan you want to use. Choose the free option. The only difference is that you can setup private repositories with the paid plan.
 
 <img src= "https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/main/Screen%20Shot%202022-03-01%20at%205.10.58%20PM.png"
     width="500" 
     height="400" />
     
 ## Creating a GitHub Repository
A Git repository tracks and saves the history of all changes made to the files in a Git project. It saves this data in a directory called .git, also known as the repository folder.

Follow these steps to create a new repository on GitHub:

1.  Log in and browse to the GitHub home page.
    
2. Find the New repository option under the + sign next to your profile picture, in the top right corner.

<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/71e1947b714c26893629cff2f7c04460063b38af/Screen%20Shot%202022-03-01%20at%2011.36.25%20PM.png" 
     width="300" 
     height="250" />" 

3.  Enter a name for your repository, provide a brief description, and choose a privacy setting. 

<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/71e1947b714c26893629cff2f7c04460063b38af/Screen%20Shot%202022-03-01%20at%2011.34.31%20PM.png" 
     width="400" 
     height="300" />" 
     
 4. You can create a README, which is a document describing your projec.
5. Click Create repository.
  
  <img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/853b73bd38266a650b60fc780a20a2008309d01d/Screen%20Shot%202022-03-02%20at%209.32.50%20AM.png" 
     width="400" 
     height="250" />"   
  ## HTTPS and SSH URLs
1. **HTTPS** 

HTTPS is a secure version of HTTP that encrypts data sent between the client and server.
    
1. **SSH** 
 
 SSH means "Secured Shell".It is also a secured version, where data sent between the client and server is encrypted.
 
   ## Clone a Repository
1. On GitHub.com, navigate to the main page of the repository.
2. Above the list of files, click **Code**.  
<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/df9d48c9e8601f1bb5459df1d00ca59f361ee314/Screen%20Shot%202022-03-02%20at%201.50.41%20PM.png" 
     width="400" 
     height="250" /> 
3. To clone the repository using HTTPS, under "Clone with HTTPS", click . To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click .
<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/df9d48c9e8601f1bb5459df1d00ca59f361ee314/Screen%20Shot%202022-03-02%20at%201.51.01%20PM.png" 
     width="400" 
     height="300" /> 
     
   <img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/df9d48c9e8601f1bb5459df1d00ca59f361ee314/Screen%20Shot%202022-03-02%20at%201.51.32%20PM.png" 
     width="400" 
     height="300" /> 
4. Open Terminal.
5. Change the current working directory to the location where you want the cloned directory.
6. Type git clone, and then paste the URL you copied earlier. 
<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/df9d48c9e8601f1bb5459df1d00ca59f361ee314/Screen%20Shot%202022-03-02%20at%201.52.11%20PM.png" 
     width="900" 
     height="50" /> 

7. Press Enter to create your local clone.

<img src="https://raw.githubusercontent.com/awadeem/Rebranded-GIT-Tutorial/df9d48c9e8601f1bb5459df1d00ca59f361ee314/Screen%20Shot%202022-03-02%20at%201.52.26%20PM.png" 
     width="450" 
     height="200" /> 

## Commands for Branching and merging
1. **Creating a local branch**

   $ git checkout -b branchname

2. **Switching between 2 branches**
   
   $ git checkout -
3. **Pushing local branch to remote**

   $ git push -u origin branchname

4. **Deleting a local branch - this won't let you delete a branch that hasn't been merged yet**

   $ git branch -d branchname
   
 5. **Deleting a local branch - this WILL delete a branch even if it hasn't been merged yet!**

    $ git branch -D branchname
